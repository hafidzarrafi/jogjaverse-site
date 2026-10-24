# JogjaVerse

Aplikasi web budaya Yogyakarta (HTML, CSS, JavaScript murni, tanpa framework).

## Struktur
```
jogjaverse/
├── index.html
├── css/style.css
├── js/app.js          (semua data sejarah, budaya, wisata, makanan, event)
└── assets/            (hero.jpg, tugu.png, joglo.png, profil.png)
```

## Tes di VS Code
1. Ekstrak zip, buka folder `jogjaverse` di VS Code.
2. Pasang ekstensi **Live Server**.
3. Klik kanan `index.html` > **Open with Live Server** (jangan klik dua kali).

## Upload ke hosting
Unggah **isi** folder `jogjaverse` ke `public_html` (cPanel), atau seret ke Netlify, Vercel, atau GitHub Pages.

## Mengubah isi
- Teks, alamat, event: edit larik `D`, `EV`, dan `FO` di `js/app.js`.
- Video YouTube: ubah `href` pada `class="vid"` di fungsi `det()`.
- Warna dan font: `css/style.css`.

## Catatan
- Login simulasi, disimpan di `localStorage` perangkat.
- Pilihan bahasa Indonesia/English mengubah menu dan tombol; isi konten masih Indonesia.
- Jogara AI di luar Claude menjawab dengan mencari isi aplikasi. AI penuh butuh server/API sendiri.
- Alamat dan tanggal event perlu diverifikasi sebelum dipublikasikan.
