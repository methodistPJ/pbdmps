# PBD Intelligence — SK Methodist (M) PJ

Pakej ini mengandungi frontend statik untuk GitHub Pages dan salinan rujukan backend Google Apps Script.

## Terbitkan di GitHub Pages

1. Muat naik `index.html` ke root repository.
2. Di GitHub, buka **Settings → Pages**.
3. Pilih sumber **Deploy from a branch**, branch utama, folder `/ (root)`.
4. Buka URL Pages yang diberikan selepas proses deployment selesai.

Frontend terus menggunakan endpoint Google Apps Script sedia ada. Google Sheet, Google Drive dan data arkib tidak dipindahkan ke GitHub. Apps Script berjalan sebagai akaun pemilik deployment, manakala pengguna hanya berinteraksi melalui dashboard.

ZIP GitHub sengaja hanya mengandungi frontend, `.nojekyll` dan panduan ini. Kod backend, konfigurasi GAS, hash akses, token sesi dan data murid tidak dimasukkan ke repository awam. Salinan pentadbiran backend kekal berasingan dalam folder kerja sekolah.

Untuk pelancaran rasmi, repository boleh dijadikan private semasa ujian dan ditukar mengikut polisi sekolah selepas semakan.
