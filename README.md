<div align="center">

# 🎬 Qrtznime 🍿  
**Modern Anime Streaming Website**

![Next JS](https://img.shields.io/badge/Next.js-13+-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-18-blue?style=flat-square&logo=react)
![Tailwind](https://img.shields.io/badge/TailwindCSS-3.x-38BDF8?style=flat-square&logo=tailwindcss)
![Vercel](https://img.shields.io/badge/Deploy-Vercel-black?style=flat-square&logo=vercel)

🚀 **Fast Performance** • 📱 **Fully Responsive** • 🎨 **Modern Minimalist UI**

</div>

## 🌸 Tentang Project

**Qrtznime** adalah platform streaming anime berbasis web yang dibangun menggunakan **Next.js (App Router)**. Project ini dirancang untuk memberikan pengalaman menonton yang mulus tanpa iklan yang mengganggu, dengan antarmuka yang bersih dan navigasi yang intuitif.

> [!IMPORTANT]
> **Legal Disclaimer:** Website ini tidak menyimpan file video di server sendiri. Semua konten ditarik secara dinamis dari API publik pihak ketiga untuk tujuan edukasi dan pengembangan portofolio.

## 👀 Preview & Demo

<div align="center">
  <img src="https://i.postimg.cc/NfrBNtwJ/qrtznime.jpg" alt="Qrtznime Preview" width="800" style="border-radius: 10px;"/>
  <br/>
  <h3><a href="https://qrtznime.netlify.app">🌐 Jelajahi Live Demo</a></h3>
</div>

## ✨ Fitur Utama (Detail)

* **⚡ High-Speed Streaming:** Menggunakan optimasi Next.js untuk memastikan perpindahan halaman yang instan.
* **🔥 Update Real-Time:** Menampilkan daftar anime **Ongoing** (sedang tayang) dan **Completed** (tamat) yang selalu diperbarui secara otomatis dari sumber data.
* **📅 Schedule System:** Fitur jadwal rilis harian agar pengguna tidak ketinggalan episode terbaru dari anime favorit mereka.
* **🔍 Advanced Search:** Pencarian cepat berdasarkan judul dengan algoritma filter yang akurat.
* **🧩 Genre Exploration:** Menjelajahi ribuan judul anime berdasarkan kategori/genre tertentu.
* **🎬 Integrated Video Player:** Player video yang responsif dan mendukung berbagai kualitas resolusi.
* **📱 Mobile First Design:** Dioptimalkan secara penuh untuk perangkat Android dan iOS.

## ⚙️ Cara Kerja Website

Website ini bekerja dengan arsitektur **Modern Web Scraper & API Integrator**:

1.  **Request:** Saat user membuka halaman, Next.js melakukan request ke API Route.
2.  **Data Fetching:** Server-side code akan mengambil data (scraping/fetching) dari API publik Samehadaku secara asinkron.
3.  **Processing:** Data mentah diproses dan dibersihkan di sisi server sebelum dikirim ke frontend untuk menjaga keamanan API Key/Endpoint.
4.  **Rendering:** Menggunakan **Server Side Rendering (SSR)** untuk SEO yang lebih baik dan **Client Side Rendering (CSR)** untuk interaksi player yang cepat.

### 🧩 Diagram Alur Data
<div align="center">
  <img src="https://quickchart.io/graphviz?format=png&graph=digraph{rankdir=LR;node[shape=box,style=filled,fillcolor=white,fontname=Arial];User->NextJS;NextJS->API;API->Samedaku;Samedaku->API;API->NextJS;NextJS->User;}" alt="Arsitektur Qrtznime" width="600"/>
</div>

## 📂 Struktur Direktori

```bash
Qrtznime/
├── 📁 app/
│   ├── 📁 anime/       # Detail informasi & sinopsis anime
│   ├── 📁 episode/     # Page khusus video player streaming
│   ├── 📁 genre/       # Navigasi berdasarkan kategori
│   ├── 📁 ongoing/     # List anime yang masih berjalan
│   ├── 📁 completed/   # Arsip anime yang sudah tamat
│   ├── 📁 jadwal/      # Jadwal rilis per hari
│   ├── 📁 components/  # Reusable UI (Navbar, Footer, Card, Skeleton)
│   └── ⚙️ config.js    # Pengaturan Base URL API & Konstanta
├── 📁 public/          # Ikon, logo, dan gambar statis
├── tailwind.config.js  # Konfigurasi custom tema & warna
└── package.json        # Dependensi project

🚀 Panduan Instalasi
🔹 Run Locally
# Clone project
git clone [https://github.com/meguminn1/Qrtznime.git](https://github.com/meguminn1/Qrtznime.git)

# Masuk ke folder
cd Qrtznime

# Install library
npm install

# Jalankan mode dev
npm run dev

Akses di: http://localhost:3000
🔹 Deploy ke Vercel
 * Hubungkan akun GitHub ke Vercel.
 * Pilih repositori Qrtznime.
 * Klik Deploy (Pengaturan otomatis terdeteksi sebagai Next.js).
🤝 Kontribusi & Support
Ingin membantu mengembangkan Qrtznime?
 * Fork project ini.
 * Buat fitur baru di branch berbeda.
 * Kirim Pull Request.
Dukungan: Jika project ini bermanfaat, berikan ⭐ Star pada repositori ini!
<div align="center">
👤 <b>Developer: meguminn1</b> 

<i>"Build with passion, code with logic."</i>
</div>
