# Laporan RJTP — UPTD Puskesmas Mowewe

Aplikasi web untuk membuat **Laporan Pelayanan Rawat Jalan Tingkat Pertama (RJTP)** dalam format dokumen Word (.docx) yang siap cetak.

## ✨ Fitur

- Input data pasien langsung di tabel (klik sel untuk edit)
- Tambah/hapus baris secara dinamis
- Pilih bulan, tahun, dan nama desa secara custom
- Generate & unduh file `.docx` langsung dari browser
- Format landscape dengan tabel kolom lengkap (sesuai standar laporan RJTP)
- **Tidak ada server** — semua proses terjadi di browser, data tidak dikirim ke mana pun

## 🚀 Deploy ke GitHub Pages

1. Buat repository baru di GitHub (misal: `laporan-rjtp`)
2. Upload file `index.html` ke root repository
3. Buka **Settings → Pages**
4. Pada *Source*, pilih **Deploy from a branch** → branch `main` → folder `/ (root)`
5. Klik **Save** — tunggu beberapa menit
6. Akses di: `https://<username>.github.io/laporan-rjtp/`

## 📁 Struktur

```
laporan-rjtp/
└── index.html      ← satu file, langsung deploy
```

## 🛠 Teknologi

- HTML + CSS + JavaScript murni (vanilla)
- [docx.js](https://docxjs.com/) via CDN — generate file Word di browser
- Google Fonts — Plus Jakarta Sans & DM Mono

## 📄 Lisensi

Bebas digunakan untuk keperluan pemerintahan dan puskesmas.
