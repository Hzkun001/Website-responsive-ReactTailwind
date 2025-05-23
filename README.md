#  Tailwind - React Portfolio

Ini adalah proyek portfolio berbasis React, Vite, dan TailwindCSS.

## Fitur

- React 19 + Vite
- TailwindCSS untuk styling
- Animasi dengan Animate.css & AOS
- Preloader, Navbar, Footer, dan Section dinamis
- Data tools & proyek terpisah di file JS

## Prasyarat

- Node.js (disarankan versi terbaru LTS)
- npm (terinstal bersama Node.js)

## Cara Menjalankan Proyek

1. **Clone repository ini**  
   (Jika belum, gunakan perintah berikut di terminal:)
   ```sh
   git clone <url-repo-anda>
   cd ngoding-mastery
   ```

2. **Install dependencies**  
   Jalankan perintah berikut di folder proyek:
   ```sh
   npm install
   ```

3. **Jalankan aplikasi dalam mode development**
   ```sh
   npm run dev
   ```
   Aplikasi akan berjalan di [http://localhost:5173](http://localhost:5173) (atau port yang tertera di terminal).

4. **Build untuk produksi**
   ```sh
   npm run build
   ```
   Hasil build akan ada di folder `dist/`.

5. **Preview hasil build**
   ```sh
   npm run preview
   ```

## Struktur Folder

- `src/` : Source code utama (komponen, data, style)
- `public/assets/` : Gambar & aset statis
- `vite.config.js` : Konfigurasi Vite
- `tailwind.config.js` : Konfigurasi TailwindCSS

## Customisasi

- Ubah data tools & proyek di [`src/data.js`](src/data.js)
- Edit tampilan di komponen pada [`src/components/`](src/components/)
- Ganti gambar di folder `public/assets/`

## Linting

Untuk cek kualitas kode:
```sh
npm run lint
```

---

Selamat ngoding! 🚀
