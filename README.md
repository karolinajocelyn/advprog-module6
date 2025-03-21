# advprog-module6

## Reflection 1

Pada tahap ini, saya membuat web server sederhana yang menerima koneksi dan membaca request HTTP menggunakan `BufReader`. Saya belajar bagaimana browser mengirim request dalam bentuk baris-baris teks, dan bagaimana Rust membaca baris-baris ini secara aman.

Hal yang menarik adalah Rust memperingatkan saya soal variabel yang tidak digunakan, yang membuat saya lebih sadar terhadap efisiensi kode. Saya juga memahami pentingnya konsep ownership di Rust, yang membuat proses seperti membaca stream lebih aman, walaupun awalnya agak membingungkan. Kode ini belum mengembalikan response ke client, tapi menjadi dasar untuk web server lebih kompleks.