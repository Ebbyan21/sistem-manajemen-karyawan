# Perancangan Aplikasi Jasa Titip Berbasis Web

[![GitHub followers](https://img.shields.io/github/followers/ebbyan21?label=Follow&style=social)](https://github.com/ebbyan21)
[![GitHub Repo stars](https://img.shields.io/github/stars/ebbyan21/[NAMA-REPOSITORI-ANDA]?style=social)](https://github.com/ebbyan21/[NAMA-REPOSITORI-ANDA]/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ebbyan21/[NAMA-REPOSITORI-ANDA]?style=social)](https://github.com/ebbyan21/[NAMA-REPOSITORI-ANDA]/network)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

[cite_start]Proyek ini merupakan bukti laporan dari kegiatan IT Booth Camp Universitas Bina Sarana Informatika, yang dikembangkan oleh **Kelompok 1**[cite: 3, 5]. [cite_start]Judul proyek ini adalah "Perancangan Aplikasi Jasa Titip Berbasis Web"[cite: 2, 451].

## 📖 Latar Belakang

[cite_start]Layanan jasa titip (jastip) yang saat ini banyak dijalankan secara manual melalui media sosial memiliki sejumlah kendala, seperti sulitnya mengelola pesanan dalam jumlah besar, potensi kesalahan pencatatan, dan kurangnya transparansi[cite: 128, 129]. [cite_start]Untuk mengatasi permasalahan tersebut, kami mengembangkan sebuah aplikasi jastip berbasis web yang bertujuan untuk memfasilitasi proses penitipan barang secara lebih aman, transparan, dan terstruktur[cite: 118]. [cite_start]Aplikasi ini dirancang untuk meningkatkan efisiensi, akurasi data, keamanan transaksi, serta memberikan pengalaman pengguna yang lebih baik bagi **Penitip** (konsumen) maupun **Traveler** (penyedia jasa titip)[cite: 131, 502].

## ✨ Fitur Utama

-   [cite_start]**Akses Multi-Peran**: Sistem mendukung tiga jenis pengguna: Admin, Penitip, dan Traveler, dengan dasbor dan hak akses yang disesuaikan untuk setiap peran[cite: 168, 542].
-   [cite_start]**Manajemen Pesanan**: Pengguna dapat membuat, memantau, dan mengelola pesanan secara *real-time*, mulai dari pesanan dibuat hingga selesai[cite: 157, 529].
-   [cite_start]**Verifikasi Traveler**: Admin memiliki kewenangan untuk melakukan verifikasi profil Traveler guna menjamin keamanan dan kredibilitas penyedia jasa[cite: 419].
-   [cite_start]**Dasbor dan Laporan**: Dasbor interaktif untuk setiap peran guna memantau statistik, riwayat transaksi, dan rekapitulasi penghasilan[cite: 171, 178, 545].
-   [cite_start]**Antarmuka Responsif**: Desain antarmuka yang modern dan ramah pengguna, dapat diakses melalui berbagai perangkat seperti desktop, tablet, maupun *smartphone*[cite: 177, 551].

## 🚀 Rangkaian Teknologi

[cite_start]Berikut adalah teknologi yang digunakan dalam pengembangan aplikasi ini[cite: 372]:

-   [cite_start]**Framework**: PHP Laravel, Tailwind CSS, Bootstrap[cite: 373, 1202].
-   [cite_start]**Bahasa Pemrograman**: PHP, JavaScript[cite: 376, 1205].
-   [cite_start]**Database**: MySQL[cite: 374, 1203].
-   [cite_start]**Text Editor**: Visual Studio Code[cite: 375, 1204].
-   [cite_start]**Server**: Localhost (Lingkungan Pengembangan Lokal)[cite: 377, 1206].

## 📸 Tampilan Aplikasi

Berikut adalah beberapa tangkapan layar dari aplikasi Jasa Titip.

*(Catatan: Unggah gambar-gambar aplikasi ke repositori Anda, kemudian ganti placeholder di bawah ini dengan tautan gambar yang sesuai).*

![Dasbor Admin]([TAUTAN-GAMBAR-DASBOR-ADMIN])
*Dasbor Admin untuk memantau seluruh aktivitas sistem.*

![Halaman Beranda]([TAUTAN-GAMBAR-BERANDA])
*Halaman beranda yang informatif bagi pengguna.*

![Proses Pemesanan]([TAUTAN-GAMBAR-FORM-PESANAN])
*Formulir untuk membuat pesanan titipan baru.*

![Dasbor Traveler]([TAUTAN-GAMBAR-DASBOR-TRAVELER])
*Dasbor khusus untuk Traveler memantau pesanan dan penghasilan.*

## ⚙️ Rincian Fitur

### **Fitur Admin**
-   [cite_start]**Manajemen Pengguna (CRUD)**: Admin dapat menambah, melihat, mengubah, dan menghapus data pengguna (Penitip dan Traveler)[cite: 418, 1479].
-   [cite_start]**Verifikasi Traveler**: Menerapkan sistem verifikasi oleh Admin untuk memastikan kredibilitas Traveler[cite: 419, 1480].
-   [cite_start]**Kelola Pesanan**: Admin memiliki hak akses untuk memantau, mengelola, dan mengubah seluruh pesanan yang masuk[cite: 420, 1481].
-   [cite_start]**Dasbor Pemantauan**: Menyediakan dasbor interaktif untuk melihat statistik keseluruhan sistem[cite: 421, 1482].

### **Fitur Penitip (Customer)**
-   [cite_start]**Registrasi dan Profil**: Pengguna dapat melakukan registrasi dan login secara aman, serta mengelola informasi profil pribadi[cite: 423, 1484].
-   [cite_start]**Membuat Pesanan**: Memungkinkan Penitip untuk membuat pesanan baru melalui formulir daring[cite: 424, 1485].
-   [cite_start]**Pemantauan Status Pesanan**: Penitip dapat melacak status pesanan secara *real-time*[cite: 425, 1486].
-   [cite_start]**Riwayat Transaksi**: Halaman riwayat untuk melihat semua transaksi dan pesanan yang pernah dibuat[cite: 426, 1487].

### **Fitur Traveler**
-   [cite_start]**Registrasi dan Verifikasi**: Traveler dapat mendaftar dan melengkapi profil untuk selanjutnya diverifikasi oleh Admin[cite: 428, 1489].
-   [cite_start]**Melihat dan Mengambil Pesanan**: Traveler dapat melihat daftar pesanan yang tersedia dan memilih untuk mengambil pesanan tersebut[cite: 429, 1490].
-   [cite_start]**Dasbor Penghasilan**: Dasbor khusus untuk memantau total pendapatan dari ongkos jasa setiap pesanan yang berhasil diselesaikan[cite: 430, 1491].
-   [cite_start]**Riwayat Pesanan**: Melihat riwayat lengkap pesanan yang telah diselesaikan untuk keperluan rekapitulasi[cite: 431, 1493].

## 🛠️ Panduan Instalasi

### **A. Instalasi melalui Git (Direkomendasikan)**
1.  **Clone Repositori**: `git clone https://github.com/ebbyan21/[NAMA-REPOSITORI-ANDA].git`
2.  **Masuk ke Direktori**: `cd [NAMA-REPOSITORI-ANDA]`
3.  **Install Dependensi**: `composer install`
4.  **Salin Berkas Environment**: `copy .env.example .env`
5.  **Generate Kunci Aplikasi**: `php artisan key:generate`
6.  **Konfigurasi Database**: Atur kredensial pada berkas `.env`. Buat sebuah database dengan nama `db_jastipku`.
7.  **Jalankan Migrasi Database**: `php artisan migrate --seed`
8.  **Install Dependensi NPM**: `npm install`
9.  **Compile Aset**: `npm run dev`
10. **Jalankan Server**: `php artisan serve`

### **B. Instalasi melalui Berkas ZIP**
1.  **Unduh dan Ekstrak**: Unduh berkas ZIP dari repositori dan ekstrak ke dalam direktori server lokal Anda (misalnya: `htdocs`).
2.  **Buka Terminal**: Buka terminal atau *command prompt* di dalam direktori proyek.
3.  Ikuti langkah 3 sampai 10 dari metode instalasi Git di atas.
4.  **Akses Aplikasi**: Setelah menyalakan server (misalnya XAMPP), buka peramban dan akses melalui `http://localhost/[nama-folder-proyek]/public`.

## 👨‍💻 Tim Pengembang (Kelompok 1)

[cite_start]Proyek ini dikerjakan dan disusun oleh tim dari Universitas Bina Sarana Informatika[cite: 17].

| Nama                          | NIM        |
| ----------------------------- | ---------- |
| Aulia Rahman                  | 19231330   |
| Adelia Arasi                  | 19230553   |
| Muhammad Zessy                | 19230067   |
| Muhammad Febriansyah          | 19231821   |
| Muhamad Fikri Firdaus         | 73230021   |
| Bimo Utomo                    | 73230040   |
| Mohammad Alfarizhi Ridho P.   | 73230062   |
| Aldo Wijaya                   | 73230026   |
| Sendi Awaludin                | 17230088   |
| Surya Daffa Fauzi Khoerudin   | 17230348   |
[cite_start]_Sumber: [cite: 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]_

## 📞 Kontak

Untuk informasi lebih lanjut, pertanyaan, atau potensi kolaborasi, silakan hubungi pengembang:

-   **Nama**: Muhammad Febriansyah
-   **GitHub**: [ebbyan21](https://github.com/ebbyan21)
-   **LinkedIn**: [Muhammad Febriansyah](https://www.linkedin.com/in/muhammad-febriansyah-77914131b)
-   **Instagram**: [@ebbyan_](https://www.instagram.com/ebbyan_)

---
<p align="center">
  Terima kasih telah mengunjungi repositori ini.
</p>
