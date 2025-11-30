# ☁️ Weather Dashboard Premium
Aplikasi Dashboard Cuaca Interaktif dan Responsif

Proyek ini adalah implementasi Weather Dashboard modern yang menampilkan data cuaca saat ini dan ramalan cuaca hingga 7 hari ke depan. Dibangun menggunakan HTML, JavaScript murni, dan styling dengan Tailwind CSS, dashboard ini menawarkan fitur interaktif penuh termasuk toggle tema gelap/terang, konversi suhu, dan manajemen kota favorit.

# 🌟 Fitur Utama
Aplikasi ini memenuhi dan melebihi spesifikasi proyek, dengan fokus pada pengalaman pengguna yang cepat dan informatif.

1. Tampilan Cuaca Saat Ini (Current Weather)
Data Lengkap: Menampilkan Suhu, Kelembaban, Kecepatan Angin (dalam km/j), dan Indeks UV.

Kondisi Visual: Kondisi cuaca dilengkapi dengan ikon cuaca yang sesuai (weather-icons).

Lokasi dan Waktu: Menampilkan Lokasi (Nama Kota) dan Timestamp eksplisit yang menunjukkan waktu terakhir data diperbarui.

Pembaruan Real-time: Data cuaca diperbarui secara otomatis setiap 5 menit menggunakan setInterval().

2. Ramalan Cuaca
Ramalan 7 Hari: Menampilkan ramalan cuaca harian, termasuk Min/Max Temperature serta Ikon dan Deskripsi Cuaca singkat.

Ramalan Per Jam: Menyediakan ramalan rinci untuk beberapa jam ke depan di hari yang sama.

3. Fungsionalitas Pencarian
Cari Kota: Pengguna dapat mencari cuaca berdasarkan Nama Kota.

Auto-complete: Dilengkapi dengan fitur auto-complete yang memberikan saran nama kota (contoh: Jakarta, New York, dll.) saat mengetik.

Kota Favorit:

Pengguna dapat Menyimpan Kota Favorit.

Tersedia tampilan khusus untuk melihat daftar kota favorit secara detail.

4. Fitur Interaktif & UX
Toggle Satuan Suhu: Tombol untuk beralih antara satuan Celsius (°C) dan Fahrenheit (°F).

Toggle Tema: Tombol untuk beralih antara mode Dark Theme (Tema Gelap) dan Light Theme (Tema Terang), dengan preferensi tersimpan di Local Storage.

Tombol Refresh: Memungkinkan pembaruan data cuaca secara manual.

Loading Indicators: Tampilan indikator memuat (<i class="fas fa-spinner fa-spin">) saat data sedang diambil dari API.

Navigasi Sidebar: Navigasi sederhana untuk beralih antara tampilan Cuaca Utama dan Daftar Kota Favorit.

# 💻 Teknologi
HTML5
JavaScript (ES6+)
Styling: Tailwind CSS (CDN)
Ikon:
Font Awesome (Untuk ikon UI)
Weather Icons (Untuk ikon kondisi cuaca)
Data Cuaca: OpenWeatherMap API

# ⚙️ Cara Menjalankan Proyek
Proyek ini adalah aplikasi front-end tunggal dan sangat mudah dijalankan.

Persiapan API Key
Dapatkan API Key dari OpenWeatherMap.

Buka file index.html.

Cari baris kode JavaScript berikut di bagian <script>:

JavaScript

# const API_KEY = "884c11bb928cc0efea9b205631f65274"; // GANTI DENGAN API KEY ANDA
Ganti nilai string tersebut dengan API Key OpenWeatherMap Anda yang valid.

Eksekusi
Cukup buka file index.html menggunakan web browser apa pun (Chrome, Firefox, Edge, dll.).

Anda dapat mengklik kanan pada file dan memilih "Open with" atau "Buka dengan" browser.

Aplikasi akan langsung memuat data cuaca untuk kota default (Bandar Lampung) dan siap digunakan.
