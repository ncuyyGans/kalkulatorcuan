# Kalkulator Cuan

Alat bantu hitung-hitungan belanja dan kulakan — langsung dari browser, tanpa install, tanpa simpan data pribadi.

🌐 **Coba langsung:** https://kalkulatorcuan.vercel.app

## ✨ Fitur

### Alat 1 — Kalkulator Cuan
Hitung potensi keuntungan sebelum checkout:
- **Modal dibayar** setelah potongan voucher
- **Laba per pcs**, total laba, dan margin keuntungan
- **Saran kuantitas optimal** — jumlah barang yang bikin potongan voucher maksimal
- Komposisi modal vs untung dalam grafik batang

### Alat 2 — Kalkulator Voucher
Buat yang sering bingung sama syarat voucher kayak *"Diskon 40% s.d. Rp25.000, minimal belanja Rp50.000"*:
- Mendukung voucher **diskon/cashback persen** maupun **potongan nominal (Rp)**
- Hitung **potongan yang didapat** dari total belanjamu
- Kasih tahu **target belanja optimal** biar potongan maksimal (misalnya Rp62.500 untuk contoh di atas)
- Peringatan kalau belanja belum memenuhi minimal, atau kalau potongan sudah mentok

### Lainnya
- 🌗 **Mode terang / gelap** — pilihan tersimpan otomatis di browser
- 📱 Tampilan responsif, nyaman di HP maupun laptop
- 🔒 Semua perhitungan berjalan di browser, tidak ada data yang dikirim ke mana pun

## 🚀 Cara Pakai

1. Buka https://kalkulatorcuan.vercel.app
2. Pilih alat yang dibutuhkan (kartu **Alat 1** atau **Alat 2** di halaman utama)
3. Isi angka-angkanya, tekan tombol hitung — hasil langsung muncul

## 🛠️ Teknologi

- Satu file `index.html` — HTML + CSS + JavaScript murni, tanpa framework, tanpa build step
- `kalkulator_bisnis_cuan.html` adalah salinan identik dari `index.html`
- Siap deploy ke hosting statis mana pun (Vercel, Netlify, GitHub Pages)

## 💻 Menjalankan Lokal

```bash
git clone https://github.com/ncuyyGans/kalkulatorcuan.git
cd kalkulatorcuan
```

Lalu buka `index.html` langsung di browser, atau jalankan server lokal:

```bash
npx serve .
```

## 📄 Lisensi

Bebas dipakai dan dimodifikasi untuk keperluan apa pun.
