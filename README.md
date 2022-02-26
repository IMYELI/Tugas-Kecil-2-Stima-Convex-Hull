# Tugas-Kecil-2-Stima-Convex-Hull

## Deskripsi Program
Program menerima dataset yang diimport dari sklearn lalu memprosesnya sesuai target.
Proses dilakukan dengan memanggil fungsi myConvexHull.
myConvexHull akan menerima array data yang sudah disort(berdasarkan kolom 0 dan 1, jika kolom 0 sama maka di sort berdasarkan kolom 1)
Array data kemudian diambil elemen pertama dan akhirnya untuk menjadi garis pertama yang akan membagi 2 data
Kemudian myConvexHull akan memanggil fungsi rekursi nextHull yang akan menjadi titik dengan jarak terjauh dari garis pertama lalu
membagi 2 data dan data yang berada di luar garis yang terbentuk akan diproses dengan nextHull

## Requirement
1. Python 3.8.8
2. Modul Pandas
3. Modul SKLearn
4. Modul Numpy
5. Modul Matplotlib

## Cara menjalankan program
Program bisa dirun menggunakan jupyter notebook atau VSCode yang sudah dipasang ekstensi untuk file ipynb.

## Cara menggunakan program
1. Line 6 di program dapat diganti dengan dataset yang diinginkan
2. Line 15 di program dapat digunakan untuk mengganti judul graf
3. Line 16 dan 17 di program dapat digunakan untuk menamai sumbu x dan sumbu y di graf
4. Line 20 di program dapat digunakan untuk mengatur kolom dan baris yang digunakan

## Author
Andreas Indra Kurniawan 13520091