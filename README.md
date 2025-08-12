# QR Code Generator — Modern & Ultra Responsive

Generator QR Code satu file **HTML** dengan UI modern, responsif, dan siap di-host di GitHub Pages.

## ✨ Fitur
- Input **Data/URL** (tekan **Enter** untuk generate cepat)
- Pilih **warna QR** dan **warna background** (HEX) + color picker & swatches
- **Background transparan** (checkerboard preview)
- **Error Correction Level**: L / M / Q / H (tombol dengan highlight aktif)
- **Ukuran**: slider + angka + preset (192 / 256 / 320 / 512 / 768) — highlight aktif
- **Quiet zone / margin** tersimpan pada ekspor
- **Ekspor** ke **PNG** dan **SVG** (PNG memaksa minimal quiet-zone ≥ 4 modul agar mudah dipindai)
- **Peringatan kontras** otomatis saat kombinasi warna berisiko sulit dipindai
- Aksesibilitas: aria-live untuk error, fokus yang jelas

## 🧱 Teknologi
- [qrcodejs](https://www.npmjs.com/package/qrcodejs) via CDN
- HTML + CSS murni, tanpa build step

## 🚀 Cara Pakai
1. Buka `index.html` di browser.
2. Tulis teks/URL, pilih warna & ukuran, lalu klik **Generate**.
3. Klik **Download PNG** atau **Download SVG** untuk menyimpan.

## 🌐 Deploy ke GitHub Pages
1. Buat repo baru, unggah `index.html` dan file lain di repo ini.
2. Settings → **Pages** → *Deploy from a branch* → pilih branch `main` dan folder `/root`.
3. Simpan. Situs akan muncul di URL GitHub Pages Anda.

## 🧪 Tips Kualitas Scan
- Gunakan **kontras tinggi** (mis. hitam di atas putih).  
- Hindari ukuran terlalu kecil; minimal **256px** untuk kebanyakan kamera.  
- Jaga **quiet zone** (spasi tepi) minimal 4 modul — script PNG/SVG sudah membantu ini.

## 📄 Lisensi
MIT — bebas dipakai untuk komersial maupun personal. Lihat `LICENSE`.
