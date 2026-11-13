# Sistem Aplikasi Koperasi KKUB Kantor Pusat

Aplikasi Manajemen Simpan Pinjam Koperasi KKUB berbasis web dengan sistem perhitungan bunga pinjaman (Flat, Efektif, Anuitas), pencatatan mutasi simpanan, laporan keuangan bulanan otomatis, keamanan Autentikasi Dua Faktor (2FA), dan integrasi cloud database Google Firebase Firestore.

## 🚀 Fitur Utama
- **Dashboard Ringkasan Eksekutif**: Pantau total aset simpanan, kredit beredar, NPL portofolio, dan tagihan jatuh tempo.
- **Simulasi & Kalkulator Kredit**: Simulasi perhitungan bunga Flat, Efektif (Menurun), dan Anuitas secara transparan.
- **Pengelolaan Pinjaman & Angsuran**: Pembuatan akad pinjaman otomatis memproduksi jadwal angsuran bulanan, pencatatan pembayaran cicilan, dan kwitansi resmi.
- **Buku Mutasi Simpanan**: Setor dan tarik simpanan pokok, wajib, dan sukarela tanpa batasan nominal.
- **Laporan Lengkap & Cetak Resmi**: Laporan kinerja bulanan, arus kas, dan laporan rinci cicilan anggota dengan kop surat dan tanda tangan pengurus resmi.
- **Backup & Restore Database**: Fitur cadangkan data ke file `.json` lokal dan pemulihan database instan.
- **Keamanan 2FA**: Autentikasi dua faktor untuk transaksi pencairan kredit dan penarikan dana.

## 🛠️ Teknologi
- **Frontend Framework**: React 19 + TypeScript
- **Bundler & Tooling**: Vite
- **Styling**: Tailwind CSS
- **Database & Auth**: Google Cloud Firebase Firestore & Firebase Authentication
- **Icons**: Lucide React

## 📦 Menjalankan Proyek Secara Lokal
```bash
# 1. Install dependensi
npm install

# 2. Jalankan server pengembangan
npm run dev

# 3. Bangun untuk produksi
npm run build
```

## 🌐 Deploy ke Netlify / Vercel
- **Build command**: `npm run build`
- **Publish directory**: `dist`
