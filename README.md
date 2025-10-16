[README.md](https://github.com/user-attachments/files/22955046/README.md)
# 🌾 Koperasi Simpan Pinjam Desa Sidorejo (KDMP)

Website koperasi digital bergaya modern seperti bank — dibuat untuk mendukung transparansi dan layanan keuangan di tingkat desa.

## 🏦 Fitur Utama
- **Login Admin** (username: `admin`, password: `kdmp1234`)
- **Form Pendaftaran Anggota** (tersimpan di LocalStorage)
- **Dashboard Admin** untuk melihat data anggota & ekspor Excel
- **Grafik Keuangan Tahunan** menggunakan Chart.js
- **Mode Gelap/Terang**
- **Desain responsif** dan mudah diakses di ponsel

## 📂 Struktur Folder
```
koperasi-sidorejo/
├── index.html       # Halaman utama koperasi
├── login.html       # Halaman login admin
├── admin.html       # Dashboard admin
└── assets/          # (opsional) tempat gambar/logo
```

## 🚀 Cara Menjalankan Secara Lokal
1. Ekstrak file `koperasi-sidorejo.zip`
2. Buka file `login.html` di browser
3. Login menggunakan:
   ```
   Username: admin
   Password: kdmp1234
   ```
4. Setelah login, kamu akan diarahkan ke halaman utama `index.html`
5. Buka `admin.html` untuk melihat data anggota

## 🌐 Upload ke GitHub Pages
1. Buat repositori baru bernama `koperasi-sidorejo`
2. Upload semua file dari folder proyek ini
3. Masuk ke **Settings → Pages**
4. Pilih:
   ```
   Source: Deploy from branch
   Branch: main / (root)
   ```
5. Tunggu 1–2 menit, lalu buka:
   ```
   https://username.github.io/koperasi-sidorejo/
   ```

## 💡 Teknologi yang Digunakan
- HTML5 + CSS3 + JavaScript
- Chart.js (visualisasi data)
- SheetJS (ekspor ke Excel)
- LocalStorage (penyimpanan sementara)

## 👨‍💻 Pengembang
Proyek ini dibuat untuk mendukung digitalisasi koperasi desa, dengan desain sederhana dan fungsional.
