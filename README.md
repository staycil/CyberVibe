Cyber Defender: Pelatihan Kesadaran Keamanan Siber

Cyber Defender adalah aplikasi simulasi berbasis web (Single Page Application) yang dirancang untuk melatih dan menguji insting kesadaran keamanan siber (cybersecurity awareness) pengguna dalam menghadapi skenario serangan dunia nyata yang umum terjadi di lingkungan kerja.


Fitur Utama
- 10 Skenario Realistis & Interaktif:
  - Phishing & Invoice Fraud (BEC): Analisis domain pengirim email, tekanan urgensi, serta pratinjau tautan (link preview) sebelum mengeklik.
  - Legitimate Communications: Melatih ketajaman untuk membedakan antara ancaman nyata dan komunikasi kerja yang sah (email IT, telepon helpdesk, chat rekan kerja) guna menghindari false alarm.
  - Baiting (USB Drive): Simulasi interaksi drag-and-drop atau klik saat menemukan perangkat penyimpanan asing di area publik.
  - Vishing (Voice Phishing): Pengambilan keputusan cepat saat menerima panggilan telepon mencurigakan yang meminta kode OTP.
  - Pretexting & Smishing: Mengenali manipulasi identitas melalui pesan singkat (SMS) dan aplikasi chat internal.
  - Tailgating (Keamanan Fisik): Menerapkan protokol "one badge, one entry" di pintu akses ruang server.

- Sistem Penilaian & Batas Waktu (System Integrity):
  - Pemain memulai dengan 100% System Integrity. Kesalahan keputusan atau kehabisan waktu akan mengurangi skor.
  - Tersedia mode Relaxed Timer (2x waktu) bagi pengguna yang membutuhkan waktu analisis lebih lama.

- Sistem Petunjuk (Hint) & Umpan Balik Instan:
  - Fitur bantuan (Hint) dengan penalti skor kecil (-5%).
  - Analisis langsung (Red Flags) setelah setiap skenario untuk menjelaskan indikator bahaya atau alasan mengapa komunikasi tersebut aman.
  - Fitur Try Again yang menyoroti tanda bahaya (warning signs) secara visual pada layar.

- Papan Peringkat Global (Leaderboard):
  - Terintegrasi dengan Supabase REST API untuk menyimpan dan menampilkan skor tertinggi serta catatan waktu tercepat (terpisah untuk mode Standard dan Relaxed).

- Desain Aksesibel & Responsif:
  - Mendukung navigasi keyboard, atribut ARIA (screen reader friendly), serta opsi prefers-reduced-motion.

Teknologi yang Digunakan
- Frontend: HTML5, CSS3 (Custom Properties / CSS Variables, Flexbox), Vanilla JavaScript (ES6+).
- Backend / Database: Supabase (REST API untuk fitur Leaderboard).
- Penyimpanan Lokal: localStorage untuk menyimpan rekor pribadi (Best Score), preferensi timer, dan nickname pemain.


Cara Menjalankan Proyek
Karena aplikasi ini dibangun menggunakan HTML, CSS, dan JavaScript murni dalam satu berkas (self-contained), Anda tidak memerlukan proses build atau instalasi dependensi apa pun:

1. Unduh atau clone folder proyek ini ke komputer Anda.
2. Buka file CyberVibe.html langsung menggunakan peramban web modern (Chrome, Firefox, Edge, Safari) atau jalankan melalui ekstensi Live Server di VS Code.
3. Klik tombol "Mulai Simulasi Sekarang" pada halaman utama untuk memulai pelatihan.
4. Atau klik link dibawah
https://staycil.github.io/CyberVibe/

ENJOY UR GAME FELLAS!!
