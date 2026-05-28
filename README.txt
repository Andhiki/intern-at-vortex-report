===================================================
TEMPLATE LATEX LAPORAN MBKM/MAGANG (STANDAR UGM)
===================================================

Struktur Folder (Rapi):
.
├── main.tex
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
│   └── bibliography
│       └── references.bib
├── assets
│   ├── images
│   │   └── diagram.jpg
│   └── LOA.pdf
└── examples
    └── prism_demo.tex

Naming Convention:
1. Nama file pakai huruf kecil + snake_case.
2. Penomoran bab ditulis eksplisit di nama file (contoh: bab_1_pendahuluan.tex).
3. File style, referensi, dan aset dipisah per folder agar maintainable.

Cara Kompilasi Laporan:
Agar daftar isi, daftar gambar, tabel, dan daftar pustaka saling terhubung dengan benar, jalankan urutan berikut di terminal (atau cukup tekan "Recompile" jika menggunakan Overleaf):

1. pdflatex main.tex
2. bibtex main
3. pdflatex main.tex
4. pdflatex main.tex

Catatan Penggunaan:
1. Ganti \rule{...} dengan \includegraphics{...} pada file sampul dan bab terkait.
2. Simpan semua gambar ke dalam folder assets/images.
3. Edit detail mahasiswa dan dosen di src/front_matter/sampul.tex dan src/front_matter/pengesahan.tex.
4. Pastikan setiap bab berisi narasi laporan aktual dan tidak menyisakan teks dummy.