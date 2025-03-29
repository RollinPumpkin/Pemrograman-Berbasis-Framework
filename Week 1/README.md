### Pertanyaan Praktikum 1
1. Git: Sistem kontrol versi untuk melacak perubahan kode, berkolaborasi, dan mengelola repositori secara efisien.
VS Code: Editor kode ringan dengan fitur canggih seperti debugging, ekstensi, dan integrasi Git.
Node.js: Runtime JavaScript di luar browser, memungkinkan pengembangan aplikasi backend dan menjalankan skrip server-side.

2. Git : ![Git proof](https://github.com/user-attachments/assets/b5eab298-59d1-478a-b3b9-deb9cc789bfd)
   VS Code : ![image](https://github.com/user-attachments/assets/c1d12cdd-1497-42ff-a967-fc6466614268)
   NodeJS : ![Screenshot 2025-02-19 091724](https://github.com/user-attachments/assets/22d6963b-af32-45e3-8bec-8144a8747cb7)


Bukti NextJS : ![Screenshot 2025-02-19 093709](https://github.com/user-attachments/assets/32ecb0df-8ce0-4df3-9497-4aaeae6214b4)

### Pertanyaan Praktikum 2
1. TypeScript – TypeScript adalah superset dari JavaScript yang menambahkan fitur tipe statis. Dengan TypeScript, kita bisa mendeteksi kesalahan kode lebih awal sebelum dijalankan, sehingga membuat pengembangan aplikasi lebih aman dan terstruktur.
ESLint – ESLint adalah alat (linter) untuk JavaScript dan TypeScript yang digunakan untuk mendeteksi kesalahan sintaks, memastikan konsistensi kode, dan menerapkan standar best practice dalam penulisan kode.Tailwind CSS – Tailwind CSS adalah framework CSS berbasis utility-first yang memungkinkan kita membangun UI lebih cepat dengan menggunakan kelas-kelas siap pakai tanpa perlu menulis banyak kode CSS kustom.
App Router – App Router adalah sistem routing terbaru di Next.js yang diperkenalkan mulai versi 13. Sistem ini menggunakan pendekatan berbasis file dalam folder app/, mendukung fitur seperti React Server Components dan rendering sisi server (SSR).
Import Alias – Import alias adalah teknik yang digunakan untuk menyederhanakan impor modul dalam proyek. Dengan alias, kita bisa mengganti path panjang dengan nama pendek yang lebih mudah dikelola, biasanya dikonfigurasi dalam tsconfig.json atau webpack.config.js.
Turbopack – Turbopack adalah bundler modern yang dikembangkan oleh Vercel sebagai penerus Webpack. Dibangun dengan teknologi Rust, Turbopack diklaim jauh lebih cepat dalam proses build dan hot reload, terutama untuk proyek Next.js.

2. .next/ – Folder ini berisi file build dan cache yang dihasilkan oleh Next.js. Biasanya diabaikan dalam version control (seperti Git).
node_modules/ – Berisi semua dependensi proyek yang diinstal melalui npm atau yarn.
public/ – Digunakan untuk menyimpan aset statis seperti gambar, ikon, dan file lainnya yang bisa diakses langsung melalui URL.
src/app/ – Folder utama untuk App Router di Next.js 13+. Berisi:
favicon.ico → Ikon yang ditampilkan di tab browser.
globals.css → File CSS global untuk styling seluruh aplikasi.
layout.tsx → Komponen yang digunakan untuk membungkus halaman agar memiliki struktur yang sama (misalnya navbar atau footer).
page.tsx → Halaman utama (/) dari aplikasi yang akan dirender oleh Next.js.

Selain itu, ada beberapa file penting di luar folder src/app/:

.gitignore – File yang menentukan file atau folder yang harus diabaikan oleh Git.
eslint.config.mjs – Konfigurasi ESLint untuk menjaga kualitas kode.
next.config.js – Konfigurasi utama untuk Next.js, seperti pengaturan API dan optimasi build.
package.json – Berisi metadata proyek serta daftar dependensi yang digunakan.
tailwind.config.ts – Konfigurasi untuk Tailwind CSS.
tsconfig.json – Konfigurasi TypeScript, menentukan bagaimana TypeScript memproses kode.

3. ![Screenshot 2025-02-19 093709](https://github.com/user-attachments/assets/42f09af5-8c1a-4813-83de-f798c8ce213d)

## Praktikum 3: Menambahkan Komponen React (Button)

| Screenshoot | Description |
| --- | --- |
| ![image](https://github.com/user-attachments/assets/35d2a3e8-7ff9-4aea-a50d-c714274fb743) | Buka file page.tsx |
| ![image](https://github.com/user-attachments/assets/cd404aad-d2c7-41db-bb5f-7a6cdf0c3b59) | Tambahkan fungsi MyButton yang mengembalikan markup komponen button yang akan ditambahkan ke dalam webpage |
| ![image](https://github.com/user-attachments/assets/cd404aad-d2c7-41db-bb5f-7a6cdf0c3b59) | Tambahkan komponen button tersebut di samping button Read Our Docs |

### Pertanyaan Praktikum 3
1. ![image](https://github.com/user-attachments/assets/b5826b74-5c5e-49e9-8b16-0b6d810ef077)

## Praktikum 4: Menulis Markup dengan JSX

| Screenshoot | Description |
| --- | --- |
| ![image](https://github.com/user-attachments/assets/13fc6e21-1b21-49a9-b3db-20de74c8541a) | Tambahkan kode JSX ke dalam file page.tsx |
| ![image](https://github.com/user-attachments/assets/f9e1cc60-2304-49fe-9cec-7781a76820e0) | | Tambahkan komponen MyProfile setelah komponen MyButton |

### Pertanyaan Praktikum 4
1. Dalam konteks Next.js dan TypeScript, sintaks user.imageUrl biasanya digunakan untuk mengakses properti imageUrl dari sebuah objek bernama user.
Kegunaannya:
Menampilkan Gambar Profil – Jika user adalah objek yang berisi informasi pengguna, user.imageUrl bisa digunakan untuk menampilkan foto profil, misalnya dalam elemen <img src={user.imageUrl} />.
Mengambil Data dari API – Jika user berasal dari respons API, imageUrl bisa berisi URL gambar yang diambil dari backend atau database.
Digunakan dalam State Management – Dalam aplikasi React atau Next.js, user.imageUrl bisa menjadi bagian dari state yang diperbarui saat pengguna mengganti foto profilnya.

3. ![image](https://github.com/user-attachments/assets/b470a6da-eae8-4b92-992c-0cbeaf892664)
