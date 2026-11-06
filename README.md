# ReAndKhay Taylor – Sistem Pemesanan Jasa Jahit

Aplikasi desktop berbasis Java yang dibuat untuk memenuhi Tugas Besar mata kuliah **Pemrograman Berorientasi Objek (PBO)**.

**ReAndKhay Taylor** merupakan aplikasi sederhana untuk mengelola pemesanan jasa jahit yang menghubungkan pelanggan dengan penjahit. Aplikasi ini menyediakan fitur pengelolaan pesanan, informasi pelanggan, status pengerjaan, serta status pembayaran.

## Fitur Utama

### Pelanggan
- Registrasi dan login akun.
- Melihat informasi profil.
- Membuat pesanan jasa jahit.
- Melihat daftar dan status pesanan.
- Melihat total harga dan status pembayaran.

### Penjahit
- Login sebagai penjahit.
- Melihat data pelanggan dan daftar pesanan.
- Mengubah detail pesanan dan total harga.
- Memperbarui status pengerjaan pesanan.
- Memperbarui status pembayaran.
- Menghapus pesanan.

## Teknologi yang Digunakan

- **Java** – Bahasa pemrograman utama.
- **Java Swing** – Pembuatan antarmuka aplikasi.
- **MySQL** – Pengelolaan dan penyimpanan database.
- **JDBC** – Menghubungkan aplikasi Java dengan database MySQL.
- **NetBeans IDE** – Lingkungan pengembangan aplikasi.

## Struktur Proyek

```text
Tugas-Besar-Pemrograman-Berorientasi-Objek/
│
├── Gambar/
│   ├── Logo.png
│   └── Dokumentasi pengerjaan
│
├── src/
│   ├── InterfacePelanggan.java
│   ├── InterfacePenjahit.java
│   ├── Koneksi.java
│   ├── Login.java
│   ├── Pelanggan.java
│   ├── Penjahit.java
│   ├── Pengguna.java
│   ├── ModelPelanggan.java
│   ├── ModelPenjahit.java
│   └── ModelPesanan.java
│
└── README.md
```

## Konsep Pemrograman Berorientasi Objek

Dalam pengembangan aplikasi ini, diterapkan beberapa konsep dasar Pemrograman Berorientasi Objek (PBO), yaitu:

- **Encapsulation:** Penggunaan atribut `private` dan method getter/setter pada kelas model.
- **Inheritance:** Kelas `ModelPelanggan` dan `ModelPenjahit` mewarisi kelas abstrak `Pengguna`.
- **Abstraction:** Penggunaan kelas abstrak `Pengguna` dan interface untuk mendefinisikan perilaku pengguna.
- **Polymorphism:** Implementasi method `getRole()` pada kelas turunan serta implementasi interface sesuai kebutuhan masing-masing pengguna.

## Anggota Kelompok 5

| Nama | NIM |
|---|---|
| Muhammad Khayru Rizki | 11251033 |
| Andika Jusuf Jeremy Mustari | 11251063 |
| Remarsya Fredericha | 11281078 |

## Dokumentasi

Dokumentasi pengerjaan dan presentasi dapat dilihat melalui Google Drive berikut:

[Google Drive – Dokumentasi Tugas Besar](https://drive.google.com/drive/folders/1mqX3H9HxpzuWcLoqZVszOkA9ThKgbXHw?usp=sharing)

---

*Tugas Besar Pemrograman Berorientasi Objek – Kelompok 5.*
