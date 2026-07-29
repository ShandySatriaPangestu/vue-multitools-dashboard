# **Ujian Akhir Semester (UAS) - Praktikum Pemrograman Berbasis Komponen (PBK)**

Aplikasi web interaktif berbasis **Vue.js** yang dikembangkan sebagai pemenuhan tugas Ujian Akhir Semester. Aplikasi ini menerapkan konsep *Single Page Application (SPA)* menggunakan **Vue Router** dengan berbagai fitur fungsional dan mini games di dalamnya.

---

## **👤 Identitas Pemilik**
* **Nama:** Sendi Satria Pangestu
* **NIM:** 213510800
* **Instagram/Social:** `@thisis_shndy`

---

## **🚀 Daftar Fitur & Menu Aplikasi**
Aplikasi ini memiliki navigasi berbasis *router* yang mencakup beberapa fitur berikut:
1. **Cuaca:** Memantau informasi kondisi cuaca secara *real-time*.
2. **Lokasi:** Menampilkan informasi titik lokasi pengguna.
3. **StopWatch:** Fitur penghitung waktu (*timer/stopwatch*).
4. **Foto Random:** Menampilkan galeri atau generator foto acak secara dinamis.
5. **Game Tebak Angka:** Permainan interaktif menebak angka dengan logika JavaScript.
6. **Game Penjaga Pintu:** Mini game interaktif bertema penjaga pintu.

---

## **💻 Teknologi yang Digunakan**
* **Vue.js** (Frontend Framework)
* **Vue Router** (Manajemen Halaman SPA)
* **HTML5 & CSS3** (Custom styling, flexbox, dan animasi latar belakang GIF)
* **JavaScript (ES6)**

---

## **📂 Struktur Direktori Proyek**
```text
├── public/
├── src/
│   ├── assets/          # Aset gambar, ikon, dan background GIF
│   ├── components/      # Komponen-komponen pendukung Vue
│   ├── router/          # Konfigurasi Vue Router
│   ├── views/           # Halaman utama dari setiap menu (Cuaca, Game, dll)
│   ├── App.vue          # Layout utama aplikasi
│   └── main.js          # Entry point utama Vue
├── index.html
├── package.json
└── README.md            # Dokumentasi proyek

⚙️ Cara Menjalankan Proyek

    Clone repository ini ke komputer lokal Anda:
    Bash

    git clone [https://github.com/ShandySatriaPangestu/213510800_SendiSatriaPangestu_UAS_Prak_PBK.git](https://github.com/ShandySatriaPangestu/213510800_SendiSatriaPangestu_UAS_Prak_PBK.git)

    Masuk ke dalam direktori proyek:
    Bash

    cd 213510800_SendiSatriaPangestu_UAS_Prak_PBK

    Install dependensi:
    Bash

    npm install

    Jalankan server lokal untuk mode pengembangan:
    Bash

    npm run serve
