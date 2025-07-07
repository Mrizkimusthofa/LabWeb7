# Dokumentasi Praktikum CodeIgniter 4 - Versi Parafrase

## Praktikum 1: Implementasi Framework PHP (CodeIgniter)

### Proses Implementasi

#### 1. Konfigurasi Awal
- Mengkonfigurasi ekstensi PHP yang diperlukan untuk menjalankan CodeIgniter
  ![Konfigurasi PHP](https://github.com/user-attachments/assets/7f228043-0f23-4669-a8cd-5afab7fe5ed9)

#### 2. Pemasangan CodeIgniter 4
- Melakukan unduhan dan ekstraksi file CodeIgniter 4 ke direktori kerja
  ![Instalasi Framework](https://github.com/user-attachments/assets/213d3973-26bf-483d-8c72-cabdb6ac1c69)

#### 3. Eksekusi Command Line Interface
- Menjalankan aplikasi melalui terminal menggunakan CLI
  ![CLI Execution](https://github.com/user-attachments/assets/4e56d28a-967e-432c-80ef-1402fe3c95ea)

#### 4. Konfigurasi Mode Debug
- Mengonfigurasi environment dengan mengubah file env menjadi .env
  ![Environment Setup](screenshots/environment.png)

#### 5. Pembuatan Route Baru
- Menambahkan routing baru dalam file Routes.php
  ![Route Configuration](https://github.com/user-attachments/assets/e02cf28f-befb-452e-901c-c81ec8986391)

#### 6. Implementasi Controller
- Membuat controller Page.php untuk menangani request
  ![Controller Implementation](screenshots/page.png)

#### 7. Pembuatan View
- Membuat view about.php untuk tampilan halaman
  ![View Creation](screenshots/about.png)

#### 8. Implementasi Layout Web dengan CSS
- Membuat template header dan footer dengan styling
  ![CSS Styling](screenshots/style.png)
  ![Header Template](screenshots/header.png)
  ![Footer Template](screenshots/footer.png)

### Hasil Implementasi

Telah berhasil menyelesaikan implementasi kode program untuk seluruh menu yang tersedia di Controller Page, sehingga seluruh navigasi pada header dapat menampilkan halaman dengan layout yang konsisten.

Halaman yang telah dibuat:
- Halaman About: ![About Page](screenshots/aboutpage.png)
- Halaman Contact: ![Contact Page](screenshots/contactpage.png)
- Halaman FAQ: ![FAQ Page](screenshots/FAQpage.png)
- Halaman Terms of Service: ![Terms Page](screenshots/Tspage.png)
- Modifikasi controller: ![Controller Update](screenshots/Pge.png)

**Output Final Praktikum 1**
![Final Result](screenshots/HasilP1.png)

## Praktikum 2: Pengembangan Framework dengan CRUD

### Tahapan Pengembangan

#### 1. Pembuatan Database
- Membuat database lab_ci4 beserta tabel artikel
  ![Database Setup](screenshots/praktikum2/database.png)

#### 2. Konfigurasi Database Connection
- Mengatur file konfigurasi .env untuk koneksi database
  ![Database Config](screenshots/praktikum2/2.png)

#### 3. Implementasi Model
- Membuat ArtikelModel.php untuk mengelola data artikel
  ![Model Implementation](screenshots/praktikum2/3.png)

#### 4. Implementasi Controller
- Membuat controller Artikel.php untuk menangani request CRUD
  ![Controller CRUD](screenshots/praktikum2/4.png)

#### 5. Implementasi View
- Membuat view index.php pada folder artikel
  ![View Index](screenshots/praktikum2/5.png)

#### 6. Penambahan Data Artikel
- Menambahkan data artikel melalui query SQL
  ![Data Entry](screenshots/praktikum2/6.png)

#### 7. Implementasi Detail Artikel dan Routing
- Membuat method view() di controller dan file detail.php
  ![Detail View Method](screenshots/praktikum2/71.png)
  ![Detail View File](screenshots/praktikum2/72.png)
  ![Detail Display](screenshots/praktikum2/73.png)

#### 8. Implementasi Menu Admin
- Membuat method admin_index() dan view admin_index.php
  ![Admin Method](screenshots/praktikum2/81.png)
  ![Admin View](screenshots/praktikum2/82.png)
  ![Admin Interface](screenshots/praktikum2/83.png)
  ![Admin Panel](screenshots/praktikum2/84.png)
  ![Admin Features](screenshots/praktikum2/85.png)

#### 9. Fitur Tambah Artikel
- Implementasi method add() dan form_add.php
  ![Add Method](screenshots/praktikum2/91.png)
  ![Add Form](screenshots/praktikum2/92.png)

#### 10. Fitur Edit Artikel
- Implementasi method edit() dan form_edit.php
  ![Edit Method](screenshots/praktikum2/101.png)
  ![Edit Form](screenshots/praktikum2/102.png)

#### 11. Fitur Hapus Artikel
- Implementasi method delete() untuk menghapus data
  ![Delete Method](screenshots/praktikum2/11.png)

### Pengembangan Tambahan

1. Implementasi CSS untuk Panel Admin
   ![Admin CSS](screenshots/praktikum2/css.png)
2. Fitur Upload Gambar
   ![Upload Feature](screenshots/praktikum2/fitur1.png)
3. Fitur Pencarian Artikel
   ![Search Feature](screenshots/praktikum2/fitur2.png)

**Output Final Praktikum 2**
![Result 1](screenshots/praktikum2/ss1.png)
![Result 2](screenshots/praktikum2/ss2.png)
![Result 3](screenshots/praktikum2/ss3.png)

## Praktikum 3: Implementasi View Layout dan View Cell

### Tahapan Implementasi

#### 1. Pembuatan Layout Utama
- Membuat folder layout dan file main.php sebagai template utama
  ![Main Layout](screenshots/praktikum3/1.png)

#### 2. Modifikasi File View
- Mengubah berbagai file view untuk menggunakan layout template yang baru
  ![View Update 1](screenshots/praktikum3/21.png)
  ![View Update 2](screenshots/praktikum3/22.png)
  ![View Update 3](screenshots/praktikum3/23.png)
  ![View Update 4](screenshots/praktikum3/24.png)
  ![View Update 5](screenshots/praktikum3/25.png)

#### 3. Penambahan Field Tanggal
- Menambahkan kolom created_at pada tabel artikel
  ![Date Field](screenshots/praktikum3/3.png)

#### 4. Implementasi View Cell Class
- Membuat folder Cells dan file ArtikelTerkini.php
  ![View Cell Class](screenshots/praktikum3/4.png)

#### 5. Implementasi View untuk View Cell
- Membuat folder components dan file artikel_terkini.php
  ![View Cell Template](screenshots/praktikum3/5.png)

#### 6. Pengembangan - Kategori Artikel
- Menambahkan kolom kategori dan implementasi filter berdasarkan kategori
  ![Category Feature](screenshots/praktikum3/61.png)

### Analisis dan Pembahasan

#### 1. Keunggulan Penggunaan View Layout dalam Pengembangan Aplikasi

Penggunaan View Layout memberikan beberapa keuntungan signifikan:

1. **Keseragaman Tampilan**: View Layout menjamin bahwa seluruh halaman memiliki struktur dan desain yang seragam.
2. **Pemisahan Concern**: Memisahkan antara konten spesifik halaman dan struktur layout umum, membuat kode lebih terorganisir.
3. **Reusabilitas**: Template layout yang sama dapat digunakan di berbagai halaman tanpa duplikasi kode.
4. **Kemudahan Maintenance**: Perubahan pada layout hanya perlu dilakukan di satu tempat dan akan terimplementasi di semua halaman.
5. **Efisiensi Pengembangan**: Developer dapat fokus pada konten halaman tanpa perlu mengulang pembuatan struktur layout.

#### 2. Perbandingan View Cell dengan View Konvensional

**View Konvensional**:
- Digunakan untuk menampilkan halaman utuh atau bagian halaman
- Dipanggil dengan `return view('nama_view', $data)`
- Biasanya tidak mengandung logika bisnis
- Dapat digunakan kembali dengan include/extend
- Berbagi konteks dengan view yang memanggilnya

**View Cell**:
- Digunakan untuk komponen UI yang dapat digunakan ulang dan bersifat modular
- Dipanggil dengan `<?= view_cell('Namespace\\Class::method', $params) ?>`
- Dapat memiliki logika bisnis sendiri
- Dirancang khusus untuk komponen yang digunakan berulang
- Memiliki konteks tersendiri yang terisolasi

**Output Final Praktikum 3**
![Final Result](screenshots/praktikum3/ss3.png)

## Praktikum 4: Implementasi Sistem Autentikasi

### Tahapan Implementasi

#### 1. Pembuatan Tabel User
- Membuat tabel user pada database lab_ci4
  ![User Table](screenshots/praktikum4/mysql.png)

#### 2. Implementasi Model User
- Membuat UserModel.php untuk mengelola data user
  ![User Model](screenshots/praktikum4/2.png)

#### 3. Implementasi Controller User
- Membuat User.php dengan method login dan logout
  ![User Controller](screenshots/praktikum4/3.png)

#### 4. Implementasi View Login
- Membuat form login di folder user
  ![Login View 1](screenshots/praktikum4/41.png)
  ![Login View 2](screenshots/praktikum4/42.png)

#### 5. Implementasi Database Seeder
- Membuat UserSeeder untuk data dummy
  ![User Seeder](screenshots/praktikum4/52.png)

#### 6. Implementasi Auth Filter
- Membuat filter Auth.php untuk proteksi halaman
  ![Auth Filter 1](screenshots/praktikum4/61.png)
  ![Auth Filter 2](screenshots/praktikum4/62.png)
  ![Auth Filter 3](screenshots/praktikum4/63.png)

#### 7. Implementasi Fungsi Logout
- Menambahkan tombol logout pada interface
  ![Logout Function](screenshots/praktikum4/71.png)

### Pengembangan Tambahan

1. Implementasi Halaman Register
   ![Register 1](screenshots/praktikum4/im11.png)
   ![Register 2](screenshots/praktikum4/im12.png)
   ![Register 3](screenshots/praktikum4/im13.png)

2. Implementasi Dashboard Admin
   ![Dashboard 1](screenshots/praktikum4/im21.png)
   ![Dashboard 2](screenshots/praktikum4/im22.png)
   ![Dashboard 3](screenshots/praktikum4/im23.png)
   ![Dashboard 4](screenshots/praktikum4/im24.png)

3. Perbaikan Tampilan dengan CSS
   ![CSS Improvement](screenshots/praktikum4/im31.png)

**Output Final Praktikum 4**
![Login Screen](screenshots/praktikum4/login.png)
![Dashboard](screenshots/praktikum4/dashboard.png)
![Admin Layout](screenshots/praktikum4/layoutadmin.png)

## Praktikum 5: Implementasi Pagination dan Pencarian

### Tahapan Implementasi

#### 1. Implementasi Pagination
Memodifikasi Controller Artikel dan View admin_index.php untuk menampilkan data secara bertahap

![Pagination 1](screenshots/praktikum5/1.png)
![Pagination 2](screenshots/praktikum5/2.png)
![Pagination 3](screenshots/praktikum5/3.png)

#### 2. Implementasi Pencarian
Memodifikasi method `admin_index` untuk menambahkan fitur pencarian dan link pagination, serta menambahkan form pencarian pada view

![Search 1](screenshots/praktikum5/4.png)
![Search 2](screenshots/praktikum5/5.png)
![Search 3](screenshots/praktikum5/6.png)
![Search 4](screenshots/praktikum5/7.png)

#### 3. Pengembangan Tambahan
Menambahkan fitur pencarian berdasarkan kategori dan menampilkan jumlah data yang ditemukan

![Enhancement 1](screenshots/praktikum5/8.png)
![Enhancement 2](screenshots/praktikum5/9.png)

**Output Final Praktikum 5**
![Admin Portal](screenshots/praktikum5/adminportal.png)

## Praktikum 6: Implementasi Upload File Gambar

### Tahapan Implementasi

#### 1. Modifikasi Method add() pada Controller Artikel
Mengupdate Controller Artikel untuk menangani upload file

![Upload Controller](screenshots/praktikum6/1.png)

#### 2. Modifikasi form_add.php
Menambahkan field input file dan menyesuaikan tag form dengan menambahkan encrypt type

![Upload Form](screenshots/praktikum6/2.png)

#### 3. Pengujian Upload File
Melakukan testing upload file melalui menu tambah artikel

![Upload Test 1](screenshots/praktikum6/31.png)
![Upload Test 2](screenshots/praktikum6/32.png)

**Output Final Praktikum 6**
![Upload Result](screenshots/praktikum6/artikel.png)

## Praktikum 7: Implementasi Relasi Tabel dan Query Builder

### Objektif
- Memahami konsep relasi antar tabel dalam database
- Implementasi relasi One-to-Many
- Melakukan query dengan join tabel menggunakan Query Builder
- Menampilkan data dari tabel yang memiliki relasi

### Tahapan Implementasi

#### 1. Pembuatan Tabel Kategori
Membuat tabel kategori dengan struktur yang sesuai

```sql
CREATE TABLE kategori (
    id_kategori INT(11) AUTO_INCREMENT,
    nama_kategori VARCHAR(100) NOT NULL,
    slug_kategori VARCHAR(100),
    PRIMARY KEY (id_kategori)
);
```

![Category Table](screenshots/praktikum7/1.png)

#### 2. Penambahan Foreign Key
Menambahkan kolom id_kategori ke tabel artikel dan membuat foreign key constraint

![Foreign Key 1](screenshots/praktikum7/2.png)
![Foreign Key 2](screenshots/praktikum7/3.png)
![Foreign Key 3](screenshots/praktikum7/4.png)

#### 3. Implementasi Model Kategori
Membuat KategoriModel.php untuk mengelola data kategori

![Category Model](screenshots/praktikum7/5.png)

#### 4. Modifikasi Model Artikel
Menambahkan method getArtikelDenganKategori() untuk melakukan JOIN

![Article Model](screenshots/praktikum7/6.png)

#### 5. Modifikasi Controller Artikel
Mengupdate controller untuk menggunakan relasi tabel

![Controller Update](screenshots/praktikum7/7.png)

#### 6. Modifikasi View
Mengupdate semua view untuk menampilkan kategori

![View Update 1](screenshots/praktikum7/8.png)
![View Update 2](screenshots/praktikum7/9.png)
![View Update 3](screenshots/praktikum7/10.png)
![View Update 4](screenshots/praktikum7/11.png)
![View Update 5](screenshots/praktikum7/12.png)
![View Update 6](screenshots/praktikum7/13.png)

#### 7. Pengujian
Hasil testing menunjukkan semua fitur berjalan dengan baik

![Testing 1](screenshots/praktikum7/15.png)
![Testing 2](screenshots/praktikum7/16.png)

**Output Final Praktikum 7**
![Final Result](screenshots/praktikum7/17.png)

## Praktikum 8: Implementasi AJAX di CodeIgniter 4

### Tahapan Implementasi

#### 1. Penambahan Library jQuery
Menambahkan jQuery ke project dengan menyalin file ke folder `public/assets/js/`

![jQuery Addition](screenshots/praktikum8/1.png)

#### 2. Implementasi AJAX Controller
Membuat controller baru bernama `AjaxController.php` untuk menangani request AJAX

![AJAX Controller](screenshots/praktikum8/2.png)

#### 3. Implementasi View
Membuat view untuk menampilkan data artikel dengan AJAX

![AJAX View 1](screenshots/praktikum8/4.png)
![AJAX View 2](screenshots/praktikum8/5.png)

#### 4. Pengembangan Tambahan
Menambahkan fitur pencarian dan filter kategori dengan AJAX

**Output Final Praktikum 8**
![AJAX Result](screenshots/praktikum8/ss.png)

## Praktikum 9: Implementasi AJAX Pagination dan Search

### Tahapan Implementasi

#### 1. Persiapan Data
Menambahkan lebih banyak data artikel untuk testing pagination

![Data Preparation](screenshots/praktikum9/1.png)

#### 2. Modifikasi Controller Artikel
Mengupdate method admin_index() untuk mendukung AJAX request

![Controller AJAX](screenshots/praktikum9/2.png)

#### 3. Modifikasi View admin_index.php
Mengubah view untuk menggunakan AJAX dengan fitur lengkap

![View AJAX](screenshots/praktikum9/3.png)

### Fitur yang Diimplementasikan
- Search real-time
- Filter kategori
- Pagination tanpa reload
- Sorting kolom

**Output Final Praktikum 9**
![AJAX Pagination](screenshots/praktikum9/ss.png)

## Praktikum 10: Implementasi API

### Tahapan Implementasi

#### 1. Persiapan
Menginstall Postman dan mengatur konfigurasi database

![API Preparation](screenshots/praktikum10/1.png)

#### 2. Implementasi REST Controller
Membuat file `Post.php` untuk menangani operasi CRUD API

![REST Controller](screenshots/praktikum10/2.png)

#### 3. Implementasi Routing
Menambahkan rute resource di `app/Config/Routes.php`

![API Routing](screenshots/praktikum10/3.png)
![Route Check](screenshots/praktikum10/4.png)

#### 4. Pengujian dengan Postman

**Menampilkan semua data (GET)**:
![GET All](screenshots/praktikum10/5.png)

**Menambahkan data (POST)**:
![POST Data](screenshots/praktikum10/6.png)

**Menampilkan data berdasarkan ID (GET)**:
![GET by ID](screenshots/praktikum10/7.png)

**Mengubah data (PUT)**:
![PUT Data](screenshots/praktikum10/8.png)

**Menghapus data (DELETE)**:
![DELETE Data](screenshots/praktikum10/9.png)

### Kesimpulan

Praktikum ini berhasil mengimplementasikan REST API dengan CodeIgniter 4 untuk operasi CRUD. API telah diuji menggunakan Postman dan semua fungsi (GET, POST, PUT, DELETE) berjalan dengan baik dan sesuai dengan standar RESTful API.
