# TUGAS PRAKTIKUN REST SOAP API

## Konsumsi Data dengan GET Request.
- Gunakan kode di atas untuk mengambil daftar post dari https://jsonplaceholder.typicode.com/posts.
- Tampilkan 5 data pertama dalam bentuk array PHP.

![localhost_Tugas praktikum pertemuan 3-4_GET php - Google Chrome 10_4_2024 5_47_41 PM](https://github.com/user-attachments/assets/d64a5f65-25fc-4222-90f1-d248ef108210)

## Mengirim Data dengan POST Request
- Gunakan kode POST di atas untuk mengirim data baru ke API yang sama.
- Ganti isi body dengan data lain yang relevan (misalnya judul dan konten berbeda).

![localhost_Tugas praktikum pertemuan 3-4_GET php - Google Chrome 10_4_2024 5_50_11 PM](https://github.com/user-attachments/assets/26d7005d-fd1b-4312-94a0-efe3b70f94ae)

## Menghapus Data dengan DELETE Request.
- Gunakan kode DELETE untuk menghapus salah satu post dari API.
- Tampilkan respon yang dikembalikan dari API setelah permintaan DELETE berhasil.

![localhost_Tugas praktikum pertemuan 3-4_GET php - Google Chrome 10_4_2024 5_50_26 PM](https://github.com/user-attachments/assets/1b4cd98c-c3ba-489b-b8b4-4cdfbb6c52c2)

## Analisis Metode HTTP
- Jelaskan perbedaan antara metode GET, POST, dan DELETE.
  1. **GET**: Mengambil data dari server melalui URL. Idempoten, tidak cocok untuk data sensitif, dan terbatas oleh panjang URL.
  2. **POST**: Mengirim data baru melalui body request. Tidak idempoten, lebih aman untuk data sensitif, dan tidak memiliki batasan ukuran data.
  3. **DELETE**: Menghapus data di server, biasanya tanpa body request. Idempoten, dan perlu hati-hati karena menghapus data permanen.
- Diskusikan skenario kapan harus menggunakan masing-masing metode dalam aplikasi nyata.
  1. **GET**: biasanya untuk menampilkan suatu data misalnya artikel, profil, dan informasi lainya
  2. **POST**: biasanya digunakan untuk menambahkan data baru seperi formulir pendaftaran, menambahkan konten pada suatu aplikasi, dan lainya
  3. **DELETE**: biasanya digunakan untuk menghapus suatu data contohnya hapus akun pengguna
