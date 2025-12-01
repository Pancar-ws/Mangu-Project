# **OUTLINE IDEAL PENGERJAAN PROYEK ROOMIFY (10 November – 14 Desember)**

Struktur outline mengikuti template resmi proposal:
1. **Abstrak**
2. **BAB I – Pendahuluan**
3. **BAB II – Tinjauan Pustaka**
4. **BAB III – Rencana Proyek**
5. **BAB IV – Penutup**
6. **Lampiran**
---
#  **GAMBARAN BESAR TIMELINE (10 November – 14 Desember — 5 Minggu Efektif)**

| Minggu       | Tanggal   | Fokus Utama                                           |
| ------------ | --------- | ----------------------------------------------------- |
| **Minggu 1** | 10–16 Nov | BAB I, BAB II, Requirement Analysis, Perancangan Awal |
| **Minggu 2** | 17–23 Nov | ERD, Use Case, Mockup, BAB III versi awal             |
| **Minggu 3** | 24–30 Nov | Implementasi Laravel (CRUD + DB + Autentikasi)        |
| **Minggu 4** | 1–7 Des   | Fitur Pencarian/Filter, UI Tailwind, Dashboard Admin  |
| **Minggu 5** | 8–14 Des  | Testing, Bug Fixing, Dokumentasi, Penyusunan Final    |

---
#  **OUTLINE DETAIL MINGGUAN**
---
#  **MINGGU 1 (10 – 16 November)**
##  _Output Minggu Ini:_
- BAB I lengkap
- BAB II (50% selesai)
- Dokumen Requirement Analysis (SRS)
- Rumusan fitur lengkap
- Daftar kebutuhan teknis + non-teknis
---
### **1. Penyusunan Dokumen Proposal**
#### **A. Abstrak (Draft Awal)**
Isi abstrak terdiri dari:
- masalah utama pencarian kos
- solusi Roomify
- teknologi yang digunakan (Laravel, SQLite, Tailwind, Breeze)
- metode waterfall
- target output aplikasi

> _Abstrak dapat diperbaiki di akhir, tetapi draf awal wajib dibuat._
---
### **2. Penyusunan BAB I – Pendahuluan (Final)**
Isi lengkap:
- Latar Belakang
- Rumusan Masalah
- Batasan Masalah
- Tujuan Proyek    
- Manfaat Proyek

Semua isi sudah ada di laporan sebelumnya → tinggal dipolish.

---
### **3. Penyusunan BAB II – Tinjauan Pustaka (50%)**
Kerjakan:
1. Teori:
    - Sistem Informasi
    - PHP
    - Laravel
    - SQLite
    - Tailwind CSS
    - Laravel Breeze        
2. _**Tambahkan penelitian/proyek sejenis**_  
    Template **wajib meminta ini**.

Contoh:
- Sistem informasi kos (Rachmawati, 2017)
- Aplikasi pendataan kamar kos berbasis web
- Perbandingan Laravel vs PHP Native (Endra, 2021)
---
### **4. Requirement Analysis (SRS)**
Buat dokumen ringkas berisi:
- Aktor (Admin, Pengunjung)
- Kebutuhan fungsional (CRUD kos, filter, login admin, dll.)
- Kebutuhan non-fungsional (responsif, keamanan, kecepatan, ketersediaan)
- Alur proses utama (flow sederhana)
---
# 🟦 **MINGGU 2 (17 – 23 November)**
##  _Output Minggu Ini:_
- ERD final
- Use Case Diagram
- Mockup UI
- BAB II (final 100%)
- BAB III (versi awal)
---
### **1. Desain Sistem**

#### **A. ERD (Entity Relationship Diagram)**
Minimal berisi tabel:
- kos
- fasilitas
- kategori
- users (admin)
#### **B. Use Case Diagram**
Aktor:
- Admin    
- Pengunjung

Use case:
- mengelola data kos
- login
- melihat kos
- melakukan filter
- melihat detail kos
#### **C. Mockup UI**
Gunakan Figma / gambar sederhana:
- halaman utama
- halaman detail kos
- halaman dashboard admin
- form tambah kos
---
### **2. Penyusunan BAB II (Final)**
Tambahkan:
- penelitian terdahulu
- gap analysis (kekurangan penelitian sebelumnya → alasan Roomify perlu dibuat)
---
### **3. Penyusunan BAB III – Rencana Proyek (Draft)**
Isi:
- Tempat & waktu (10 Nov – 14 Des)
- Metode Waterfall (tabel fase → output)
- Uraian kegiatan
- Draft jadwal proyek
---
# 🟦 **MINGGU 3 (24 – 30 November)**
##  _Output Minggu Ini:_
- Project Laravel jadi
- Migration, Model, Controller
- CRUD lengkap
- Autentikasi Laravel Breeze
---
### **1. Setup Proyek Laravel**
- `laravel new roomify`
- Setup SQLite → `.env`
- Install Breeze → `php artisan breeze:install`
---
### **2. Implementasi Backend**
#### **A. Migration & Model**
- kos
- user (admin)
- fasilitas (opsional)
#### **B. CRUD**
- Create
- Read
- Update
- Delete
#### **C. Blade View Sederhana**
Tidak perlu rapi dulu.

---
### **3. Dokumentasi untuk BAB III**
- simpan screenshot hasil implementasi
- catat kendala & solusi
---
# 🟦 **MINGGU 4 (1 – 7 Desember)**
##  _Output Minggu Ini:_
- Fitur pencarian & filtering
- Dashboard admin lengkap
- Tailwind CSS final
- UI responsif
---
### **1. Fitur Pencarian dan Filtering**
Filter berdasarkan:
- harga
- lokasi
- fasilitas    
- kategori

Gunakan:
`$query = Kos::query();`

---
### **2. Dashboard Admin**
- tabel data kos
- form edit / delete
- validasi input
---
### **3. Penerapan Tailwind CSS**
- responsive grid
- card kos
- navbar
- dark/light mode (opsional)
---
### **4. Persiapan Lampiran**
- screenshot halaman
- hasil filtering
- dashboard admin
---
# 🟦 **MINGGU 5 (8 – 14 Desember)**
##  _Output Minggu Ini:_
- Testing lengkap
- Bug fixing
- BAB III final
- BAB IV final
- Lampiran final
- Dokumen Final Project siap dikumpulkan
---
### **1. Verification & Testing**
Buat tabel testing:
- uji setiap fitur    
- catat bug + perbaikan

Metode:
- unit testing ringan
- UAT (user acceptance testing)

---
### **2. BAB III – Versi Final**
Isi lengkap:
- Tempat & waktu
- Uraian kegiatan
- Metode waterfall + diagram    
- Jadwal kegiatan (tabel + gantt chart)

Tambahkan Gantt Chart ke BAB III (bukan lampiran).

---
### **3. BAB IV – Penutup**
Isi:
- Kesimpulan
- Harapan

Tambahkan kalimat:
- fitur lanjutan (rating, maps, booking online)
---
### **4. Lampiran Final**
Lampiran wajib:
1. Matriks Jadwal
2. Gantt Chart
3. ERD
4. Use Case
5. Mockup
6. Screenshot aplikasi
7. Hasil testing