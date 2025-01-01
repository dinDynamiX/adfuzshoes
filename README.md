# Sistem Penjualan Barang - Adfuzshoes

## Deskripsi
Proyek ini adalah sistem informasi penjualan barang untuk toko Adfuzshoes, dirancang menggunakan **Java** dan diimplementasikan dengan **NetBeans IDE**. Sistem ini mencakup fitur-fitur seperti manajemen barang, pelanggan, transaksi, serta laporan.

## Teknologi yang Digunakan
- **Java**: Bahasa pemrograman utama untuk pengembangan aplikasi.
- **NetBeans IDE**: Lingkungan pengembangan terintegrasi untuk pengkodean.
- **MySQL**: Sistem manajemen basis data untuk menyimpan informasi barang, pelanggan, dan transaksi.
- **PHPMyAdmin**: Alat berbasis web untuk administrasi database MySQL.

## Fitur Utama
1. **Login dan Registrasi**: Autentikasi pengguna dengan dukungan untuk hak akses.
2. **Manajemen Barang**: CRUD (Create, Read, Update, Delete) untuk data barang.
3. **Manajemen Pelanggan**: Menyimpan dan mengelola informasi pelanggan.
4. **Transaksi Penjualan**: Sistem untuk mencatat dan mengelola transaksi.
5. **Laporan**: Menghasilkan laporan data untuk evaluasi bisnis.


## Struktur Database
1. **Tabel `barang`**: Menyimpan data barang dengan `id` sebagai primary key.
2. **Tabel `detail_barang`**: Menyimpan detail barang dengan `Kode_Detail` sebagai primary key.
3. **Tabel `pelanggan`**: Menyimpan data pelanggan dengan `nik` sebagai primary key.
4. **Tabel `transaksi`**: Menyimpan data transaksi dengan `Kode_Transaksi` sebagai primary key.
5. **Tabel `user`**: Menyimpan data pengguna dengan `id` sebagai primary key.

## Persyaratan Sistem
- **Sistem Operasi**: Windows 10.
- **Prosesor**: Intel Core i5-7300U atau setara.
- **Database**: MySQL yang diakses menggunakan PHPMyAdmin.

## Cara Menjalankan
1. Pastikan Java, NetBeans, dan MySQL sudah terinstal di sistem Anda.
2. Import database menggunakan file SQL yang telah disediakan.
3. Buka proyek di NetBeans.
4. Jalankan aplikasi melalui tombol **Run**.

