# Tugas Minggu 2 - Kopi Pojok

## 1. Apa yang muncul di address bar setelah form dikirim, dan mengapa data form tampil di sana?

Setelah tombol Kirim ditekan, di ujung URL pada address bar muncul tanda tanya (`?`) diikuti nama input dan isiannya, contohnya:

`pesan.html?nama=Andi&whatsapp=08123456789&menu=americano&jumlah=2&cara_ambil=ambil&catatan=es+sedikit`

Data tersebut tampil di address bar karena tag `<form>` memakai `method="get"`. Sesuai materi HTTP Minggu 1, browser mengirim request `GET` dengan cara menempelkan data form langsung ke bagian query string URL.

## 2. Pemilihan element semantic dan alasannya dibanding `<div>`

Saya memakai element `<nav>` di dalam `<header>` untuk membungkus daftar link antarhalaman (Beranda, Menu, dan Pesan). Kalau memakai `<div>`, browser cuma membacanya sebagai kotak pembungkus biasa tanpa tahu fungsinya. Dengan `<nav>`, browser dan pembaca layar (screen reader) bisa mengenali bahwa bagian itu adalah navigasi utama situs.