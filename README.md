# CA'NIM — Landing Page

Landing Page resmi generasi baru berkecepatan tinggi untuk aplikasi **[CA'NIM (Kh1zZ/CA-NIM)](https://github.com/Kh1zZ/CA-NIM)** — Klien Pelacak Anime & Manga Open-Source Super Ringan untuk Android.

Direkayasa ulang secara penuh selaras dengan perombakan total kode sumber **CA'NIM v6.3.0 (Clean Architecture & Apollo Kotlin 4.x)** bersama **Google Gemini 3.8 Flash** sebagai AI Software Architect & Lead Engineer.

---

## ⚡ Sorotan Pembaruan Landing Page v6.3.0
- **Live Sync GitHub Release Engine**: Otomatis mendeteksi tag rilis terbaru (`v6.3.0+`), build code (`38`), ukuran APK riil (~`2.40 MB`), changelog rilis, dan tautan unduh APK langsung dari GitHub API tanpa perlu edit manual berkas HTML.
- **Minimalist Cyberpunk Aesthetic**: Palet warna gelap mendalam (`#0a0e17`), aksen cyan (`#4cd7f6`), emerald neon (`#10b981`), dan tipografi tajam yang mempertahankan identitas visual khas CA'NIM namun jauh lebih bersih, rapi, dan mudah dibaca.
- **Interactive Clean Architecture Showcase**:
  - **Clean Architecture Diagram** (Presentation, Domain Use Cases, Data Layer & Room Cache) berformat WebP resolusi tinggi (`assets/clean-architecture-diagram.webp`) yang terintegrasi langsung dengan kontrol zoom/pan interaktif.
- **Advanced Interactive Lightbox (Zoom & Pan)**:
  - Tombol kontrol zoom (+, -, reset 100%).
  - Mouse Wheel Zoom & Drag-to-Pan saat diperbesar.
  - Pinch-to-zoom & touch drag mulus untuk perangkat layar sentuh/mobile.
- **100% Responsif & Mobile-First**:
  - Touch target standar aksesibilitas minimum 44px.
  - Horizontal snap carousel untuk 9 tangkapan layar antarmuka asli tanpa memicu horizontal page overflow.
  - Quick download sticky-bar responsif di layar mobile.
- **374 Automated Tests Showcase**: Visualisasi 55 suite pengujian otomatis (Unit Tests, Room DB, Repository, Mappers, Flow State & Hilt DI) dengan 100% tingkat kelulusan.
- **Performa Ekstrem**: Skrip non-blocking, asynchronous WebP image loading, SVG icons inline, dan zero layout shift (CLS).

---

## 📦 Menjalankan Secara Lokal
Cukup buka berkas `index.html` di browser favorit Anda, atau jalankan server lokal sederhana:
```bash
# Menggunakan Python
python -m http.server 3000

# Atau menggunakan Node.js npx serve
npx serve .
```

---

## 🌐 Deploy ke GitHub Pages
1. Masuk ke **Settings** repositori GitHub ini (`CA-NIM-LP`).
2. Masuk ke menu **Pages** di sidebar kiri.
3. Pada **Build and deployment > Source**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
5. Landing page Anda akan aktif dalam beberapa menit di domain GitHub Pages Anda!

