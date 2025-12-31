<div align="center">

<img src="https://i.postimg.cc/NfrBNtwJ/qrtznime.jpg" alt="Qrtznime Banner" width="100%" style="border-radius: 10px;"/>

# 🎬 Qrtznime 🍿  
**Modern Anime Streaming Website**

🚀 **Fast Performance** • 📱 **Fully Responsive** • 🎨 **Modern Minimalist UI**

</div>

---

## 🌸 Tentang Project

**Qrtznime** adalah platform streaming anime berbasis web yang dibangun menggunakan **Next.js (App Router)**. Project ini dirancang untuk memberikan pengalaman menonton yang mulus tanpa iklan yang mengganggu, dengan antarmuka yang bersih dan navigasi yang intuitif.

> [!IMPORTANT]
> **Legal Disclaimer:** Website ini tidak menyimpan file video di server sendiri. Semua konten ditarik secara dinamis dari API publik pihak ketiga untuk tujuan edukasi.

<div align="center">
  <h3><a href="https://qrtznime.netlify.app">🌐 Jelajahi Live Demo (Klik Disini)</a></h3>
</div>

---

## 🛠️ Tech Stack

<div align="center">

![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## ✨ Fitur Utama

* **⚡ High-Speed Streaming:** Optimasi Next.js untuk perpindahan halaman instan.
* **🔥 Update Real-Time:** Daftar anime **Ongoing** & **Completed** otomatis.
* **📅 Schedule System:** Jadwal rilis harian agar tidak ketinggalan episode.
* **🔍 Advanced Search:** Pencarian cepat berdasarkan judul.
* **🧩 Genre Exploration:** Jelajahi anime berdasarkan kategori.
* **🎬 Integrated Player:** Video player responsif dengan berbagai kualitas.
* **📱 Mobile First:** Tampilan sempurna di Android & iOS.

---

## ⚙️ Cara Kerja Website

1.  **Request:** User mengakses halaman via browser.
2.  **Server-Side Fetching:** Next.js mengambil data dari API publik Samehadaku.
3.  **Data Processing:** Data difilter dan diproses di sisi server sebelum dirender.
4.  **Instant Rendering:** User menerima halaman yang sudah jadi (SSR) untuk performa maksimal.

### 🧩 Arsitektur Aplikasi
<div align="center">
  <img src="https://quickchart.io/graphviz?format=png&graph=digraph{rankdir=LR;node[shape=box,style=filled,fillcolor=white,fontname=Arial,fontsize=12];User->NextJS;NextJS->API;API->Samedaku;Samedaku->API;API->NextJS;NextJS->User;}" alt="Arsitektur Qrtznime" width="600"/>
</div>

---

## 📂 Struktur Project

```bash
Qrtznime/
├── 📁 app/             # App Router (Halaman & Logika)
├── 📁 components/      # UI Components Reusable
├── 📁 public/          # Assets (Ikon & Logo)
├── ⚙️ config.js        # API Endpoint Config
├── 🎨 tailwind.config  # Styling Theme
└── 📦 package.json     # Dependencies

🚀 Panduan Instalasi
🔹 Run Locally
 * Clone project ke komputer kamu:
<!-- end list -->
git clone [https://github.com/meguminn1/Qrtznime.git](https://github.com/meguminn1/Qrtznime.git)

 * Masuk ke folder project:
<!-- end list -->
cd Qrtznime

 * Install semua library yang dibutuhkan:
<!-- end list -->
npm install

 * Jalankan server dalam mode development:
<!-- end list -->
npm run dev
```

🔹 Deploy ke Vercel
 * Hubungkan akun GitHub kamu ke Vercel.
 * Pilih repositori Qrtznime.
 * Klik Deploy (Vercel akan mendeteksi konfigurasi Next.js secara otomatis).
🤝 Kontribusi & Support
Ingin membantu mengembangkan Qrtznime?
 * Fork repo ini.
 * Buat fitur baru di branch berbeda.
 * Kirim Pull Request.
Jangan lupa berikan ⭐ Star jika kamu menyukai project ini!
<div align="center">
👤 <b>Developer: meguminn1</b> 

<i>"Build with passion, code with logic."</i>
</div>
