# Intern Report

LaTeX source for final MBKM internship report. Report is built from `intern-report.tex` and split into reusable source files under `src/`.

Compiled PDF: [intern-report.pdf](intern-report.pdf)

## Project Structure

```text
.
├── intern-report.tex
├── intern-report.pdf
├── src
│   ├── styles
│   │   └── report_style.sty
│   ├── front_matter
│   │   ├── sampul.tex
│   │   ├── pengesahan.tex
│   │   └── kata_pengantar.tex
│   ├── chapters
│   │   ├── bab_1_pendahuluan.tex
│   │   ├── bab_2_profil_dan_tinjauan.tex
│   │   ├── bab_3_pengembangan_fitur_dan_modul_proyek.tex
│   │   ├── bab_4_pengujian_unit_dan_modul_proyek.tex
│   │   ├── bab_5_kemampuan_berkomunikasi.tex
│   │   └── bab_6_penutup.tex
│   ├── appendices
│   │   └── lampiran.tex
│   ├── bibliography
│   │   └── references.bib
│   └── forms
│       └── form_penilaian_mbkm_content_only.tex
├── assets
│   ├── images
│   ├── coda-test-items.json
│   ├── coda-test-report.md
│   └── *.pdf
└── examples
    └── prism_demo.tex
```

## Build

Recommended:

```bash
latexmk -pdf -interaction=nonstopmode intern-report.tex
```

Force full rebuild:

```bash
latexmk -pdf -g -interaction=nonstopmode intern-report.tex
```

Manual fallback:

```bash
pdflatex intern-report.tex
bibtex intern-report
pdflatex intern-report.tex
pdflatex intern-report.tex
```

## Editing Guide

- Main entry point: `intern-report.tex`.
- Report styling and packages: `src/styles/report_style.sty`.
- Cover page: `src/front_matter/sampul.tex`.
- Approval sheet and preface are present but currently commented out in `intern-report.tex`.
- Chapter content lives in `src/chapters/`.
- Appendix content lives in `src/appendices/lampiran.tex`.
- Bibliography entries live in `src/bibliography/references.bib`.
- Images and supporting PDFs live in `assets/`.

## Naming Notes

- Use lowercase `snake_case` for source files.
- Keep chapter numbers explicit in chapter filenames.
- Store images under `assets/images/`.
- Keep generated build files out of source edits unless the final PDF needs to be updated.

## Current Report Scope

The report documents MBKM internship work as a Frontend Developer Intern at PT Vortex Buana Edumedia, mainly covering:

- Neon Interfaces documentation and design library work.
- Import Nilai Neon Uji feature in the Pendidikan repository.
- Manual testing, issue iteration, and unit-test design references.
- Communication and coordination activities during internship.
