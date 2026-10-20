# Asisten Akademik & Tugas UT (JawabDiskusi AI)

Aplikasi web berbasis Single Page Application (SPA) yang dirancang khusus untuk membantu mahasiswa Universitas Terbuka (UT)—khususnya Program Studi Sistem Informasi—dalam menyusun draf jawaban diskusi Tuton, tugas kuliah, dan proposal Metode Penelitian (Metopen).

## 🚀 Fitur Utama

- **KOP BJU UT Otomatis**: Hasil jawaban dilengkapi KOP Kertas Jawaban Resmi UT yang siap dicetak/diekspor.
- **Humanizer & Anti-AI Engine**: Menggunakan prompt engineering khusus untuk menghasilkan gaya bahasa naratif alami (persentase skor deteksi AI teroptimasi).
- **Multi-File Reference Manager**: Mendukung pembacaan materi modul PDF/TXT menggunakan PDF.js secara langsung di browser.
- **Referensi Akademik**: Integrasi sitasi otomatis format APA 7th Edition, BMP UT, UU ITE/PDP, dan standar IT (ISO/COBIT).
- **Ekspor & Riwayat**: Fitur salin cepat, unduh Word (.docx), cetak PDF, dan penyimpanan draf otomatis di `localStorage`.

## 🛠️ Teknologi yang Digunakan

- **Frontend**: HTML5, Tailwind CSS (via CDN)
- **Engine JS**: Native Vanilla JavaScript (ES6+)
- **AI Integration**: Google Gemini REST API
- **PDF Extraction**: PDF.js (Mozilla)

## 🔒 Keamanan API Key

Aplikasi ini berjalan sepenuhnya di sisi klien (*Client-side*). Gemini API Key disimpan secara aman di `localStorage` browser pengguna dan tidak pernah dikirimkan ke server eksternal mana pun selain endpoint resmi Google AI Studio.
