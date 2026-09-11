# 🌿 Pretest Fotosintesis SD

## Fitur
- Nama siswa
- Kelas 4A, 4B, 4C, 4D
- 10 soal pilihan ganda fotosintesis
- Progress bar
- Desain cute dan interaktif untuk anak SD
- Nilai otomatis
- Review jawaban
- Siap GitHub Pages
- Bisa dihubungkan ke Google Sheets

## Upload ke GitHub
1. Ekstrak ZIP.
2. Buat repository baru.
3. Upload seluruh isi folder.
4. Settings → Pages.
5. Pilih branch main dan folder /root.
6. Simpan.

## Simpan hasil ke Google Sheets
1. Buat Google Sheet dengan sheet bernama `Pretest`.
2. Baris pertama:
Waktu | Nama | Kelas | Skor Benar | Nilai (%) | Soal 1 | Soal 2 | Soal 3 | Soal 4 | Soal 5 | Soal 6 | Soal 7 | Soal 8 | Soal 9 | Soal 10
3. Extensions → Apps Script.
4. Salin `apps-script/Code.gs`.
5. Deploy → New deployment → Web app.
6. Salin URL Web App.
7. Buka `index.html`, cari `const WEB_APP_URL=""`.
8. Masukkan URL Web App tersebut dan upload ulang ke GitHub.

Jika URL dibiarkan kosong, website berjalan dalam mode demo dan hasil tersimpan hanya pada perangkat/browser yang digunakan.
