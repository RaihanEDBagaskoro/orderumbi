# Kebijakan Keamanan

## Versi yang Didukung

Orderumbi masih berada pada tahap pengembangan awal. Perbaikan keamanan
diterapkan pada versi terbaru di branch `main`.

## Melaporkan Kerentanan

Jangan melaporkan kerentanan yang memuat data sensitif melalui issue publik.

Data sensitif meliputi:

- Nomor telepon pelanggan
- Nama dan alamat pelanggan
- Isi pesanan
- Informasi pribadi lainnya
- Langkah eksploitasi yang dapat membahayakan pengguna

Untuk melaporkan kerentanan, gunakan fitur pelaporan keamanan privat GitHub
jika tersedia atau hubungi maintainer melalui informasi kontak pada profil
GitHub.

Sertakan informasi berikut:

- Penjelasan kerentanan
- File atau fitur yang terdampak
- Langkah untuk mereproduksi masalah
- Dampak yang mungkin terjadi
- Saran perbaikan, jika tersedia

Maintainer akan memeriksa laporan dan memberikan tanggapan setelah informasi
yang diperlukan tersedia.

## Ruang Lingkup

Kebijakan ini mencakup:

- Kode HTML, CSS, dan JavaScript dalam repositori
- Formulir pemesanan
- Integrasi WhatsApp
- Deployment melalui GitHub Pages

## Praktik Keamanan

Kontributor harus:

- Tidak menyimpan data pelanggan di repositori
- Tidak mengunggah kredensial, token, atau kata sandi
- Memvalidasi input pengguna
- Memeriksa kode sebelum melakukan commit
- Menghindari dependensi yang tidak diperlukan
