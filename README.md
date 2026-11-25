https://anxerx-vix.github.io/kedai_kopi/
# Tugas Minggu 3 - Kopinang Aku

# Kopinang Aku
## 1. Sebutkan satu bagian yang kamu susun dengan Flexbox dan satu bagian dengan Grid. Mengapa pilihan itu cocok untuk kedua bagian tersebut?
Saya pakai Flexbox di bagian header (`.kepala` dan `nav ul`) untuk menaruh judul kedai di kiri dan link menu di kanan. Flexbox cocok di bagian ini karena isinya satu baris ke samping di layar laptop dan turun ke bawah di layar HP.

Di halaman `menu.html` (`.grid-menu`), saya pakai Grid untuk daftar menu. Grid cocok karena kartu menunya butuh susunan baris dan kolom yang bisa berubah dari 1 kolom di HP jadi 3 kolom di laptop.

## 2. Ceritakan satu aturan CSS yang awalnya tidak berlaku. Apa yang kamu lihat di panel Styles, dan bagaimana kamu memperbaikinya?
Pada awalnya, saya menulis `width: 100%` pada semua elemen `input`. Akibatnya, tombol pilihan *radio button* ikut melebar dan labelnya bergeser ke baris baru.

Setelah memeriksa elemen tersebut melalui panel *Styles* di Developer Tools, terlihat bahwa aturan `width: 100%` menimpa ukuran bawaan *radio button*. Saya memperbaikinya dengan membatasi selector hanya untuk `input[type="text"]`, `input[type="tel"]`, dan `input[type="number"]`.
