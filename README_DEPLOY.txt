SAKUNALAR — Paket GitHub Pages (UKin IPS Kelas IX)
=================================================

ISI PAKET
- index.html : Website SAKUNALAR lengkap dengan gambar, komik, logo, maskot,
               Dashboard Guru, rubrik LKM & Presentasi, dekoder dan nilai akhir.
- .nojekyll : Penanda agar GitHub Pages menayangkan file secara statis.
- README_DEPLOY.txt : Petunjuk ini.

CARA DEPLOY
1. Ekstrak ZIP ini di komputer (jangan unggah ZIP sebagai satu file).
2. Buat repository GitHub PUBLIC, misalnya SAKUNALAR-UKIN.
3. Buka repository > Add file > Upload files.
4. Unggah index.html dan .nojekyll dari hasil ekstrak (posisi ROOT repository).
5. Klik Commit changes.
6. Buka Settings > Pages > Build and deployment:
   Source: Deploy from a branch; Branch: main; Folder: /(root); Save.
7. Alamat situs: https://USERNAME.github.io/SAKUNALAR-UKIN/
   Ganti USERNAME dengan username GitHub dan nama repository bila berbeda.

CATATAN PENTING
- Semua aset gambar utama sudah tertanam (embedded) di index.html. Tidak ada
  folder gambar lain yang diperlukan untuk menampilkan website.
- Ukuran index.html sekitar 21,7 MiB, di bawah batas unggah file GitHub via
  antarmuka web (25 MiB per file).
- Font Quicksand diambil dari Google Fonts; bila offline, font alternatif
  perangkat digunakan.
- Nilai tersimpan lokal pada browser perangkat. Data penilaian tidak otomatis
  tersinkron antar HP/laptop. Impor kode dan simpan cadangan JSON / rekap CSV.
- Website GitHub Pages PUBLIC. Jangan menyertakan data pribadi murid atau
  cadangan hasil nilai ke repository publik.
- File LKM dan Exit Ticket final tetap disimpan/cetak secara terpisah; tidak
  perlu diunggah untuk menjalankan website.

PENGECEKAN SESUDAH DEPLOY
- Beranda dan seluruh menu navigasi berfungsi.
- Komik enam kelompok tampil tanpa gambar rusak.
- Presentasi fullscreen dan timer dapat dipakai.
- Penguatan enam kartu dan simulasi uang saku berfungsi.
- Asesmen kelompok menghasilkan kode, Dashboard Guru dapat memproses kode.
- Rubrik LKM/Presentasi, Total Poin /38, Nilai Akhir /100, unduhan CSV,
  dan cadangan JSON bekerja.
