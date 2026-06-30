# ARUS - Audio-Route Navigation Assistant

Aplikasi navigasi Android pintar berbasis peta TomTom yang mendukung perintah suara (Voice Command) dan fitur *Text-to-Speech* (TTS) untuk membacakan rute serta estimasi perjalanan dalam Bahasa Indonesia.

## 🚀 Fitur Utama

- **Pencarian Lokasi Cerdas (Voice & Text Input)**: Pengguna dapat mencari lokasi tujuan dengan mengetik langsung atau menggunakan perintah suara (*Speech-to-Text*).
- **Text-to-Speech (TTS) Terintegrasi**: Aplikasi secara otomatis membacakan rute yang siap, termasuk informasi jarak (km) dan estimasi waktu tempuh (menit) dalam Bahasa Indonesia.
- **Peta Interaktif TomTom SDK**: Menampilkan peta berkualitas tinggi lengkap dengan informasi arus lalu lintas secara real-time (*traffic flow*).
- **Kategori Lokasi Cepat (Quick Access POI)**: Akses sekali sentuh untuk mencari tempat-tempat penting di sekitar pengguna, seperti:
  - SPBU (Gas Station)
  - Rumah Sakit (Hospital)
  - Restoran (Restaurant)
  - Area Parkir (Parking Lot)
- **Lokasi Saya**: Menampilkan dan memfokuskan peta secara langsung pada posisi GPS pengguna saat ini secara real-time.

---

## 🛠️ Teknologi & SDK yang Digunakan

- **Bahasa**: Java & Kotlin (Android)
- **SDK Peta & Navigasi**: TomTom Maps SDK, TomTom Search API, TomTom Routing API
- **Engine Suara**:
  - Android Speech Recognizer (untuk input suara)
  - Android TextToSpeech Engine (untuk output suara Bahasa Indonesia)

---

## 📥 Cara Instalasi Aplikasi (APK)

1. Buka halaman repository ini di browser Anda.
2. Masuk ke bagian **Releases** di sebelah kanan halaman GitHub ini.
3. Unduh berkas **`app-debug.apk`** versi terbaru.
4. Buka berkas `.apk` yang telah diunduh di perangkat Android Anda.
5. Jika muncul peringatan keamanan, aktifkan opsi **Izinkan Instalasi dari Sumber Tidak Dikenal (Unknown Sources)**.
6. Buka aplikasi **ARUS** dan berikan izin akses berikut saat diminta agar fitur berjalan dengan lancar:
   - **Akses Lokasi (GPS)**: Untuk menentukan titik keberangkatan Anda.
   - **Akses Mikrofon (Audio)**: Untuk menggunakan fitur perintah suara.

---

## 📝 Lisensi
Proyek ini dibuat untuk keperluan akademis / praktikum navigasi berbasis peta. Semua hak cipta TomTom SDK dan Google Speech API dimiliki oleh masing-masing penyedia layanan.
