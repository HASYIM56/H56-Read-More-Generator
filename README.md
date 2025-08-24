<p align="center">
  <img src="https://h56-readmore-generator.netlify.app/H56.png" alt="H56 Read More Generator Logo" width="80" style="margin-bottom:16px;" />
</p>
<h1 align="center">H56 Read More Generator</h1>
<p align="center">
  <b>Dibuat oleh Muhammad Ali Hasyim</b>
</p>
<p align="center">
  <img src="https://h56-readmore-generator.netlify.app/images/Screenshot_20250824_132110_Chrome.jpg" alt="H56 Read More Generator Banner" />
</p>

---

## 🚀 Tentang Project

**H56 Read More Generator** adalah web app untuk membuat pesan dengan efek <i>read more</i> pada WhatsApp, Telegram, dan platform chat lainnya.  
Fitur ini memungkinkan Anda menyembunyikan sebagian pesan yang hanya akan muncul setelah penerima mengklik <b>read more</b>, baik secara multiline maupun <i>inline</i> (sejajar).

Web ini sangat berguna untuk:
- 🎲 Tebakan/quiz yang jawabannya ingin disembunyikan
- 📜 Pesan panjang yang ingin diringkas
- 🤫 Membuat <i>spoiler</i> chat
- 📢 Promosi event dengan detail tersembunyi

---

## ✨ Fitur Utama

- **WhatsApp, Telegram, Generic Read More:** Otomatis menghasilkan pesan sesuai platform.
- **Sembunyi Datar (Inline):** Fitur unik, membuat pesan seperti `Halo...read more` yang berubah menjadi `Halo semuanya` setelah diklik!
- **Kekuatan Read More:** Atur seberapa kuat efek tersembunyinya.
- **Salin & Bersihkan:** Output siap disalin, dengan tombol salin & bersihkan.
- **Responsif & Estetik:** Menggunakan TailwindCSS + DaisyUI dengan glassmorphism dan animasi modern.
- **Custom Separator:** Untuk mode inline, separator "read more" dapat diganti sesuai selera.

---

## 🖼️ Tampilan

<p align="center">
  <img src="https://h56-readmore-generator.netlify.app/images/Screenshot_20250824_132216_Chrome.jpg" alt="Preview H56 Read More Generator" width="600" />
</p>

---

## ⚡ Cara Menggunakan

1. **Teks Depan:** Tulis pesan yang akan tampil sebelum <i>read more</i>.
2. **Teks Belakang:** Tulis pesan yang akan muncul setelah <i>read more</i> diklik.
3. **Preset Platform:** Pilih WhatsApp, Telegram, Generic, atau Sembunyi Datar (Inline).
4. **Kekuatan Read More:** Geser untuk atur seberapa kuat efek tersembunyi.
5. _(Optional)_ **Separator:** Untuk mode inline, ubah separator sesuai keinginan.
6. Klik **Generate**.
7. Salin hasil dan tempelkan di chat pilihan Anda!

---

## 📱 Contoh Output

### WhatsApp Multiline
```text
Teks depan

(read more akan muncul)

Teks belakang
```

### WhatsApp Inline
```text
Halo...read more
Halo semuanya!
```

### Telegram
```text
Pesan awal

[read more]

Pesan lanjutan
```

### Generic Read More
```text
Intro

[read more]

Isi tersembunyi
```

---

## 🛠️ Tech Stack

- ⚡ **Frontend:** HTML, TailwindCSS, DaisyUI  
- 🧩 **Framework:** JavaScript Vanilla + Custom Logic  
- 🎨 **UI/UX:** Glassmorphism, Animasi modern  
- 🚀 **Hosting:** Netlify  

---

## 📂 Struktur Proyek

```
H56-Readmore-Generator/
├── index.html         # Halaman utama
├── style.css          # Styling tambahan
├── script.js          # Logika utama generator
├── /images            # Asset gambar & screenshot
└── /assets            # Ikon, font, dsb.
```

---

## 📝 Roadmap & Rencana Fitur

- [x] WhatsApp Multiline Generator  
- [x] WhatsApp Inline Generator  
- [x] Telegram Preset  
- [x] Generic Read More  
- [ ] Dark Mode  
- [ ] Fitur Auto-Preview di Browser  
- [ ] Ekspor hasil ke file (txt/md)  

---

## 🤝 Kontribusi

Kontribusi selalu terbuka! 🎉  
Jika Anda ingin menambahkan fitur atau memperbaiki bug:

1. Fork repository ini
2. Buat branch baru (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -m 'Tambah fitur baru'`)
4. Push branch (`git push origin fitur-baru`)
5. Buat Pull Request

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License** — bebas digunakan, dimodifikasi, dan dibagikan dengan tetap mencantumkan atribusi.

---

<!-- Footer Medsos Start -->
<div align="center">

<b>Temui kami di platform media sosial:</b><br>

<a href="https://youtube.com/@HASYIM56" target="_blank">
  <img src="https://cdn.jsdelivr.net/gh/edent/SuperTinyIcons/images/svg/youtube.svg" alt="YouTube" width="32" style="border-radius:50%;margin:8px;background:#fff;" />
</a>
<a href="https://instagram.com/HASYIM56" target="_blank">
  <img src="https://cdn.jsdelivr.net/gh/edent/SuperTinyIcons/images/svg/instagram.svg" alt="Instagram" width="32" style="border-radius:50%;margin:8px;background:#fff;" />
</a>
<a href="https://t.me/HASYIM56" target="_blank">
  <img src="https://cdn.jsdelivr.net/gh/edent/SuperTinyIcons/images/svg/telegram.svg" alt="Telegram" width="32" style="border-radius:50%;margin:8px;background:#fff;" />
</a>

</div>
<!-- Footer Medsos End -->

---