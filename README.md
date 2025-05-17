- 👋 Hi, I’m @AfaCodea
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

AfaCodea/AfaCodea is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.

# Analisis Sinyal DTMF menggunakan Python

Proyek ini menyediakan skrip Python untuk menganalisis file audio yang berisi sinyal DTMF (Dual-Tone Multi-Frequency). Skrip ini akan memvisualisasikan spektrum frekuensi dari sinyal audio dan mencoba mengidentifikasi dua frekuensi dominan yang membentuk nada DTMF.

## Latar Belakang

Sinyal DTMF digunakan dalam sistem telekomunikasi, misalnya pada tombol angka di telepon. Setiap tombol menghasilkan kombinasi unik dari dua frekuensi: satu frekuensi dari grup rendah dan satu frekuensi dari grup tinggi. Dengan menganalisis frekuensi-frekuensi ini, kita dapat menentukan tombol mana yang ditekan.

Latihan ini mengikuti langkah-langkah berikut (seperti yang dijelaskan dalam gambar `image_228d01.jpg`):
1.  Upload file audio ke Google Colab.
2.  Lakukan konversi agar menjadi PCM.
3.  Gunakan FFT untuk menampilkan spektrum frekuensi.
4.  Tampilkan frekuensi dominan di atas grafik.

## Fitur

* Mengunggah file audio langsung di lingkungan Google Colab.
* Memuat dan mengonversi file audio ke format PCM menggunakan `librosa`.
* Menghitung dan menampilkan spektrum frekuensi menggunakan Fast Fourier Transform (FFT) dari `numpy`.
* Memvisualisasikan spektrum frekuensi menggunakan `matplotlib`.
* Mencoba mengidentifikasi dan menyorot dua frekuensi DTMF dominan pada grafik.

## Persyaratan

* Python 3.x
* Lingkungan Google Colaboratory (disarankan, karena kode menggunakan `google.colab.files` untuk unggahan) atau lingkungan Python lokal dengan pustaka berikut terinstal:
    * `librosa`: Untuk pemrosesan audio.
    * `numpy`: Untuk operasi numerik dan FFT.
    * `matplotlib`: Untuk membuat plot.

Jika menjalankan secara lokal (bukan di Colab), Anda dapat menginstal pustaka yang diperlukan menggunakan pip:
```bash
pip install librosa numpy matplotlib
