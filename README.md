# Laporan Tugas Praktikum Pemrograman Mobile
**Nama:** Khaila salsa marfah bilqis
**NIM:** [H1D023014]
**Pertemuan:** 10 (CRUD 1)

---

## A. Pengujian Backend (Rest API)
Berikut adalah bukti bahwa REST API CodeIgniter 4 telah berjalan dan berhasil diuji menggunakan Postman.

### 1. Registrasi & Login
Proses pendaftaran user baru dan pengambilan token akses.
![Bukti Registrasi](screenshots_api/registrasi.png)
![Bukti Login](screenshots_api/login.png)

### 2. CRUD Produk
Proses Create (Tambah), Read (Lihat), dan Delete (Hapus) data produk.
![Bukti Tambah Produk](screenshots_api/create_produk.png)
![Bukti List Produk](screenshots_api/list_produk.png)

---

## B. Implementasi UI Flutter (Personalisasi)
Berikut adalah tampilan aplikasi Flutter yang telah dimodifikasi dengan menambahkan identitas pada setiap Action Bar.

### 1. Login & Registrasi
Halaman autentikasi pengguna.
* **Login Page:** Meminta input email & password. Judul diubah menjadi "Login Khaila".
* **Registrasi Page:** Form pendaftaran user. Judul diubah menjadi "Registrasi Khaila".

![Screenshot Login](screenshots_app/login_khaila.png)
![Screenshot Registrasi](screenshots_app/registrasi_khaila.png)

### 2. Manajemen Produk
Halaman pengelolaan data barang.
* **List Produk:** Menampilkan daftar barang dummy. Judul: "List Produk Khaila".
* **Detail Produk:** Menampilkan info lengkap barang. Judul: "Detail Produk Khaila".
* **Form Produk:** Halaman dinamis untuk Tambah/Ubah barang. Judul menyesuaikan, misal "TAMBAH PRODUK KHAILA".

![Screenshot List Produk](screenshots_app/list_khaila.png)
![Screenshot Detail Produk](screenshots_app/detail_khaila.png)
![Screenshot Form Produk](screenshots_app/form_khaila.png)

---

## C. Penjelasan Kode Singkat
1.  **Model (`lib/model`)**: Berisi class `Produk`, `Login`, dan `Registrasi` untuk memetakan format JSON dari API ke objek Dart.
2.  **UI (`lib/ui`)**: Berisi tampilan antarmuka. Menggunakan widget seperti `TextFormField` untuk input dan `ElevatedButton` untuk aksi. Logika validasi form diterapkan menggunakan `GlobalKey<FormState>`.