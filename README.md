# Tugas Inco-Alterra 3: Vue Dasar

## Deskripsi Proyek

Proyek ini merupakan bagian dari tugas ketiga dalam program Inco-Alterra. Fokus utama dari proyek ini adalah untuk membangun aplikasi web sederhana dengan menggunakan Vue.js. Tujuan dari proyek ini adalah untuk memahami dasar-dasar Vue.js, termasuk pembuatan komponen, penggunaan data binding, dan implementasi reactivity dalam Vue.js.

## Struktur Proyek

-   `src/`
    -   `assets/`
    -   `components/`
    -   `App.vue`
    -   `main.js`
-   `public/`
    -   `index.html`
-   `babel.config.js`
-   `package.json`
-   `README.md`

### Penjelasan Folder dan File

#### `src/`

Folder `src` merupakan folder utama yang berisi semua source code aplikasi Vue.js. Di dalam folder ini, terdapat folder dan file sebagai berikut:

-   `assets/`: Menyimpan aset-aset statis seperti gambar dan file CSS.
-   `components/`: Menyimpan komponen-komponen Vue yang digunakan dalam aplikasi.
-   `App.vue`: Komponen root dari aplikasi Vue.
-   `main.js`: File entry point yang digunakan untuk menginisialisasi dan menjalankan aplikasi Vue.

#### `public/`

Folder `public` berisi file HTML utama yang akan di-render oleh aplikasi Vue.js. File utama di folder ini adalah:

-   `index.html`: File HTML utama yang menjadi template untuk aplikasi Vue.js.

#### `babel.config.js`

File konfigurasi untuk Babel, yang digunakan untuk transpile kode JavaScript modern agar kompatibel dengan browser yang lebih lama.

#### `package.json`

File konfigurasi yang berisi metadata proyek serta daftar dependencies dan script yang digunakan dalam proyek.

## Dependencies

Proyek ini menggunakan beberapa dependencies utama sebagai berikut:

-   **Babel**: Digunakan untuk transpile kode JavaScript modern.
-   **Vue CLI**: Alat yang digunakan untuk menginisialisasi dan mengelola proyek Vue.js.
-   **ESLint**: Alat yang digunakan untuk memastikan kualitas dan konsistensi kode JavaScript.

## Fitur Utama

1. **Komponen Vue**: Membuat dan menggunakan komponen Vue untuk membangun antarmuka pengguna yang modular dan dapat digunakan kembali.
2. **Data Binding**: Menggunakan data binding untuk mengikat data antara model dan tampilan secara reaktif.
3. **Reactivity**: Mengimplementasikan reactivity untuk memperbarui tampilan secara otomatis ketika data berubah.

## Cara Menggunakan

1. **Clone Repository**:

    ```sh
    git clone https://github.com/username/tugas-inco-alterra-3.git
    ```

2. **Install Dependencies**:

    Pindah ke direktori proyek dan install dependencies dengan perintah berikut:

    ```sh
    cd tugas-inco-alterra-3
    npm install
    ```

3. **Run Development Server**:

    Jalankan development server dengan perintah berikut:

    ```sh
    npm run serve
    ```

4. **Buka Aplikasi di Browser**:

    Buka browser dan akses alamat `http://localhost:5173` untuk melihat aplikasi Vue.js Anda.

**Date**: Jul 20, 2022

**Original Repository**:\
https://github.com/azkacrows/Latihan-Bootcamp/tree/main/Alterra
