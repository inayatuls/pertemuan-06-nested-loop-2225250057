# Pertemuan 06 Nested Loop Python

Nama: Inayatul Sholihah
NIM: 2225250057
Kelas: 3A

## Tujuan

Menggunakan nested loop, pola, akumulasi, dan pencacahan.

## Cara Menjalankan

```bash
python3 tugas/tabel_perkalian_dan_statistik.py
```

## Algoritma Tugas 3

- Loop luar digunakan untuk mengatur baris tabel perkalian.
- Loop dalam digunakan untuk mengatur kolom dan menghitung hasil perkalian.
- Akumulator digunakan untuk menghitung jumlah setiap baris dan total seluruh hasil perkalian.
- Counter digunakan untuk menghitung banyak hasil perkalian yang bernilai genap.

## Hasil Pengujian

### Test Case 1

**Input:**
```text
n: 1
```

**Hasil yang diharapkan:**
```text
   1 | jumlah baris = 1
Total seluruh hasil = 1
Banyak hasil genap = 0
```

**Keluaran aktual:**
```text
   1 | jumlah baris = 1
Total seluruh hasil = 1
Banyak hasil genap = 0
```

**Status:** Berhasil

### Test Case 2

**Input:**
```text
n: 2
```

**Hasil yang diharapkan:**
```text
   1   2 | jumlah baris = 3
   2   4 | jumlah baris = 6
Total seluruh hasil = 9
Banyak hasil genap = 3
```

**Keluaran aktual:**
```text
   1   2 | jumlah baris = 3
   2   4 | jumlah baris = 6
Total seluruh hasil = 9
Banyak hasil genap = 3
```

**Status:** Berhasil

### Test Case 3

**Input:**
```text
n: 3
```

**Hasil yang diharapkan:**
```text
   1   2   3 | jumlah baris = 6
   2   4   6 | jumlah baris = 12
   3   6   9 | jumlah baris = 18
Total seluruh hasil = 36
Banyak hasil genap = 5
```

**Keluaran aktual:**
```text
   1   2   3 | jumlah baris = 6
   2   4   6 | jumlah baris = 12
   3   6   9 | jumlah baris = 18
Total seluruh hasil = 36
Banyak hasil genap = 5
```

**Status:** Berhasil

## Analisis Efisiensi

Untuk input n, loop luar berjalan sebanyak n kali. Pada setiap iterasi loop luar, loop dalam berjalan sebanyak n kali. Jadi, badan loop dalam berjalan sebanyak n × n atau n² kali.

## Refleksi

Salah satu kesalahan nested loop yang dapat terjadi adalah kesalahan indentasi. Kesalahan tersebut diperbaiki dengan memastikan setiap perintah berada pada tingkat indentasi yang sesuai dengan loop luar dan loop dalam.

## Kuis Formatif

### 1. Jika loop luar berjalan 4 kali dan loop dalam 6 kali, berapa total iterasi badan loop dalam?

**Jawaban:** 24 iterasi.

### 2. Kapan loop dalam kembali ke nilai awal?

**Jawaban:** Ketika loop luar masuk ke iterasi berikutnya.

### 3. Apa fungsi `print()` setelah loop dalam pada pola simbol?

**Jawaban:** Untuk membuat baris baru setelah loop dalam selesai.

### 4. Di mana `total_baris` harus diinisialisasi jika jumlah dihitung untuk setiap baris?

**Jawaban:** Di dalam loop luar, sebelum loop dalam.

### 5. Di mana `total_semua` harus diinisialisasi jika jumlah mencakup seluruh pasangan?

**Jawaban:** Sebelum loop luar.

### 6. Apa perbedaan counter dengan accumulator?

**Jawaban:** Counter digunakan untuk menghitung banyak kejadian, sedangkan accumulator digunakan untuk menjumlahkan nilai.

### 7. Jika `i` dan `j` dari 1 sampai 3, berapa pasangan yang diperiksa?

**Jawaban:** 9 pasangan.

### 8. Bagaimana `if` dapat digabung dengan nested loop untuk pencacahan?

**Jawaban:** `if` digunakan untuk memeriksa kondisi pada setiap pasangan, kemudian counter bertambah jika kondisi terpenuhi.

### 9. Apa arti working tree clean pada `git status`?

**Jawaban:** Tidak ada perubahan yang belum di-commit.

### 10. Perintah apa yang mengirim commit lokal terbaru ke GitHub?

**Jawaban:**
```bash
git push
```