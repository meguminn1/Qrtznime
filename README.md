<div align="center">

# 🎬 Qrtznime 🍿  
**Modern Anime Streaming Website**

![Next JS](https://img.shields.io/badge/Next.js-13+-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-18-blue?style=flat-square&logo=react)
![Tailwind](https://img.shields.io/badge/TailwindCSS-3.x-38BDF8?style=flat-square&logo=tailwindcss)
![Deploy](https://img.shields.io/badge/Deploy-Vercel-black?style=flat-square&logo=vercel)

🚀 Fast • 📱 Responsive • 🎨 Clean UI  

</div>

## 🌸 Tentang Project

**Qrtznime** adalah website streaming anime gratis berbasis **Next.js (App Router)** yang menampilkan anime **ongoing**, **completed**, **jadwal rilis**, **genre**, dan **pencarian anime**.

> ⚠️ Website ini **tidak menyimpan file video apa pun di server**.  
> Semua data dan video berasal dari **API publik Sankavollerei (Samehadaku)**.

## 👀 Preview

<div align="center">
  <img src="https://i.postimg.cc/NfrBNtwJ/qrtznime.jpg" alt="Qrtznime Preview" width="800"/>
</div>

<div align="center">
  <h3>
    <a href="https://qrtznime.netlify.app">🌐 Coba Demo Live (Klik Disini)</a>
  </h3>
</div>

## ✨ Fitur

- 🔥 Anime Ongoing & Completed
- 📅 Jadwal rilis anime
- 🔍 Pencarian anime
- 🧩 Filter berdasarkan genre
- 🎥 Video player custom
- 📱 Responsive (mobile & desktop)
- ⚡ Fast loading dengan Server Side Rendering (SSR)

## 🛠️ Teknologi

| Teknologi | Keterangan |
|---------|-----------|
| ⚛️ Next.js | Framework React (App Router) |
| ⚡ React | Library UI |
| 🎨 Tailwind CSS | Styling |
| 🌐 Samedaku API | Sumber data |
| 📦 Node.js | Runtime |

## 🧩 Arsitektur Aplikasi

```mermaid
graph TD
    A[User / Client] -->|Buka Website| B[Next.js Frontend]
    B -->|Request Anime/Episode| C{API Route Handler}
    C -->|Scrape Data| D[Samedaku / Sumber Data]
    D -->|Return HTML/JSON| C
    C -->|Response JSON| B
    B -->|Render UI & Player| A
    
    style B fill:#0070f3,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#f59e0b,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#10b981,stroke:#fff,stroke-width:2px,color:#fff

🚀 Roadmap
Berikut adalah fitur yang sedang dikerjakan atau direncanakan:
 * [x] Basic Streaming (Ongoing & Completed)
 * [x] Pencarian Anime
 * [x] Responsive Mobile UI
 * [ ] 🌙 Dark/Light Mode Toggle
 * [ ] 💾 Simpan History Tontonan (Local Storage)
 * [ ] 💬 Komentar Disqus
📂 Struktur Project
Qrtznime/
├── 📁 app/
│   ├── 📁 anime/       # Halaman detail anime
│   ├── 📁 episode/     # Halaman streaming/nonton
│   ├── 📁 genre/       # Filter anime per genre
│   ├── 📁 ongoing/     # Halaman list ongoing
│   ├── 📁 completed/   # Halaman list tamat
│   ├── 📁 jadwal/      # Jadwal rilis
│   ├── 📁 components/  # Komponen UI (Navbar, Card, dll)
│   └── ⚙️ config.js    # Konfigurasi global
├── public/             # Assets statis
└── package.json

⚙️ Setup & Konfigurasi
🔹 Jalankan di Lokal
Ikuti langkah ini untuk menjalankan project di komputer kamu:
# 1. Clone repository
git clone [https://github.com/meguminn1/Qrtznime.git](https://github.com/meguminn1/Qrtznime.git)

# 2. Masuk ke folder project
cd Qrtznime

# 3. Install dependencies
npm install

# 4. Jalankan server development
npm run dev

Buka browser dan akses: http://localhost:3000
🔹 Deploy ke Vercel
Cara termudah untuk online adalah menggunakan Vercel:
 * Login ke Vercel.
 * Klik New Project.
 * Import repository Qrtznime dari GitHub kamu.
 * Klik Deploy.
 * Selesai! Website kamu sudah online.
🤝 Contributing
Jika ingin berkontribusi menambah fitur:
 * Fork repo ini.
 * Buat branch baru (git checkout -b feature/nama-fitur).
 * Commit perubahanmu (git commit -m "Tambah fitur xyz").
 * Push ke branch (git push origin feature/nama-fitur).
 * Buat Pull Request di GitHub.
💙 Support
Jika ingin mendukung pengembangan Qrtznime:
DANA / QRIS – Link tersedia di website.
⚠️ Disclaimer
Qrtznime tidak menyimpan file video apa pun di server kami.
Semua konten berasal dari pihak ketiga dan digunakan hanya untuk tujuan edukasi/pembelajaran pemrograman.
📜 License
Open Source — bebas dipelajari dan dikembangkan.
<div align="center">
👤 <b>Author</b> 

GitHub: <a href="https://www.google.com/search?q=https://github.com/meguminn1">@meguminn1</a>
</div>
