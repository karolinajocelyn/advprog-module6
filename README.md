# advprog-module6

## Reflection 1

Pada tahap ini, saya membuat web server sederhana yang menerima koneksi dan membaca request HTTP menggunakan `BufReader`. Saya belajar bagaimana browser mengirim request dalam bentuk baris-baris teks, dan bagaimana Rust membaca baris-baris ini secara aman.

Hal yang menarik adalah Rust mengajari saya tentang variabel yang tidak digunakan, yang membuat saya lebih sadar terhadap efisiensi kode. Saya juga memahami pentingnya konsep ownership di Rust, yang membuat proses seperti membaca stream lebih aman, walaupun awalnya agak membingungkan. Kode ini belum mengembalikan response ke client, tapi menjadi dasar untuk web server lebih kompleks.

## Reflection 2

![Commit 2 screenshot](assets/images/reflection2.png)

Pada bagian ini, saya memodifikasi fungsi handle_connection agar web server dapat mengembalikan halaman HTML sederhana ke browser. Saya belajar bagaimana format HTTP response disusun, termasuk baris status dan header seperti Content-Length. Saya juga mengenal penggunaan fungsi fs::read_to_string untuk membaca file HTML yang dikirimkan ke client. Rust memaksa saya menulis kode yang eksplisit dan aman, terutama saat mengelola file dan koneksi. Saya mulai melihat bagaimana web server berinteraksi langsung dengan browser, bukan sekadar mencetak ke console. Pengalaman ini membuka wawasan saya soal komunikasi client-server dari sisi server low-level.