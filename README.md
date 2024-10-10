# Pengolahan Citra dengan Berbagai Filter
Proyek ini mendemonstrasikan teknik dasar pengolahan citra menggunakan Python. Berbagai jenis filter diterapkan seperti filter rata-rata, median, minimum, maksimum, Laplacian, dan Sobel untuk mendeteksi tepi pada sebuah citra, kemudian hasilnya divisualisasikan dalam bentuk perbandingan.

## Fitur
- **Perhitungan Perbedaan**: Menghitung perbedaan antara dua gambar grayscale.
- **Filter Rata-rata**: Mengaburkan gambar dengan menghitung rata-rata nilai piksel di sekitar piksel target.
- **Filter Median**: Mengurangi noise dengan mengganti nilai piksel dengan nilai median dari tetangganya.
- **Filter Minimum & Maksimum**: Menonjolkan fitur tertentu dalam gambar dengan menerapkan filter minimum dan maksimum.
- **Filter Laplacian**: Menekankan tepi gambar dengan menggunakan kernel untuk menghitung turunan orde kedua.
- **Filter Gradien Sobel**: Menghitung gradien gambar pada sumbu X dan Y, menonjolkan tepi pada gambar.

## Instalasi
1. Clone repository ini:

   git clone <repository-url>
   
2. Install dependensi yang diperlukan:

    pip install -r requirements.txt

Dependensi meliputi:
- numpy
- matplotlib
- opencv-python
- scipy

## Penggunaan
1. Letakkan gambar input Anda di direktori proyek. Dalam contoh ini, gambar yang digunakan bernama bunga&bebek.jpg.
2. Jalankan script Python untuk menerapkan filter dan melihat hasilnya:

python image_filters.py

3. Script ini akan:
- Membaca gambar input dan mengonversinya ke grayscale jika diperlukan.
- Menerapkan setiap filter (rata-rata, median, minimum, maksimum, Laplacian, Sobel X, dan Sobel Y) pada gambar.
- Menampilkan gambar asli dan gambar hasil filter.

## Contoh Hasil
Setelah menjalankan script, Anda akan melihat beberapa subplot yang menampilkan perbandingan antara gambar asli dengan gambar yang telah difilter:
1. Gambar Asli: Gambar input dalam bentuk grayscale.
2. Filter Rata-rata: Gambar yang di-blur.
3. Filter Median: Gambar dengan noise yang berkurang.
4. Filter Minimum: Menonjolkan area gelap.
5. Filter Maksimum: Menonjolkan area terang.
6. Filter Laplacian: Menonjolkan tepi gambar.
7. Sobel X: Menampilkan tepi horizontal.
8. Sobel Y: Menampilkan tepi vertikal.
