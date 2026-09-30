Vortex Cloud Phone — Fixed Premium Landing Page

Perbaikan utama:
- Ikon FontAwesome ditambahkan/dirapikan di navbar, tombol, fitur, statistik, console, server, komunitas, footer.
- CDN FontAwesome dibuat valid tanpa integrity hash yang rusak.
- Horizontal overflow dikunci agar halaman tidak bisa digeser kiri/kanan.
- Background html/body tetap gelap saat overscroll cepat.
- Navbar fixed dirapikan untuk mobile/tablet/desktop.
- Mobile menu tidak menyebabkan layout melebar.
- Container, spacing, radius, dan grid diseragamkan.
- Console tetap interaktif sebagai simulasi frontend.
- logo.png dan logo.svg disertakan.

Jalankan index.html. Ganti link placeholder dan fungsi downloadAPK() dengan URL produksi.


Update tambahan:
- Badge verified-style berbentuk SVG vector ditambahkan di samping nama Vortex Cloud Phone pada navbar.
- Kartu Documentation sekarang membuka docs/index.html.
- Documentation lengkap dengan sidebar desktop, menu mobile, pencarian, code copy, Getting Started, Cloud Phone, Streaming, Developer API, ADB over WebRTC, Webhooks, Remote Touch Injection, Troubleshooting, FAQ, Changelog, dan Resources.
- Dokumentasi menandai contoh API sebagai contoh/simulasi sampai backend produksi benar-benar dihubungkan.


Update terbaru:
- Social links resmi diperbarui: Discord, YouTube, dan TikTok.
- Musik background resmi Vortex Cloud Phone ditambahkan sebagai `assets/Vortex Cloud Phone.mp3`.
- Website memakai layar Enter Vortex agar audio dapat mulai dengan interaksi pengguna sesuai kebijakan autoplay browser.
- Tombol music ON/OFF tersedia di pojok bawah.


Login + Video Update:
- Login awal kini memakai clear dark glass UI khas Vortex Cloud Phone.
- Video MP4 pengguna ditempatkan di `assets/vortex-login.mp4` dan diputar muted + loop di frame bagian atas login.
- Tombol `Lanjutkan dengan Google` sudah disiapkan untuk Firebase Authentication dengan Google Provider.
- Firebase config sengaja dikosongkan karena kredensial project harus berasal dari Firebase project milik Anda.
- Setelah Firebase dikonfigurasi, sesi login memakai browserLocalPersistence dan login yang valid akan membuka halaman utama.
- Musik tetap memakai `assets/Vortex Cloud Phone.mp3`, volume 40%, dan kontrol ON/OFF.
- Untuk mengaktifkan Google Login: isi `VORTEX_FIREBASE_CONFIG` di `index.html`, aktifkan Google provider di Firebase Authentication, dan tambahkan domain website pada Authorized Domains.
