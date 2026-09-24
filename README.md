# Portfolio Frontend (Vue)

Website portfolio pribadi — menampilkan profil, project, dan pengalaman, dengan dukungan 2 bahasa (Indonesia & English) serta admin panel untuk mengelola konten secara dinamis.

Repo backend (Laravel API): [portfolio-backend](https://github.com/USERNAME/portfolio-backend)

---

##  Tech Stack

- **Vue 3** (Vite)
- **Tailwind CSS** — styling
- **Vue Router** — routing antar halaman
- **Pinia** — state management (bahasa aktif, token JWT)
- **vue-i18n** — multi-bahasa untuk teks statis UI

##  Fitur

- **Home** — hero, preview about, preview project, contact form
- **About** — bio, timeline pendidikan, sertifikat, skill
- **Projects** — daftar lengkap project dengan link demo & GitHub
- **Download CV** — unduh file resume dalam format PDF
- **Toggle Bahasa** — beralih antara Indonesia & English
- **Admin Panel** — login OTP, kelola project/about/pesan masuk (protected, butuh JWT)

##  Cara Menjalankan di Lokal

1. Clone repository ini
   ```bash
   git clone https://github.com/USERNAME/portfolio-frontend.git
   cd portfolio-frontend
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Copy file environment dan sesuaikan isinya
   ```bash
   cp .env.example .env
   ```
   Isi `VITE_API_BASE_URL` dengan alamat backend Laravel (lokal atau production).

4. Jalankan development server
   ```bash
   npm run dev
   ```
   Buka `http://localhost:5173` di browser.

5. Build untuk production
   ```bash
   npm run build
   ```

##  Struktur Halaman

| Halaman | Deskripsi |
|---|---|
| `/` | Home (one-page: hero, preview about, preview project, contact) |
| `/about` | Bio, timeline pendidikan, sertifikat, skill |
| `/projects` | Daftar semua project |
| `/admin/login` | Login admin (OTP) |
| `/admin/dashboard` | Dashboard admin |

##  Live Demo

> Akan diisi setelah deploy ke Vercel.

##  Author

Dibuat oleh siswa Abraham azka rizky putra hardianto, sebagai project portfolio pribadi.
