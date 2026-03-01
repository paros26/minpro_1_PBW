# minpro_1_PBW

# MUHAMMAD FARROS ANAND | 2409116085

#📌 Deskripsi Project

Website ini merupakan portfolio pribadi berbasis HTML dan CSS yang menampilkan informasi tentang diri saya, kemampuan (skills), pengalaman, serta project yang pernah dibuat.

Website ini menggunakan Bootstrap 5 untuk membantu tampilan agar lebih rapi, modern, dan responsif.

🧭 1. Navbar

Menampilkan menu navigasi:

Home

About

Projects

Contact

<img width="1919" height="110" alt="image" src="https://github.com/user-attachments/assets/84eacbb5-a058-40c3-9073-4e0d38db4fc6" />


Navbar berada di bagian atas (fixed)

Background transparan + blur (glass effect)

🏠 2. Home (Hero Section)

Menampilkan:

Foto profil

Nama



Tombol menuju section lain

<img width="1919" height="913" alt="image" src="https://github.com/user-attachments/assets/2c95c488-1cee-4cda-8994-bf1743e77b0b" />


Background gradient (biru ke ungu)

Teks berada di tengah

Terdapat animasi masuk (fade up)

Efek typing pada teks

👤 3. About Me

Menampilkan:

Deskripsi diri

Pengalaman

Skill dalam bentuk progress bar

<img width="1919" height="609" alt="image" src="https://github.com/user-attachments/assets/7123e927-5cf4-424e-92bf-98eb3bb3e285" />


Layout 2 kolom

Progress bar berwarna gradient

Tampilan rapi dan informatif

💼 4. Projects

Menampilkan:

Daftar project dalam bentuk card

<img width="1903" height="344" alt="image" src="https://github.com/user-attachments/assets/ef6be7d6-62d6-4455-93df-3ad7ada93be6" />


Grid 3 kolom

Card memiliki efek hover (naik dan zoom)

Gambar + judul + deskripsi

📞 5. Contact

<img width="1918" height="298" alt="image" src="https://github.com/user-attachments/assets/86575773-71cf-4b4d-a1e1-4ed019b4c2dc" />

Menampilkan:

Email

Tombol WhatsApp

Tampilan:

Posisi di tengah

Tombol interaktif

# PENJELASAN KODE

💻 Penjelasan Code Setiap Section / Fitur
🧭 Navbar
<nav class="navbar navbar-expand-lg fixed-top navbar-dark">

Penjelasan:

navbar → komponen navigasi dari Bootstrap

fixed-top → navbar tetap di atas saat scroll

navbar-dark → warna teks terang

🏠 Hero Section
<section class="hero d-flex align-items-center text-center">

Penjelasan:

d-flex → menggunakan flexbox

align-items-center → posisi vertikal tengah

text-center → teks rata tengah

👤 About Me
<div class="row">
    <div class="col-md-6">

Penjelasan:

row → membuat baris layout

col-md-6 → membagi menjadi 2 kolom

Progress bar:

<div class="progress">
  <div class="progress-bar" style="width:90%"></div>
</div>
💼 Projects
<div class="card modern-card">

Penjelasan:

card → komponen Bootstrap

modern-card → custom CSS (shadow & hover effect)

📞 Contact
<a href="https://wa.me/..." class="btn btn-success">

Penjelasan:

btn → tombol Bootstrap

btn-success → warna hijau

🎨 Penjelasan CSS (style.css)
1. Global
body {
    font-family: 'Segoe UI', sans-serif;
}

Mengatur font dan tampilan dasar.

2. Hero
.hero {
    background: linear-gradient(135deg, #0d6efd, #6610f2);
}

Memberikan background gradient.

3. Card
.modern-card:hover {
    transform: translateY(-10px);
}

Efek hover agar card terlihat interaktif.

4. Animasi
@keyframes fadeUp { ... }

Digunakan untuk animasi muncul pada Hero.

5. Dark Mode
#dark-toggle:checked ~ * {
    background: #121212;
}

Mengaktifkan mode gelap tanpa JavaScript.

6. Gradient Text
.gradient-text {
    -webkit-text-fill-color: transparent;
}

Memberikan efek warna gradient pada teks.

# 🛠️ Teknologi yang Digunakan

HTML

Struktur dasar website

CSS

Styling (warna, layout, animasi)

Bootstrap 5

Navbar

Grid system

Card

Button

Progress bar

Responsive design
