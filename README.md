# Rekap Absensi LUNAPOS

[![AI Assisted](https://img.shields.io/badge/Developed%20with-AI%20Assistance-8b7cf8?style=flat-square&logo=openai&logoColor=white)](https://github.com/embercincau)
[![Client-Side](https://img.shields.io/badge/Client--Side-100%25-0d9488?style=flat-square)](https://github.com/embercincau)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

Aplikasi web berbasis *client-side* untuk mengolah dan merekapitulasi data laporan absensi dari sistem POS LUNAPOS secara otomatis langsung melalui peramban web (*browser*).

---

## 📌 Fitur Utama

* **Pencocokan Shift Otomatis**: Menghitung keterlambatan dengan mencocokkan jam masuk aktual karyawan ke jadwal shift terdekat untuk hari kerja (*Weekday*) maupun akhir pekan (*Weekend*).
* **Toleransi Keterlambatan**: Konfigurasi menit toleransi keterlambatan sesuai kebijakan outlet.
* **Filter & Pencarian**: Filter ringkasan data berdasarkan outlet serta pencarian nama karyawan secara *real-time*.
* **Popup Log Detail**: Rincian riwayat keterlambatan karyawan (tanggal, hari, shift, jam jadwal, jam aktual, dan menit telat) yang tersusun kronologis dari tanggal awal ke terbaru.
* **Ekspor Laporan**: Unduh hasil rekapitulasi ke format **Excel (.xlsx)** (termasuk ringkasan & log detail) dan format **PDF**.
* **Mode Gelap / Terang**: Dilengkapi *switch toggle* tema geser.
* **100% Client-Side & Aman**: Pemrosesan file `.xlsx`, `.xls`, atau `.csv` berjalan langsung di perangkat pengguna tanpa mengunggah data ke server luar.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & Vanilla CSS3** (Desain responsif desktop & *mobile*, CSS Variables)
* **JavaScript (ES6+)**
* [SheetJS (xlsx.full.min.js)](https://sheetjs.com/) – Pembacaan dan pembuatan file Excel
* [jsPDF & jsPDF-AutoTable](https://github.com/parallax/jsPDF) – Pembuatan dokumen laporan PDF

---

## 🚀 Cara Penggunaan

1. Buka file `index.html` pada peramban web atau akses melalui GitHub Pages.
2. Atur jam masuk pada **Master Jadwal Shift Kerja** dan tentukan batas **Toleransi Keterlambatan** (opsional).
3. Unggah file laporan absensi LUNAPOS format `.xlsx`, `.xls`, atau `.csv`.
4. Lihat ringkasan dashboard, klik nama karyawan untuk melihat detail, atau unduh laporan dalam format Excel / PDF.

---

## 👤 Author

Created by **[EMBERCINCAU](https://github.com/embercincau)**
