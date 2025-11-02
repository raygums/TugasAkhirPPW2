# 🌐 Portfolio Website - Muhammad Rayhan Gumay

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Website portfolio pribadi yang menampilkan profil, kemampuan, dan proyek-proyek yang telah dikerjakan.

## 📋 Deskripsi

Website portfolio ini dibuat sebagai tugas akhir praktikum Pemrograman Web. Website ini menampilkan informasi tentang diri saya, kemampuan bahasa pemrograman yang dikuasai, serta proyek-proyek yang pernah dikerjakan.

## 👍 Fitur

- **Responsive Design** - Tampilan yang optimal di berbagai ukuran layar
- **Modern UI/UX** - Desain yang bersih, modern, dan user-friendly
- **Section About** - Informasi profil dan kontak
- **Section Skills** - Daftar kemampuan bahasa pemrograman dengan ikon
- **Section Projects** - Showcase proyek-proyek yang telah dikerjakan
- **Smooth Scrolling** - Navigasi yang halus antar section
- **Hover Effects** - Interaksi yang menarik pada elemen-elemen

## 🛠️ Teknologi yang Digunakan

- **HTML5** - Struktur halaman web
- **CSS3** - Styling dan layout
  - CSS Grid & Flexbox
  - CSS Variables
  - CSS Animations & Transitions
  - Media Queries untuk responsive design

## ? Cara Menggunakan

### Clone Repository

```bash
git clone (https://github.com/raygums/TugasAkhirPPW2.git)
```

### Jalankan Secara Lokal

1. **Buka file `index.html`** di browser favorit Anda
2. Atau gunakan Live Server di VS Code untuk development

### Alternatif dengan Live Server

```bash
# Install Live Server (jika menggunakan npm)
npm install -g live-server

# Jalankan di folder proyek
live-server
```

## 🎨 Customisasi

### Mengubah Warna Tema

Edit CSS Variables di `style.css`:

```css
:root {
    --primary-color: #2563eb;      /* Warna utama */
    --secondary-color: #1e40af;    /* Warna sekunder */
    --text-dark: #1f2937;          /* Warna teks gelap */
    --text-light: #6b7280;         /* Warna teks terang */
}
```

### Menambah Skill Baru

Tambahkan card baru di section skills:

```html
<div class="skill-card">
    <div class="skill-icon">🔥</div>
    <h3>Nama Skill</h3>
</div>
```

### Menambah Proyek Baru

Tambahkan card baru di section projects:

```html
<div class="project-card">
    <div class="project-image">
        <img src="./gambar/project-name.png" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Nama Proyek</h3>
        <p>Deskripsi singkat proyek</p>
        <div class="project-tags">
            <span class="tag">Tech1</span>
            <span class="tag">Tech2</span>
        </div>
    </div>
</div>
```

## 🌿 Branch

- **`main`** - Branch utama dengan styling standar

### Mencoba Buat Branch Baru

```bash
git branch <nama-branch>
git checkout <nama-branch>
```

Styling eksperimen memiliki fitur:
- Gradient color scheme (purple & pink)
- Enhanced hover effects
- Modern glassmorphism elements
- Animated elements
- Circular profile photo

## 👨‍💻 Tentang Developer

**Muhammad Rayhan Gumay**
- Email: rayhangumay2004@gmail.com
- Lokasi: Bandarlampung, Indonesia
- Mahasiswa Teknik Informatika - Universitas Lampung
- Konsentrasi: Rekayasa Perangkat Lunak (RPL)

## 📊 Proyek yang Ditampilkan

### 1. E-Journal Unila
Website Portal Jurnal Digital Universitas Lampung
- **Tech Stack**: HTML, Bootstrap, JavaScript, PHP, MySQL

### 2. MovieRating
Platform diskusi mengenai film-film yang sedang tayang
- **Tech Stack**: React, Tailwind, MongoDB, Express, Node

### 3. Readify.id
Website company profile yang profesional dan elegan
- **Tech Stack**: React, Laravel, PostgreSQL
