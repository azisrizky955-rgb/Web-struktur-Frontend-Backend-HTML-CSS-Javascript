# Web-struktur-Frontend-Backend-HTML-CSS-Javascript
Berikut tutorial interaktif belajar Web — klik tab di atas untuk berpindah antara **Frontend**, **Backend**, dan **Integrasi**.

---

### Urutan belajar yang disarankan

Jika kamu mulai dari nol, ikuti urutan ini:

**HTML → CSS → JavaScript** (frontend dulu, karena kamu langsung lihat hasilnya di browser). Setelah cukup percaya diri, lanjut ke **Backend** dengan Node.js + Express, lalu pelajari cara keduanya terhubung di tab **Integrasi**.

### Estimasi waktu belajar

| Tahap | Waktu (konsisten 1–2 jam/hari) |
|---|---|
| HTML dasar | 1 minggu |
| CSS + layout | 2–3 minggu |
| JavaScript | 4–6 minggu |
| Backend dasar | 3–4 minggu |
| Full-stack integrasi | 2–4 minggu |

### Tips paling penting

Jangan hanya menonton — langsung ketik kodenya, rusak, dan perbaiki sendiri. Error adalah bagian dari proses, bukan tanda kamu gagal. Mau tanya topik spesifik atau minta contoh kode? Silakan!
*Frontend*
*Pemula*
- Struktur Dasar HTML
Anatomi dokumen: <!DOCTYPE>, <html>, <head>, <body>
Tag teks: heading h1–h6, paragraf p, link a, gambar img
List: ul, ol, li dan tabel table
Form input: input, textarea, button, select
*Menengah*
- HTML Semantik
Tag semantik: header, nav, main, section, article, footer
Atribut aksesibilitas: alt, aria-label, role
Meta tag SEO: description, og:title, viewport

*Pemula*
- CSS Dasar
Selektor: tag, class .nama, id #nama, kombinator
Box model: margin, padding, border, width, height
Warna & tipografi: color, font-size, font-family, line-height
*Menengah*
- Layout Modern
Flexbox: display:flex, justify-content, align-items, gap
CSS Grid: grid-template-columns, grid-area, auto-fit
Responsive: media query @media, unit rem, vw, %
*Lanjutan*
- Animasi & Variabel CSS
CSS Variables: --nama-var dan var() untuk theming
Transisi & animasi: transition, @keyframes, animation
Pseudo-class & pseudo-element: :hover, :focus, ::before, ::after

*Pemula*
- Dasar JavaScript
Variabel: let, const, tipe data string, number, boolean, array, object
Kontrol alur: if/else, for, while, forEach
Fungsi: deklarasi, arrow function, parameter, return
*Menengah*
- DOM & Event
Manipulasi DOM: querySelector, getElementById, innerHTML, classList
Event listener: addEventListener — click, submit, keyup, input
Array methods: map, filter, reduce, find
*Lanjutan*
- Async & Fetch API
Promise: .then(), .catch(), chaining
Async/Await: async function, await, try/catch
Fetch API: GET, POST data ke server, parsing JSON
ES Modules: import / export, struktur kode modular

*Backend*
Pemula
- Konsep Dasar Backend
Apa itu server? Perbedaan client vs server
HTTP & HTTPS: request, response, status code (200, 404, 500)
Pilih bahasa: Node.js / JSPythonPHP
*Menengah*
- Membuat REST API
Framework: Express.js (Node) · Django/Flask (Python) · Laravel (PHP)
HTTP Methods: GET (baca), POST (buat), PUT/PATCH (ubah), DELETE (hapus)
Routing & middleware: memproses request sebelum sampai handler
Format data: JSON — cara data frontend & backend saling bicara
Menengah
_ Database
SQL (relasional): MySQL / PostgreSQL — tabel, kolom, relasi, JOIN
NoSQL (dokumen): MongoDB — koleksi, dokumen JSON, query
ORM / ODM: Prisma, Sequelize, Mongoose — akses DB tanpa SQL mentah
CRUD: Create, Read, Update, Delete ke database
Lanjutan
- Autentikasi & Keamanan
JWT (JSON Web Token): login, menyimpan sesi, validasi token
Hashing password: bcrypt — jangan simpan password polos
Environment variable: simpan secret di file .env
CORS: izinkan/batasi domain yang boleh mengakses API kamu

*Integrasi*
- Cara kerja
Alur Request Frontend → Backend
User klik tombol di browser (frontend)
JavaScript mengirim HTTP request ke API (fetch/axios)
Server backend menerima, proses, akses database
Server kirim JSON response kembali ke browser
JS memperbarui tampilan halaman tanpa reload
Praktik
- Proyek Full-Stack Latihan
Level 1: To-do list — HTML/CSS/JS frontend + Node.js API + penyimpanan array
Level 2: Blog sederhana — React/Vanilla JS + Express + MongoDB
Level 3: Aplikasi login — JWT auth + bcrypt + session management
Level 4: Deploy ke internet — Vercel (frontend) + Railway/Render (backend)
- Alat Bantu
*Tools yang Perlu Dikuasai*
-  Editor & Terminal
VS Code · Git & GitHub
npm / yarn · Terminal bash
-  Test API
Postman · Thunder Client
curl · browser DevTools
-  Database GUI
TablePlus · DBeaver
MongoDB Compass
-  Deploy
Vercel · Netlify
Railway · Render · Supabase
