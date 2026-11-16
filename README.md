# Praktikum 8: PHP dan Database MySQL

## 1. Membuat Database dan Tabel
Membuat database baru dengan nama `latihan1` serta tabel `data_barang` melalui phpMyAdmin, lalu mengisinya dengan data awal.
<img width="1366" height="738" alt="Screenshot from 2026-11-16 13-35-34" src="https://github.com/user-attachments/assets/ca960765-a86c-4279-822b-dd0a8df81a33" />
<img width="1366" height="738" alt="Screenshot from 2026-11-16 13-35-45" src="https://github.com/user-attachments/assets/8b345eb0-a9e9-46e3-a7e1-9f324705305b" />
<img width="1366" height="738" alt="Screenshot from 2026-11-16 13-37-10" src="https://github.com/user-attachments/assets/a98aff2b-12ed-4a31-b878-8adec2f6be41" />

## 2. Pengujian Koneksi Database (`koneksi.php`)
Membuat file `koneksi.php` untuk menghubungkan aplikasi PHP dengan server database MySQL dan mengujinya melalui browser.
<img width="1366" height="738" alt="Screenshot from 2026-11-16 13-39-20" src="https://github.com/user-attachments/assets/2de49a5c-59cd-4cc2-aba5-9352a3262a43" />



## 3. Menampilkan Data (`index.php` - Read)
Membuat halaman utama untuk mengambil dan menampilkan seluruh data dari tabel `data_barang` ke dalam bentuk tabel HTML.
<img width="1366" height="738" alt="Screenshot from 2026-11-16 13-44-46" src="https://github.com/user-attachments/assets/c31933d5-5aca-4f5d-b921-10dab986bcb4" />


## 4. Menambah Data (`tambah.php` - Create)
Membuat form input barang baru beserta fitur unggah file gambar ke dalam direktori `gambar/`.
<img width="1366" height="738" alt="Screenshot from 2026-11-16 13-47-15" src="https://github.com/user-attachments/assets/8d47c3ec-3ad1-4e9b-8595-1f8aef9543c9" />


## 5. Mengubah Data (`ubah.php` - Update)
Membuat halaman untuk memperbarui data barang yang sudah ada berdasarkan `id_barang`.
<img width="1366" height="738" alt="Screenshot from 2026-11-16 13-50-35" src="https://github.com/user-attachments/assets/acdfe6aa-405e-4a9c-9d5f-39f2c7052e7c" />


## 6. Menghapus Data (`hapus.php` - Delete)
Menghapus data barang yang dipilih dari database dan langsung mengarahkan kembali ke halaman `index.php`.
