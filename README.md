Nama    : Muhamad Rizki Wahyu Saputra
Nim     : 312410534
Kelas   : TI.24.A5
Matkul  : Pemograman Web 1
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Lab-1-Web
Penjelasan Langkah-Langkah Kode HTML
Siapkan Aplikasi VSCode
Gambar 1 ![alt text](?raw=true)

Kemudian buat file baru dengan nama lab1_tag_dasar.html dan masukan kode tag dasar dokumen
HTML.
Gambar 2
1. <!DOCTYPE html>
- Fungsi: Menyatakan bahwa dokumen ini menggunakan standar HTML5.
- Proses: Memberi tahu browser agar merender halaman sesuai aturan HTML5.

2. <html lang="id"> … </html>
- Fungsi: Tag pembungkus seluruh dokumen HTML.
- Atribut lang="id": Menandakan bahwa isi halaman menggunakan Bahasa Indonesia.
- Proses: Membantu mesin pencari dan pembaca layar memahami bahasa konten.

3. <head> … </head>
Bagian ini berisi informasi metadata yang tidak ditampilkan langsung ke pengguna.
- <meta charset="UTF-8">: Menentukan encoding karakter agar teks ditampilkan dengan benar.
- <title>: Judul halaman yang akan muncul di tab browser.
Dijalankan hasil kodenya di Browser dan hasilnya masih kosong:
Gambar 3

Kemudian masukan kode Judul utama halaman seperti gambar dibawah ini:
Gambar 4
4. <h1>Belajar Dasar HTML</h1>
- Fungsi: Menampilkan judul utama halaman.
- Proses: Ditampilkan dengan ukuran besar dan tebal, menandakan topik utama.
  
5. <p> … </p>
Paragraf pertama:
- Fungsi: Menjelaskan konteks pembelajaran HTML.
- Proses: Teks ditampilkan dalam format paragraf yang rapi.
- 
6. <h2>Paragraf pada HTML</h2>
- Fungsi: Subjudul untuk bagian yang membahas paragraf.
- Proses: Ditampilkan lebih kecil dari <h1>, menandakan bagian baru.
  Paragraf kedua:
Sekaligus di isi paragrafnya dan hasilnya:
Gambar 5

Kemudian masukan kode untuk menambahkan gambar seperti gambar dibawah ini:
Gambar 6
7. <h3>Menambahkan Gambar</h3>
- Fungsi: Subjudul untuk bagian gambar.
- Proses: Ditampilkan lebih kecil dari <h2>, menandakan subbagian.

8. <img src="logo_UPB.jpeg" title="Logo Universitas Pelita Bangsa">
- Fungsi: Menampilkan gambar.
- Atribut:
- src: Lokasi file gambar.
- title: Teks yang muncul saat mouse diarahkan ke gambar.
- Proses: Browser mencari file gambar dan menampilkannya di halaman.
✅ Pastikan file logo_UPB.jpeg berada di folder yang sama dengan file HTML agar gambar muncul.
Hasilnya:
Gambar 7

Kemudian tambahkan kode untuk menampilkan konten visual ke pengguna seperti gambar dibawah ini:
Gambar 8
9. <body> … </body>
Bagian utama yang menampilkan konten visual ke pengguna.

10. <nav> … </nav>
Bagian navigasi berisi tautan ke halaman lain.
- <a href="...">: Membuat tautan ke halaman lokal atau eksternal.
- Proses: Saat diklik, browser akan membuka halaman yang dituju.
11. <hr>
- Fungsi: Membuat garis horizontal sebagai pemisah visual.
- Proses: Memisahkan bagian navigasi dengan konten utama.
Hasilnya:
Gambar 9

Dan ini hasil semua kode langkah-langkah diatas:
Gambar 10

📌 Kesimpulan
Struktur HTML ini sudah lengkap dan benar untuk praktikum dasar:
*Tag dan Fungsi Utama*
<!DOCTYPE> = Menentukan standar HTML5
<html></html> = Membungkus seluruh dokumen HTML
<head></head> = Metadata dan judul halaman
<body></body> = Konten utama yang ditampilkan
<nav></nav> = Navigasi antar halaman
<a></a> = Tautan ke halaman lain
<hr> = Garis pemisah
<h1></h3> = Judul dan subjudul
<p></p> = Paragraf teks
<img> = Menampilkan gambar

