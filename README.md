# 🧆 TAHU HUHAH — Website Resmi

Website landing page produk **Tahu Huhah**, camilan tahu isi ayam suwir berbumbu rempah khas Indonesia. Dibuat oleh Luna.

---

## 📋 Deskripsi Proyek

Website ini berfungsi sebagai **halaman promosi digital** untuk produk Tahu Huhah. Pengunjung dapat melihat katalog produk, mengetahui informasi produk, menghubungi penjual via WhatsApp / Instagram, serta melihat lokasi usaha melalui Google Maps.

---

## 🗂️ Struktur File

```
tahu-huhah/
├── index.html                  # File utama website
├── README.md                   # Dokumentasi ini
└── asset/
    ├── logo tahu huhah.jpeg    # Logo navbar & favicon
    ├── produk 1.jpeg           # Foto produk 1 (juga dipakai di hero & about)
    ├── produk 2.jpeg           # Foto produk 2
    └── produk 3.jpeg           # Foto produk 3
```

---

## ✨ Fitur

- **Navbar responsif** — fixed di atas, logo + menu navigasi
- **Hero section** — background foto produk dengan overlay gradient
- **About section** — deskripsi produk + keunggulan
- **Katalog produk** — 3 kartu produk dengan foto dan harga
- **CTA (Call to Action)** — tombol WhatsApp & Instagram
- **Peta lokasi** — Google Maps embed lokasi usaha
- **Footer** — info hak cipta
- **Animasi scroll reveal** — elemen muncul saat di-scroll
- **Fully responsive** — tampil baik di HP maupun desktop

---

## 🎨 Desain

| Elemen | Detail |
|--------|--------|
| Font utama | Playfair Display (judul), Nunito (body) |
| Warna utama | Pink (`#C2185B`), Orange (`#E8500A`) |
| Warna aksen | Emas (`#F2A918`) |
| Warna latar | Krem (`#FFF8EE`) |

---

## 📞 Kontak Usaha

| Platform | Link |
|----------|------|
| WhatsApp | [+62 895-382-622-885](https://wa.me/62895382622885) |
| Instagram | [@tahu_huhah9](https://www.instagram.com/tahu_huhah9) |

---

## 📍 Lokasi

**Desa Srobyong RT 05 RW 01**  
Kec. Mlonggo, Kab. Jepara, Jawa Tengah

---

## 🚀 Cara Menjalankan

Website ini adalah file **HTML statis**, tidak butuh server atau instalasi apapun.

### Lokal (di komputer)
1. Download / clone semua file
2. Pastikan folder `asset/` berisi semua foto
3. Buka file `index.html` di browser

### Upload ke Hosting
1. Upload seluruh file (termasuk folder `asset/`) ke hosting
2. Pastikan struktur folder tetap sama
3. Akses via domain yang sudah terdaftar

---

## 🗺️ Update Lokasi Maps

Untuk pin lokasi yang lebih akurat di Google Maps:

1. Buka **Google Maps** di HP
2. Cari & tekan lama di titik lokasi rumah
3. Salin koordinat yang muncul (contoh: `-6.5191, 110.7108`)
4. Buka `index.html`, cari bagian `<iframe` di section `map-section`
5. Ganti nilai `!3d` (latitude) dan `!2d` (longitude) dengan koordinat yang baru

---

## 📝 Cara Update Konten

### Ganti Foto Produk
Ganti file di folder `asset/` dengan nama yang sama:
- `produk 1.jpeg` → foto produk 1
- `produk 2.jpeg` → foto produk 2
- `produk 3.jpeg` → foto produk 3

### Ganti Harga
Cari teks `Rp 5.000 / pcs` di `index.html` dan ubah sesuai harga terbaru.

### Ganti Nomor WhatsApp
Cari `https://wa.me/62895382622885` dan ganti dengan nomor baru (format: `628xxxxxxxxxx`).

---

## 🛠️ Teknologi

- HTML5
- CSS3 (variabel CSS, animasi, grid, flexbox)
- JavaScript vanilla (Intersection Observer untuk scroll reveal)
- Google Fonts (Playfair Display, Nunito)
- Google Maps Embed API

---

*© 2026 TAHU HUHAH — Dibuat oleh Luna*
