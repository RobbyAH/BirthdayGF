<div align="center">

# 🌸 Happy Birthday, Bunga Safitriani ❤️
### *Special Romantic Birthday Website — 10 November 2026*

[![Made with Love](https://img.shields.io/badge/Made%20with-Love%20%26%20JavaScript-e45a8d?style=for-the-badge&logo=javascript&logoColor=white)](https://github.com/RobbyAH/BirthdayGF)
[![Target Date](https://img.shields.io/badge/Special%20Date-10%20November%202026-d4a359?style=for-the-badge)](https://github.com/RobbyAH/BirthdayGF)
[![Deploy on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com)

<p align="center">
  <em>"Di dunia ini ada jutaan jenis bunga di taman, tapi cuma satu Bunga yang berhasil tumbuh dan mekar selamanya di hatiku: <strong>Bunga Safitriani</strong>."</em>
</p>

</div>

---

## ✨ Tentang Proyek Ini

**BirthdayGF** adalah website ucapan ulang tahun interaktif, estetik, dan penuh kata-kata romantis (*bucin*) yang dibuat khusus untuk merayakan hari ulang tahun **Bunga Safitriani** pada tanggal **10 November 2026**.

Dirancang dengan nuansa warna *Soft Rose Gold*, *Blush Pink*, dan *Warm Ivory*, website ini menghadirkan pengalaman membuka kado digital yang hangat, manis, dan berkesan baik di smartphone maupun desktop.

---

## 💖 Fitur Utama

- 💌 **Wax-Sealed Envelope Opening** — Layar pembuka bergaya surat bersegel lilin yang ketika dibuka langsung memutar melodi romantis disertai hujan hati.
- 🎶 **Built-in Web Audio Music Box + MP3 Support** — Dilengkapi *synthesizer* kotak musik otomatis berbasis JavaScript (*Web Audio API*) sehingga musik tetap berbunyi lembut tanpa perlu file eksternal, serta mendukung file `assets/musik.mp3` kustom.
- ⏳ **Live Countdown 10 November 2026** — Hitung mundur *real-time* (Hari, Jam, Menit, Detik) menuju tanggal **10 November 2026** yang otomatis berubah menjadi mode perayaan saat hari-H tiba.
- 🎂 **Interactive Virtual Birthday Cake** — Kue ulang tahun interaktif dengan nyala api lilin yang bisa ditiup (lengkap dengan efek kepulan asap, ledakan hati, dan kartu doa).
- 📸 **Aesthetic Polaroid Gallery & Lightbox** — Menampilkan 9 foto kenangan terbaik dalam bingkai polaroid yang dapat diklik untuk membuka pesan rahasia di balik setiap foto.
- 📜 **Vintage Love Letter** — Surat ulang tahun dan ungkapan hati yang panjang dengan desain kertas surat klasik beraksen emas.
- 💝 **Jar of Bucin Notes** — Kapsul berisi kumpulan kata-kata gombalan dan bucin manis yang bisa diganti secara interaktif.
- 🥺 **Playful Mini-Game ("Mau Gak Terus Sama Aku?")** — Pertanyaan interaktif di mana tombol penolakan akan terus menghindar secara lucu saat didekati kursor atau disentuh jari.

---

## 📁 Struktur Folder

```text
BirthdayGF/
├── assets/
│   ├── img/
│   │   ├── gambar1.jpeg
│   │   ├── gambar2.jpeg
│   │   ├── ...
│   │   └── gambar9.jpeg
│   └── musik.mp3          # (Opsional) Lagu latar MP3 kustom
├── index.html             # Struktur halaman utama
├── style.css              # Styling Rose Gold, animasi kue, & responsif
├── script.js              # Logika countdown, musik, partikel canvas, & galeri
├── vercel.json            # Konfigurasi deployment Vercel
├── package.json           # Metadata proyek & script lokal
└── README.md              # Dokumentasi proyek
```

---

## 🚀 Cara Menjalankan & Deploy

### 1. Menjalankan Secara Lokal
Cukup buka file `index.html` langsung di browser, atau jalankan melalui server lokal:
```bash
# Menggunakan npx serve
npx serve .
```
Atau jika menggunakan **XAMPP**, letakkan di dalam `htdocs/BirthdayGF` lalu akses:
```text
http://localhost/BirthdayGF/
```

### 2. Kustomisasi Cepat
Seluruh teks, tanggal ulang tahun, daftar foto, dan kata-kata bucin dapat diubah dengan mudah di bagian atas file [`script.js`](./script.js) pada objek `CONFIG`:
```javascript
const CONFIG = {
  recipientName: "Bunga Safitriani",
  envelopeRecipient: "Bunga Safitriani ❤️",
  senderName: "Pacarmu yang Paling Bucin ❤️",
  birthdayDateISO: "2026-11-10T00:00:00+07:00",
  // ...
};
```

### 3. Deploy ke Vercel
Proyek ini sudah dilengkapi `vercel.json` dan siap dideploy secara instan:
1. Login ke [Vercel](https://vercel.com/).
2. Klik **Add New Project** dan pilih repository `RobbyAH/BirthdayGF`.
3. Klik **Deploy** — selesai!

---

<div align="center">
  Dibuat dengan sepenuh hati & rasa bucin paling dalam oleh <strong>Robby</strong> untuk <strong>Bunga Safitriani</strong> ❤️<br/>
  <sub>Spesial 10 November 2026</sub>
</div>
