**Nama	: RIZKY HANIFUDIN**

**NIM		: 201011400105**

**Kelas	: 06TPLE005**

**Cara Instalasi Aplikasi Crop Gambar**

# README

Aplikasi Crop Gambar adalah aplikasi web yang memungkinkan Anda mengunggah gambar, melihat pratinjau, memotong gambar berdasarkan posisi dan ukuran, serta mengunduh gambar yang telah dipotong. Aplikasi web ini dibangun menggunakan Flask dan OpenCV.

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
   git clone https://github.com/rizky-hanifudin/aplikasi-crop-gambar.git
   ```

2. Pindah ke direktori proyek:

   ```bash
   cd aplikasi-crop-gambar
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
![Run Aplikasi](https://github.com/rizky-hanifudin/aplikasi-crop-gambar/blob/main/tutorial/run.png "Sorot gambar, akan keluar tulisan ini")

2. Buka web browser Anda dan kunjungi `http://127.0.0.1:5000`.
![Tampilan Aplikasi](https://github.com/rizky-hanifudin/aplikasi-crop-gambar/blob/main/tutorial/web.png "Sorot gambar, akan keluar tulisan ini")

3. Pilih file gambar dengan mengklik tombol "Pilih gambar".

4. Pratinjau gambar yang telah dipilih.
![Berhasil Upload](https://github.com/rizky-hanifudin/aplikasi-crop-gambar/blob/main/tutorial/upload.png "Sorot gambar, akan keluar tulisan ini")

5. Pilih posisi pemotongan dari daftar dropdown.

6. Tentukan ukuran pemotongan dalam piksel.
   \*Catatan jika ukuran crop melebihi ukuran gambar maka akan gagal.
Hasil jika ukuran crop melebihi ukuran gambar:
![Gagal Crop](https://github.com/rizky-hanifudin/aplikasi-crop-gambar/blob/main/tutorial/error.png "Sorot gambar, akan keluar tulisan ini")

7. Klik tombol "Potong" untuk melakukan operasi pemotongan.

8. Lihat gambar yang telah dipotong.

9. Unduh gambar yang telah dipotong sebagai file markdown atau gambar.
![Berhasil](https://github.com/rizky-hanifudin/aplikasi-crop-gambar/blob/main/tutorial/berhasil.png "Sorot gambar, akan keluar tulisan ini")
