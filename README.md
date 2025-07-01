[![github-follow](https://img.shields.io/github/followers/ebbyan21?label=Follow&logoColor=purple&style=social)](https://github.com/ebbyan21)
[![GitHub stars](https://img.shields.io/github/stars/ebbyan21/sistem-manajemen-karyawan.svg?style=social)](https://github.com/ebbyan21/sistem-manajemen-karyawan/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ebbyan21/sistem-manajemen-karyawan.svg)](https://github.com/ebbyan21/sistem-manajemen-karyawan/network)
[![license](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://choosealicense.com/licenses/mit/)

# Sistem Manajemen Karyawan Berbasis Laravel

Aplikasi ini merupakan sebuah sistem informasi berbasis web yang dirancang untuk membantu perusahaan dalam mengelola data dan aktivitas karyawan secara efisien. Dibangun menggunakan Laravel 10, aplikasi ini mencakup berbagai fitur yang disesuaikan untuk setiap tingkatan peran dalam organisasi, mulai dari karyawan hingga direktur.

---

## Fitur Utama

Fitur aplikasi dibagi berdasarkan peran pengguna untuk memastikan keamanan dan relevansi data yang diakses.

### **Dashboard Direktur**
- **Executive Summary:** Menampilkan ringkasan data tingkat tinggi seperti total karyawan, jumlah manajer, dan jumlah karyawan yang sedang cuti pada hari berjalan.
- **Analytics Dashboard:** (Fitur dalam pengembangan) Menyajikan data produktivitas dan tren SDM dalam bentuk grafik.

### **Panel Human Resources (HR)**
- **Manajemen Karyawan:** Fungsi CRUD (Create, Read, Update, Delete) untuk seluruh data karyawan di perusahaan.
- **Manajemen Role & Jabatan:** Mengelola peran dan posisi setiap karyawan.
- **Manajemen Absensi & Cuti:** (Fitur dalam pengembangan) Mengelola dan menarik laporan absensi serta cuti seluruh perusahaan.
- **Manajemen Payroll:** (Fitur dalam pengembangan) Mengelola komponen dan proses penggajian.
- **Broadcast Pengumuman:** (Fitur dalam pengembangan) Mengirim pengumuman ke seluruh atau departemen tertentu.

### **Panel Manajer**
- **Dashboard Tim:** Menampilkan ringkasan data anggota tim, termasuk jumlah bawahan dan jumlah pengajuan yang menunggu persetujuan.
- **Pusat Persetujuan (Approval Center):** Menyetujui atau menolak pengajuan cuti dari anggota tim.
- **Manajemen Laporan Kerja Tim:** (Fitur dalam pengembangan) Melihat dan memberikan umpan balik terhadap laporan kerja anggota tim.

### **Dasbor Karyawan**
- **Profil Pribadi:** Melihat data personal, posisi, dan atasan langsung.
- **Pengajuan Cuti:** Mengajukan permohonan cuti secara digital dan melihat sisa kuota cuti.
- **Riwayat Pengajuan:** Melacak status dan riwayat semua pengajuan yang pernah dibuat (cuti, lembur, klaim).
- **Laporan Kerja:** (Fitur dalam pengembangan) Mengirim laporan kerja harian atau mingguan kepada atasan.

---

## Teknologi yang Digunakan
- **Backend:** Laravel 10
- **Frontend:** Blade Template Engine, Bootstrap 5
- **Database:** MySQL

---

## Panduan Instalasi & Setup

Berikut adalah langkah-langkah untuk menjalankan proyek ini di lingkungan lokal Anda:

1.  **Clone Repositori**
    ```bash
    git clone [https://github.com/ebbyan21/sistem-manajemen-karyawan.git](https://github.com/ebbyan21/sistem-manajemen-karyawan.git)
    cd sistem-manajemen-karyawan
    ```

2.  **Instal Dependensi Composer**
    ```bash
    composer install
    ```

3.  **Konfigurasi Lingkungan**
    Salin berkas `.env.example` menjadi `.env`.
    ```bash
    cp .env.example .env
    ```

4.  **Generate Application Key**
    ```bash
    php artisan key:generate
    ```

5.  **Konfigurasi Database**
    Buka berkas `.env` dan sesuaikan kredensial database Anda (DB_DATABASE, DB_USERNAME, DB_PASSWORD).

6.  **Jalankan Migrasi & Seeder**
    Perintah ini akan membuat semua tabel dan mengisi data awal (termasuk data login) ke dalam database.
    ```bash
    php artisan migrate:fresh --seed
    ```

7.  **Jalankan Server Pengembangan**
    ```bash
    php artisan serve
    ```

8.  **Akses Aplikasi**
    Buka peramban (browser) Anda dan kunjungi `http://127.0.0.1:8000`.

---

## Akun Demo

Anda dapat menggunakan akun berikut untuk mencoba setiap peran setelah proses instalasi selesai. **Password** untuk semua akun adalah `password`.

-   **Direktur:** `direktur@kantor.com`
-   **HR:** `hr@kantor.com`
-   **Manajer:** `manajer@kantor.com`
-   **Karyawan:** `budi@kantor.com`

---

## Kontak Penulis

Jika Anda memiliki pertanyaan atau ingin terhubung, silakan hubungi saya melalui:

-   **GitHub:** [ebbyan21](https://github.com/ebbyan21)
-   **LinkedIn:** [Muhammad Febriansyah](https://www.linkedin.com/in/muhammad-febriansyah-77914131b)
-   **Instagram:** [@ebbyan_](https://www.instagram.com/ebbyan_)
-   **X (Twitter):** [@ebbyan_](https://twitter.com/ebbyan_)
-   **Tiktok:** [@ebbyan_](https://tiktok.com/ebbyan_)

---

## Lisensi
Proyek ini dilisensikan di bawah [Lisensi MIT](https://choosealicense.com/licenses/mit/).
