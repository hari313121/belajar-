# Aplikasi Belajar Anak Interaktif (Gemini AI + Canvas + TTS)

Aplikasi Android interaktif untuk anak usia 5 tahun untuk belajar membaca dan menulis angka & huruf dengan bantuan Google Gemini AI untuk materi dinamis dan Text-To-Speech (TTS) bersuara anak-anak.

## Fitur Utama
- **Gemini AI Integration:** Soal, huruf, angka, dan pesan semangat diproduksi secara dinamis via Google Gemini API.
- **Suara Anak (TTS):** Menggunakan Text-To-Speech Android dengan pitch tinggi dan nada ceria seperti anak-anak.
- **Canvas Interaktif:** Menjiplak dan menebalkan huruf/angka dengan kuas warna-warni cerah.
- **Build Otomatis (CI/CD):** GitHub Actions workflow untuk merakit file APK secara otomatis di Cloud.

## Cara Konfigurasi Gemini API Key
Tambahkan API Key di `MainActivity.kt` pada variabel `GEMINI_API_KEY`. API Key bisa didapatkan secara gratis di Google AI Studio (aistudio.google.com).
