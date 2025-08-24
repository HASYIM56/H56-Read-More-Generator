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

**H56 Read More Generator** adalah web app untuk membuat pesan dengan efek <i>read more</i> pada WhatsApp, Telegram, dan platform chat lainnya. Fitur ini memungkinkan Anda menyembunyikan sebagian pesan yang hanya akan muncul setelah penerima mengklik <b>read more</b>, baik secara multiline maupun <i>inline</i> (sejajar).

Web ini sangat berguna untuk:
- Tebakan/quiz yang jawabannya ingin disembunyikan
- Pesan panjang yang ingin diringkas
- Membuat <i>spoiler</i> chat
- Promosi event dengan detail tersembunyi

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
```text

---

# 📌 Changelog — H56 Read More Generator

Semua perubahan penting pada project ini akan didokumentasikan di sini.  
Format mengikuti urutan **versi terbaru → versi lama**.

---

## [v2.0] - 24 Agustus 2025
### 🚀 Fitur Baru
- **Inline v2**: Penyempurnaan dari inline v1  
  - Custom marker otomatis (contoh: 👉 Klik Disini, emoji, teks lain).  
  - Multi-inline dalam satu pesan.  
  - Preview langsung di web sebelum disalin.  
  - Optimasi kompatibilitas WhatsApp & Telegram.  

---

## [v1.2] - 10 Agustus 2025
### ✨ Penambahan
- **Custom Separator**: Mode inline kini mendukung penggantian separator sesuai keinginan user.  

---

## [v1.1] - 5 Agustus 2025
### 🎨 Peningkatan
- Tampilan UI ditingkatkan dengan **glassmorphism** dan animasi modern berbasis Tailwind + DaisyUI.  

---

## [v1.0] - 1 Agustus 2025
### 🏁 Rilis Awal
- Rilis pertama H56 Read More Generator.  
- Fitur utama:  
  - WhatsApp Multiline  
  - Telegram Read More  
  - Generic Read More  
  - Inline v1 (sembunyi datar sederhana).