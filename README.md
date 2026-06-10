# 🌌 X-Downloader (Futuristic Web Frontend)

Situs web berbasis statis dengan tampilan modern dan futuristik yang berfungsi sebagai antarmuka (frontend) untuk aplikasi pengunduh video/audio YouTube. Web ini terhubung langsung secara real-time dengan custom API backend yang di-host di Hugging Face.

Proyek ini dideploy menggunakan **GitHub Pages** dan dapat dicoba langsung di: `https://restagan.github.io/Nama-Repositori-Kamu/`

## ✨ Fitur & Kelebihan UI
- **Futuristic Dark Theme:** Desain bertema gelap dengan aksen neon biru dan ungu untuk memberikan kesan teknologi masa depan.
- **Glassmorphism Effect:** Menggunakan teknik desain modern berbasis transparansi kaca (`backdrop-filter`) pada kartu utama.
- **Responsive & Interactive UI:** Tampilan yang adaptif di HP maupun laptop, dilengkapi dengan animasi *smooth fading* serta indikator *loading state* (spinner) saat sistem sedang bekerja.
- **Real-time Metadata Fetching:** Menampilkan judul video, nama channel, durasi, dan thumbnail secara instan sebelum user memutuskan untuk mengunduh.

## 🛠️ Teknologi yang Digunakan
- **HTML5 & CSS3** (Struktur halaman, variabel CSS, dan kustomisasi animasi)
- **JavaScript (ES6+)** (Menggunakan *Async/Await* dan *Fetch API* untuk komunikasi asinkronus ke server)
- **FontAwesome Icons** (Untuk kebutuhan ikon video dan musik)
- **Google Fonts (Plus Jakarta Sans)** (Untuk tipografi yang bersih dan profesional)

## 💡 Cerita & Pengalaman Belajar (My Learning Experience)
Proyek frontend ini mengasah kemampuan saya dalam menerjemahkan ide visual menjadi kode yang fungsional. Melalui proyek ini, saya belajar tentang:
1. **Komunikasi Antar-Domain (CORS):** Memahami bagaimana frontend statis yang di-host di GitHub Pages berinteraksi dengan API backend di server terpisah secara aman.
2. **Manipulasi Blob & File Streaming:** Belajar bagaimana JavaScript menangani data mentah (*binary/blob*) yang dikirim oleh server, lalu mengubahnya menjadi file unduhan fisik (MP3/MP4) di browser pengguna lengkap dengan nama file aslinya.
3. **Asynchronous JavaScript:** Memperdalam pemahaman tentang *promises* untuk memastikan UI tidak macet (*freeze*) saat menunggu proses unduhan video yang membutuhkan waktu beberapa saat di sisi server.

---
Dibuat sebagai bagian dari perjalanan belajar software development oleh **Restagan**.
