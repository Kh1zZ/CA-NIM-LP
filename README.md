# CA'NIM — Landing Page

Landing Page resmi berkecepatan tinggi untuk aplikasi **[CA'NIM (Kh1zZ/CA-NIM)](https://github.com/Kh1zZ/CA-NIM)** — Klien Pelacak Anime & Manga Open-Source Super Ringan untuk Android.

## 🚀 Fitur Landing Page
- **Live Sync GitHub Release**: Otomatis mendeteksi tag rilis terbaru (`vX.Y.Z`), nama file APK, ukuran file riil dalam MB, dan URL unduhan langsung dari GitHub API tanpa perlu edit manual.
- **Tech Stack Ultra-Ringan**: Dibuat dengan HTML5 murni, Tailwind CSS, dan Vanilla JavaScript tanpa dependensi framework yang berat.
- **100% Responsif & Mobile-First**: Dioptimalkan secara mulus untuk tampilan smartphone (tata letak vertikal) hingga monitor desktop (2-kolom layout).
- **Mockup Interaktif**: Simulasi smartphone dengan HUD card tombol cepat progres episode (`+1 Ep`).
- **Galeri Tangkapan Layar 9:19 & Lightbox**: 9 slot tangkapan layar antarmuka asli dengan slider horizontal dan pratinjau resolusi tinggi (Lightbox Modal).
- **Audit & Benchmark**: Tabel komparatif visual antara CA'NIM vs aplikasi pelacak konvensional.

## 📦 Menjalankan Secara Lokal
Cukup buka berkas `index.html` di browser favorit Anda, atau jalankan server lokal sederhana:
```bash
# Menggunakan Python
python -m http.server 3000

# Atau menggunakan Node.js npx serve
npx serve .
```

## 🌐 Deploy ke GitHub Pages
1. Masuk ke **Settings** repositori GitHub ini (`CA-NIM-LP`).
2. Masuk ke menu **Pages** di sidebar kiri.
3. Pada **Build and deployment > Source**, pilih **Deploy from a branch**.
4. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
5. Landing page Anda akan aktif dalam beberapa menit di domain GitHub Pages Anda!
