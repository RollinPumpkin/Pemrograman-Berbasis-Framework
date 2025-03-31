# Pertemuan 3
# Pengenalan Next.js

## Persiapan Lingkungan

| Screenshoot | Description |
| --- | --- |
| ![image](https://github.com/user-attachments/assets/07b34228-96fb-493a-abf4-ed275ab2e6cf) | Pastikan Node.js dan npm sudah terinstal di komputer Anda. Anda dapat memeriksanya dengan menjalankan perintah berikut di terminal atau command prompt |
| ![image](https://github.com/user-attachments/assets/95713332-8291-42e6-ad0e-1f3006ca1384) | Buat direktori baru untuk proyek Next.js Anda |
| ![image](https://github.com/user-attachments/assets/1d22109b-1292-419e-b07f-ac051ccdf6dc) | Inisialisasi proyek Next.js dengan menjalankan perintah berikut: Perhatikan bahwa App Routerbelum digunakan |
| ![image](https://github.com/user-attachments/assets/9d117774-9bc6-4233-803e-779eb4920c46) | Jalankan aplikasi Next.js dengan perintah |

## Membuat Halaman dengan Server-Side Rendering (SSR)

| Screenshoot | Description |
| --- | --- |
| ![image](https://github.com/user-attachments/assets/a531b9b7-950d-4a99-a009-39da43b8b175) | Buka file pages/index.tsx di text editor Anda |
| ![image](https://github.com/user-attachments/assets/3608e8aa-584d-47b3-bd16-7de887847acd) | Ganti kode di dalamnya dengan kode berikut untuk membuat halaman sederhana |
| ![image](https://github.com/user-attachments/assets/f4145509-75f3-4a02-930b-2576c19a17d6) | Simpan file dan lihat perubahan di browser. Anda akan melihat halaman utama dengan teks "Selamat Datang di Website Saya!". |

## Menggunakan Static Site Generation (SSG)

| Screenshoot | Description |
| --- | --- |
| ![image](https://github.com/user-attachments/assets/3186ddd4-0865-467c-b1f9-01c9250b2cbd) | Buat file baru di direktori pages dengan nama blog.js dan tambahkan kode berikut untuk membuat halaman blog dengan SSG |
| ![image](https://github.com/user-attachments/assets/d706e7b6-d2ea-4640-87e9-8afaf71f3c71) | Simpan file dan buka http://localhost:3000/blog di browser. Anda akan melihat daftar post yang diambil dari API eksternal. |

## Menggunakan Dynamic Routes

| Screenshoot | Description |
| --- | --- |
| ![image](https://github.com/user-attachments/assets/7e07cbd3-1395-43f0-b889-5a84f2ee19d2) | Buat direktori baru di pages dengan nama blog, Buat file di dalam direktori blog dengan nama [slug].js, Tambahkan kode berikut untuk membuat halaman dinamis berdasarkan slug |
|  | Simpan file dan buka http://localhost:3000/blog/contoh-post di browser. Anda akan melihat halaman yang menampilkan slug dari URL. |
