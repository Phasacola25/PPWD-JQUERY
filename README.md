# Praktikum Pemrograman Web Dasar

Repositori ini dibuat khusus untuk keperluan *deployment* tugas mata kuliah Praktikum Pemrograman Web Dasar. Repositori ini didedikasikan secara terpisah dari arsip repositori utama praktikum (PPWD2026) guna menjaga struktur *file* di *root directory* tetap bersih dan menghindari konflik repositori (*nested git*).

## Mekanisme Deployment
Sistem *deploy* pada repositori ini diotomatisasi menggunakan **GitHub Actions**. 

Setiap kali terdapat pembaruan kode yang di-*push* ke *branch* `main`, sebuah *workflow* akan berjalan untuk mengirimkan *webhook* ke server **aaPanel** dosen pengampu. Konfigurasi ini memungkinkan kode terbaru langsung ditarik (di-*pull*) oleh server dan *website* diperbarui secara *real-time* tanpa perlu unggah *file* manual.

## Teknologi yang Digunakan
* HTML, CSS, PHP
* Git & GitHub (Source Code Management)
* GitHub Actions (Continuous Deployment)

## Informasi Mahasiswa
* **Nama:** Phasacola Grey Kalista
* **Angkatan:** 2025
* **Program Studi:** Sistem Informasi
* **Instansi:** Universitas Tanjungpura