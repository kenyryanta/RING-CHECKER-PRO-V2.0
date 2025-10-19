# 💍 Ring Checker Pro

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![made-with-tkinter](https://img.shields.io/badge/Made%20with-Tkinter-red)](https://docs.python.org/3/library/tkinter.html)

**Ring Checker Pro** adalah aplikasi desktop interaktif berbasis Python yang dirancang untuk menganalisis struktur aljabar yang dikenal sebagai *ring*. Aplikasi ini sangat berguna bagi mahasiswa, pengajar, dan peneliti di bidang matematika untuk memvalidasi dan menjelajahi properti-properti dari sebuah ring.


*Tampilan antarmuka Ring Checker Pro dengan tema Forest-dark.*

---

## ✨ Fitur Utama

-   🎨 **GUI Modern & Responsif**: Dilengkapi dengan tema gelap (Forest) dan terang (Azure) untuk kenyamanan visual.
-   🔢 **Tabel Operasi Interaktif**: Input tabel operasi penjumlahan dan perkalian dengan mudah.
-   🔬 **Analisis Properti Mendalam**:
    -   Asosiativitas, Komutativitas, Distributivitas
    -   Elemen Satuan (Unity) & Invers
    -   Pembagi Nol (Zero Divisors)
-   🏷️ **Klasifikasi Ring**: Secara otomatis menentukan apakah ring termasuk **Field**, **Integral Domain**, **Division Ring**, dan lainnya.
-   💾 **Manajemen Data**:
    -   Simpan dan muat kalkulasi ke/dari database **SQLite**.
    -   Impor dan ekspor data dalam format **JSON**.
-   ⚡ **Analisis Multi-threaded**: Menganalisis ring di *background thread* agar antarmuka tetap responsif.
-   📚 **Contoh Bawaan**: Sudah termasuk contoh-contoh ring seperti $Z_3$, Boolean Ring, dan lainnya untuk memulai.

---

## 🚀 Instalasi dan Menjalankan Aplikasi

Pastikan Anda sudah memiliki **Python 3** terpasang di sistem Anda.

1.  **Clone Repository**
    ```bash
    git clone [https://github.com/your-username/ring-checker-pro.git](https://github.com/your-username/ring-checker-pro.git)
    cd ring-checker-pro
    ```

2.  **Install Dependencies**
    Aplikasi ini menggunakan `customtkinter`, `ttkthemes`, dan `sv-ttk`. Install semuanya dari file `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Jalankan Aplikasi**
    Untuk menjalankan aplikasi, eksekusi skrip `final.py`:
    ```bash
    python final.py
    ```

---

## 📖 Cara Menggunakan

1.  **Buka Aplikasi**: Jalankan skrip seperti petunjuk di atas.
2.  **Tentukan Ukuran Ring**: Pilih ukuran ring yang diinginkan (misalnya, 3 untuk ring dengan 3 elemen: A, B, C).
3.  **Generate Tabel**: Klik tombol **'Generate Table'**.
4.  **Isi Tabel Operasi**: Lengkapi tabel penjumlahan dan perkalian. Pastikan setiap entri adalah elemen ring yang valid (misalnya, A, B, C).
5.  **Analisis**: Klik **'Analyze Ring'** untuk melihat hasil analisis properti dan klasifikasi ring di panel kanan.
6.  **Gunakan Sampel**: Jelajahi contoh-contoh ring yang sudah ada di tab **'Samples'**.
7.  **Simpan & Muat**: Gunakan menu `File` untuk menyimpan, memuat, mengimpor, atau mengekspor pekerjaan Anda.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Aksi                  |
| :------- | :-------------------- |
| `Ctrl+N` | Kalkulasi Baru        |
| `Ctrl+S` | Simpan Kalkulasi      |
| `F11`    | Toggle Fullscreen Mode|

> **📝 Catatan Penting**
> Pastikan semua sel dalam tabel operasi terisi dengan benar. Setiap entri harus merupakan elemen ring yang telah didefinisikan (A, B, C, dst.). Input yang tidak valid akan menyebabkan analisis gagal.
