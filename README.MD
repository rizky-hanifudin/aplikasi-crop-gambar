# README

Ini adalah aplikasi [Flask](http://flask.pocoo.org/) untuk latihan ujian akhir saya.

Demo: [https://fumui-img-cropper.onrender.com](https://fumui-img-cropper.onrender.com)

Py Image Cropper adalah aplikasi web yang memungkinkan Anda mengunggah gambar, melihat pratinjau, memotong gambar berdasarkan posisi dan ukuran, serta mengunduh gambar yang telah dipotong. Aplikasi web ini dibangun menggunakan Flask dan OpenCV.

## Fitur

- Pilih file gambar dari perangkat lokal Anda.
- Pratinjau gambar yang dipilih sebelum dipotong.
- Pilih posisi pemotongan dari opsi yang telah ditentukan.
- Tentukan ukuran pemotongan sebagai nilai numerik.
- Potong gambar berdasarkan posisi dan ukuran yang dipilih.
- Lihat gambar yang telah dipotong.
- Unduh gambar yang telah dipotong.
- Unduh proses pemotongan sebagai file markdown.

## Instalasi

1. Clone repositori ini:

   ```bash
   git clone https://github.com/fumui/py-img-cropper.git
   ```

2. Pindah ke direktori proyek:

   ```bash
   cd py-img-cropper
   ```

3. Instal dependensi:

   ```bash
   pip install -r requirements.txt
   ```

## Penggunaan

1. Jalankan aplikasi web:

   ```bash
   python app.py
   ```

2. Buka web browser Anda dan kunjungi `http://localhost:5000`.

3. Pilih file gambar dengan mengklik tombol "Pilih gambar".

4. Pratinjau gambar yang telah dipilih.

5. Pilih posisi pemotongan dari daftar dropdown.

6. Tentukan ukuran pemotongan dalam piksel.

7. Klik tombol "Potong" untuk melakukan operasi pemotongan.

8. Lihat gambar yang telah dipotong.

9. Unduh gambar yang telah dipotong sebagai file markdown atau gambar.