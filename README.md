# Rekap Absensi LUNAPOS

[![AI Assisted](https://img.shields.io/badge/Developed%20with-AI%20Assistance-8b7cf8?style=flat-square&logo=openai&logoColor=white)](https://github.com/embercincau)
[![Client-Side](https://img.shields.io/badge/Client--Side-100%25-0d9488?style=flat-square)](https://github.com/embercincau)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

Aplikasi web berbasis *client-side* untuk mengolah dan merekapitulasi data laporan absensi dari sistem POS LUNAPOS secara otomatis langsung melalui peramban web (*browser*).

---

## 📌 Fitur Utama

* **Jadwal Shift Fleksibel per Hari**: Konfigurasi jam masuk resmi yang dapat dipilih berlaku pada hari-hari tertentu (Senin–Minggu) dan otomatis tersimpan di penyimpanan lokal (*localStorage*).
* **Toleransi Keterlambatan**: Pengaturan batas toleransi keterlambatan dalam hitungan menit.
* **Fitur Izin Telat**: Checkbox status izin pada log detail keterlambatan untuk mengampuni/mengabaikan keterlambatan pada tanggal tertentu secara *real-time*.
* **Formulir Kritik & Saran**: Form masukan terintegrasi yang mengirim pesan langsung ke Google Sheets.
* **Ekspor Laporan Resmi**: Unduh hasil rekapitulasi ke format **Excel (.xlsx)** (lengkap dengan status izin) dan format **PDF** berstandar dokumen resmi dengan kop laporan serta kolom tanda tangan *approval*.
* **Mode Gelap / Terang**: Dilengkapi *switch toggle* tema geser.
* **100% Client-Side & Aman**: Pemrosesan file `.xlsx`, `.xls`, atau `.csv` berjalan langsung di perangkat pengguna.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & Vanilla CSS3** (Desain responsif desktop & *mobile*, CSS Variables)
* **JavaScript (ES6+)**
* [SheetJS (xlsx.full.min.js)](https://sheetjs.com/) – Pembacaan dan pembuatan file Excel
* [jsPDF & jsPDF-AutoTable](https://github.com/parallax/jsPDF) – Pembuatan dokumen laporan PDF
* **Google Apps Script** – Integrasi pencatatan log akses dan kritik/saran ke Google Sheets

---

## 🚀 Cara Penggunaan

1. Buka file `index.html` pada peramban web atau akses melalui GitHub Pages.
2. Sesuaikan jam masuk serta hari aktif pada **Master Jadwal Shift Kerja** (pengaturan tersimpan otomatis di perangkat).
3. Atur batas **Toleransi Keterlambatan** jika diperlukan.
4. Unggah file laporan absensi LUNAPOS format `.xlsx`, `.xls`, atau `.csv`.
5. Lihat ringkasan dashboard, gunakan pencarian/filter outlet, klik nama karyawan untuk melihat detail atau menandai **Izin Telat**.
6. Unduh laporan dalam format **Excel** atau **PDF**.

---

## 👤 Author

Created by **[EMBERCINCAU](https://github.com/embercincau)**
