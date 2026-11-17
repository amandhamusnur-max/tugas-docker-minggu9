# Tugas Docker Minggu 9: Kontainerisasi Halaman Profil

Halaman profil sederhana milik Amandha J D P Musnur yang dijalankan dengan Docker (nginx:alpine).

## Cara Build
docker build -t profil-amandha:1.0 .

## Cara Run
docker run -d --name profil-amandha -p 8082:80 profil-amandha:1.0

Lalu buka http://localhost:8082 di browser.

## Screenshot
(tambahkan screenshot halaman profil di sini)
