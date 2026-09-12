# LearnX Premium — Learning OS

Web app dashboard belajar futuristik, dibuat sebagai **base GitHub Pages** tanpa backend.

## Isi
- `index.html` — struktur aplikasi
- `styles.css` — UI premium, glassmorphism, animasi, responsive
- `app.js` — fingerprint simulation, video gate, dashboard, IQ quiz, Japanese lab, psychology lab, Pomodoro, notes, music dock
- `assets/intro.mp4` — video intro yang diberikan pengguna

## Cara menjalankan di GitHub
1. Buat repository baru di GitHub.
2. Upload semua isi folder ini dengan struktur yang sama.
3. Buka **Settings → Pages**.
4. Pada Source pilih **Deploy from a branch**, branch `main`, folder `/root`.
5. Simpan. Tunggu GitHub Pages selesai deploy.

## Penting
Fingerprint di sini adalah **simulasi UI**, bukan autentikasi biometrik HP yang sebenarnya.
Music dock memakai tone generator lokal sehingga tidak memerlukan file musik eksternal. Tombol pencarian memfilter katalog musik demo; untuk musik nyata, audio dapat dikembangkan menjadi playlist file lokal/URL yang memiliki izin penggunaan.

## Video
Video diputar setelah simulasi sidik jari berhasil. Saat video selesai, tombol **Berikutnya** muncul. Pengguna tetap berada di video sampai tombol ditekan.
