# Coda Test Job Report

Source: VRT - Product v5 / Test Jobs  
Job: 11/27/2025 - integrasi neon uji x neutron  
Total items: 21  
Passed: 11  
Failed: 10  

## Media Attachments

Saved folder: `C:\tmp\coda-media`

| Row | Test Case | Files |
| --- | --- | --- |
| 1 | Verifikasi navigasi ke halaman impor Neon Uji | `row-01-image-1.webp`, `row-01-image-2.webp` |
| 15 | Verifikasi aktivasi button "Hasilkan Penilaian" | `row-15-image-1.webp`, `row-15-image-2.webp` |
| 18 | User melakukan import skor (siswa) IRT | `row-18-image-1.webp`, `row-18-image-2.webp` |
| 21 | User mempublikasikan nilai | `row-21-image-1.webp` |

Videos found: none.

## Test Items

### 1. Verifikasi navigasi ke halaman impor Neon Uji

Status: Failed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menampilkan halaman input penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"

Details:
Issue: Button import penilaian tidak sesuai dengan UI design

Ekspektasi:

ADDITIONAL ISSUE:
Button secara UI memang sudah sesuai, tapi tidak muncul dropdown dan langsung mengarahkan ke import manual

Media:
- `C:\tmp\coda-media\row-01-image-1.webp`
- `C:\tmp\coda-media\row-01-image-2.webp`

### 2. User melakukan input penilaian manual

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menampilkan halaman Penilaian yang sudah berjalan (alur manual)

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Penilaian Manual"

### 3. Verifikasi dropdown pemilihan Tipe Hasil Penilaian

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menampilkan tipe hasil penilaian
- User dapat memilih tipe hasil penilaian
- User dapat meng-klik tipe hasil penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian

### 4. Verifikasi dropdown pemilihan Jenjang Studi

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menampilkan jenjang studi
- User dapat memilih jenjang studi
- User dapat meng-klik jenjang studi

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan

### 5. Verifikasi dropdown pemilihan Jenis  Penilaian

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menampilkan jenis penilaian
- User dapat memilih jenis penilaian
- User dapat meng-klik jenis penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan
9. Klik dropdown "Pilih Jenis Penilaian"
10. Pilih salah satu jenis penilaian

### 6. Verifikasi dropdown pemilihan Siswa

Status: Failed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menampilkan nama siswa
- User dapat memilih nama siswa
- User dapat meng-klik nama siswa

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan
9. Klik dropdown "Pilih Jenis Penilaian"
10. Pilih salah satu jenis penilaian
11. Klik dropdown "Pilih Siswa"
12. Pilih salah satu siswa

### 7. Verifikasi dropdown pemilihan Kelompok Belajar

Status: Failed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menampilkan jenis penilaian kelompok belajar
- User dapat memilih nama kelompok belajar
- User dapat meng-klik nama kelompok belajar

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan
9. Klik dropdown "Pilih Jenis Penilaian"
10. Pilih jenis penilaian Kelompok Belajar
11. Klik dropdown "Kelompok Belajar"
12. Pilih salah satu kelompok belajar

Details:
Issue: Inkonsistensi antara State Checkbox dan Tampilan 'Selected Value' pada Dropdown Kelompok Belajar

Deskripsi: Ketika user klik checkbox, tanda centang (checkmark) muncul tapi datanya tidak terpilih dan tidak ter-render sebagai chip/tag (label berlatar belakang merah) di dalam kolom input

### 8. Verifikasi dropdown pemilihan Tipe Penilaian

Status: Failed  
Case: Positive  
Priority: Medium

Expected result:
- Sistem menampilkan tipe penilaian
- User dapat memilih tipe penilaian
- User dapat meng-klik tipe penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan
9. Klik dropdown "Pilih Jenis Penilaian"
10. Pilih salah satu jenis penilaian
11. Klik dropdown "Pilih Siswa"
12. Pilih salah satu siswa
13. Klik dropdown "Tipe Penilaian"
14. Pilih salah satu tipe penilaian

Details:
Issue: Button 'Lanjutkan' gagal nonaktif kembali setelah input tipe penilaian dikosongkan

Deskripsi: Button 'Lanjutkan' tidak memperbarui statusnya menjadi disabled ketika user menghapus pilihan tipe penilaiannya

Langkah Reproduce:
1. Pilih Kelompok Belajar
2. Pilih Tipe Penilaian
3. Klik batalkan pemilihan tipe penilaian (icon silang) pada tipe penilaian yang sebelumnya dipilih

### 9. Verifikasi aktivasi button "Lanjutkan"

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Button Lanjutkan aktif jika semua field penilaian belum terisi
- Button Lanjutkan non-aktif jika semua field penilaian belum terisi

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan
9. Klik dropdown "Pilih Jenis Penilaian"
10. Pilih salah satu jenis penilaian
11. Klik dropdown "Pilih Siswa"
12. Pilih salah satu siswa
13. Klik dropdown "Tipe Penilaian"
14. Pilih salah satu tipe penilaian
15. Perhatikan button "Lanjutkan"

### 10. Verifikasi navigasi ke halaman NIlai

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Sistem men-generate komponen penilaian, quiz, tipe penilaian, cabang

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan
9. Klik dropdown "Pilih Jenis Penilaian"
10. Pilih salah satu jenis penilaian
11. Klik dropdown "Pilih Siswa"
12. Pilih salah satu siswa
13. Klik dropdown "Tipe Penilaian"
14. Pilih salah satu tipe penilaian
15. Klik button "Lanjutkan"

### 11. Verifikasi button "Batalkan"

Status: Passed  
Case: Negative  
Priority: Low

Expected result:
- Sistem membatalkan proses import nilai
- Sistem mengarahkan user kembali ke halaman koleksi penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Klik dropdown "Tipe Hasil Penilaian"
6. Pilih salah satu tipe penilaian
7. Klik dropdown "Jenjang Studi"
8. Pilih salah satu jenjang pendidikan
9. Klik dropdown "Pilih Jenis Penilaian"
10. Pilih salah satu jenis penilaian
11. Klik dropdown "Pilih Siswa"
12. Pilih salah satu siswa
13. Klik dropdown "Tipe Penilaian"
14. Pilih salah satu tipe penilaian
15. Klik button "Batalkan"

### 12. Memverifikasi pemetaan Komponen Penilaian ke Quiz (Non-IRT)

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menyiapkan quiz yang akan diambil skornya
- Komponen penilaian yang tadi dipilih akan menunjukkan dat quiz yang telah dipetakan

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih salah satu jenis penilaian
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz non-IRT yang akan diimpor
13. Klik button Terapkan Nilai

### 13. Memverifikasi pemetaan Komponen Penilaian ke Quiz (IRT)

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Sistem menyiapkan quiz yang akan diambil skornya
- Komponen penilaian yang tadi dipilih akan menunjukkan dat quiz yang telah dipetakan

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih salah satu jenis penilaian
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz IRT yang akan diimpor
13. Klik button Terapkan Nilai

### 14. Verifikasi aktivasi button "Terapkan Nilai"

Status: Passed  
Case: Positive  
Priority: Low

Expected result:
- Button Terapkan Nilai aktif jika semua field penilaian belum terisi
- Button Terapkan Nilai non-aktif jika semua field penilaian belum terisi

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih salah satu jenis penilaian
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz yang akan diimpor
13. Perhatikan button Terapkan Nilai

### 15. Verifikasi aktivasi button "Hasilkan Penilaian"

Status: Failed  
Case: Positive  
Priority: Medium

Expected result:
- Button Hasilkan Penilaian aktif jika semua field penilaian belum terisi
- Button Hasilkan Penilaian non-aktif jika semua field penilaian belum terisi

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih salah satu jenis penilaian
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz yang akan diimpor
13. Klik button Terapkan Nilai
14. Pastikan semua quiz pada komponen penilaian terisi
15. Perhatikan button Hasilkan Penilaian

Details:
Issue: Button 'Hasilkan Penilaian' aktif walaupun quiz pada komponen penilaian tidak diisi lengkap

Ekspektasi: Walaupun hanya salah satu quiz yang dipilih, button tetap nonaktif

Media:
- `C:\tmp\coda-media\row-15-image-1.webp`
- `C:\tmp\coda-media\row-15-image-2.webp`

### 16. User melakukan import skor (siswa) non-IRT

Status: Failed  
Case: Positive  
Priority: High

Expected result:
- Sistem memproses data penilaian
- berhasil menginputkan skor
- SIstem mengarahkan kembali user ke halaman koleksi penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih jenis penilaian "Siswa"
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz non-IRT yang akan diimpor
13. Klik button Terapkan Nilai
14. Pastikan semua quiz pada komponen penilaian terisi
15. Klik button Hasilkan Penilaian
16. Klik button Publikasikan nilai

Details:
Issue: Gagal mengimport dengan alert message "Tidak ada quiz attempt yang ditemukan" padahal user siswa sudah mengerjakan quiz

### 17. User melakukan import skor (kelompok belajar) non-IRT

Status: Failed  
Case: Positive  
Priority: High

Expected result:
- Sistem memproses data penilaian
- berhasil menginputkan skor
- SIstem mengarahkan kembali user ke halaman koleksi penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih jenis penilaian "Kelompok Belajar"
8. Pilih salah satu kelompok belajar
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz non-IRT yang akan diimpor
13. Klik button Terapkan Nilai
14. Pastikan semua quiz pada komponen penilaian terisi
15. Klik button Hasilkan Penilaian
16. Klik button Publikasikan nilai

Details:
Issue: Muncul error message "Tidak ada student yang ditemukan" padahal ada siswanya

### 18. User melakukan import skor (siswa) IRT

Status: Failed  
Case: Positive  
Priority: Medium

Expected result:
- Sistem memproses data penilaian
- berhasil menginputkan skor
- SIstem mengarahkan kembali user ke halaman koleksi penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih jenis penilaian "Siswa"
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz IRT yang akan diimpor
13. Klik button Terapkan Nilai
14. Pastikan semua quiz pada komponen penilaian terisi
15. Klik button Hasilkan Penilaian
16. Klik button Publikasikan nilai

Details:
Issue: Terdapat kolom score

Ekspektasi: Tidak ada kolom score

Media:
- `C:\tmp\coda-media\row-18-image-1.webp`
- `C:\tmp\coda-media\row-18-image-2.webp`

### 19. User melakukan import skor (kelompok belajar) IRT

Status: Failed  
Case: Positive  
Priority: Low

Expected result:
- Sistem memproses data penilaian
- berhasil menginputkan skor
- SIstem mengarahkan kembali user ke halaman koleksi penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih jenis penilaian "Kelompok Belajar"
8. Pilih salah satu kelompok belajar
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klip dropdown quiz dan pilih salah satu quiz IRT yang akan diimpor
13. Klik button Terapkan Nilai
14. Pastikan semua quiz pada komponen penilaian terisi
15. Klik button Hasilkan Penilaian
16. Klik button Publikasikan nilai

### 20. Melakukan proses import skor saat Data attempt tidak ditemukan

Status: Passed  
Case: Negative  
Priority: Low

Expected result:
- Sistem menampilkan pop-up "data sedang diproses"
- Setelah selesai diproses, sistem menampilkan error message jika data siswa tidak ditemukan

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih salah satu jenis penilaian
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz yang akan diimpor
13. Klik button Terapkan Nilai
14. Pastikan semua quiz pada komponen penilaian terisi
15. Pastikan juga data attempt tidak ada
16. Klik button Hasilkan Penilaian

### 21. User mempublikasikan nilai

Status: Failed  
Case: Positive  
Priority: Low

Expected result:
- User kembali ke halaman koleksi penilaian
- Sistem menampilkan data-data penilaian

Steps:
1. User login ke aplikasi Neutron
2. Masuk ke halaman menu Penilaian
3. Klik button +Penilaian pada hover
4. Klik "Import dari Neon Uji"
5. Pilih salah satu tipe penilaian
6. Pilih salah satu jenjang pendidikan
7. Pilih jenis penilaian "Siswa"
8. Pilih salah satu siswa
9. Pilih salah satu tipe penilaian
10. Klik button "Lanjutkan"
11. Pada tab Nilai, pilih salah satu Data Komponen Penilaian
12. Klik dropdown quiz dan pilih salah satu quiz yang akan diimpor
13. Klik button Terapkan Nilai
14. Pastikan semua quiz pada komponen penilaian terisi
15. Klik button Hasilkan Penilaian
16. Klik button Publikasikan nilai

Details:
Issue: Whitespace terlalu besar

Ekspektasi: Whitespace tidak terlalu besar

Additional Issue: Ketika button close pada notifikasi di klik, modal penilaian otomatis ikut tertutup

Ekspektasi: Walaupun notifikasi di close, modal penilaian tidak terganggu

Media:
- `C:\tmp\coda-media\row-21-image-1.webp`
