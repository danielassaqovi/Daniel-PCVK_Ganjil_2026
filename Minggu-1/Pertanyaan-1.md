# Pengolahan Citra dan Visi Komputer – Jurusan Teknologi Informasi

## Pertanyaan

### 1. Google Colab

Jelaskan, mengapa pada modul praktikum ini eksekusi kode Python dilakukan menggunakan **Google Colab**?

### 2. Library pada Praktikum

Jelaskan mengenai kegunaan setiap **library** pada praktikum langkah ke-8.

Apakah semua library tersebut harus digunakan dalam praktikum sesi ini? Jelaskan!

### 3. Uji Coba Langkah ke-9

Pada uji coba langkah ke-9 terdapat potongan kode program sebagai berikut:

```python
    image = cv.resize(image, (0, 0), fx=0.5, fy=0.5)
```

Apa kegunaan kode program tersebut? Dan apa pengaruhnya jika kode tersebut tidak dilakukan?

### 4. Nilai `[255, 255, 255]`

Perhatikan potongan kode program berikut:

```python
for y in range (lebar):
    image_3 [int((tinggi)/2),y] = [255,255,255]
```

Apakah kegunaan kode:

```python
[255, 255, 255]
```

Jelaskan!

### 5. Pixel dan Resolusi Gambar

Jelaskan keterkaitan antara **pixel** dan **resolusi gambar**, baik pada gambar dengan resolusi tinggi maupun rendah.

## Jawaban

### 1.Google Colab
Karena Google Colab menyediakan GPU dan juga environment yang terinstall library yang dibutuhkan untuk praktikum ini.

### 2.Library pada Praktikum
- NumPy: mengolah array dan data numerik.
- Pandas: mengolah data berbentuk tabel.
- OpenCV: pengolahan dan manipulasi gambar.
- Scikit-image: pengolahan dan transformasi gambar.
- Pillow: membaca dan memanipulasi gambar.
- Matplotlib: menampilkan dan memvisualisasikan gambar.

### 3. Uji Coba Langkah ke-9

```python
    image = cv.resize(image, (0, 0), fx=0.5, fy=0.5)
```

Kode tersebut mengecilkan ukuran gambar menjadi 50% dari ukuran awal. 

### 4. Nilai `[255, 255, 255]`

Nilai [255, 255, 255] menunjukkan nilai tiga channel warna RGB. Karena semuanya bernilai 255, pixel tersebut berwarna putih.

### 5. Pixel dan Resolusi Gambar

Pixel adalah bagian terkecil penyusun gambar digital. Resolusi menunjukkan jumlah pixel pada gambar dalam bentuk lebar × tinggi.

Resolusi tinggi memiliki lebih banyak pixel sehingga detail gambar lebih tinggi, sedangkan resolusi rendah memiliki lebih sedikit pixel sehingga detail gambar lebih rendah.