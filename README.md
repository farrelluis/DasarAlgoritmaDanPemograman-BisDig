# 1. Untuk menyelesaikan masalah menghitung total harga pembelian 3 barang, kita dapat mengikuti langkah-langkah algoritma berikut:

Inisialisasi: Siapkan variabel untuk menyimpan harga dari masing-masing barang.

Input Harga: Minta pengguna untuk memasukkan harga dari 3 barang.

Hitung Total: Jumlahkan ketiga harga untuk mendapatkan total pembayaran.

Tampilkan Hasil: Tampilkan total harga kepada pengguna.

Penjelasan Program:

Program dimulai dengan menginisialisasi variabel untuk menyimpan harga barang.

Kemudian, program meminta pengguna untuk memasukkan harga masing-masing barang menggunakan fungsi 'input()', dan mengonversi input tersebut menjadi tipe data 'float' untuk memungkinkan perhitungan desimal.

Setelah mendapatkan harga dari ketiga barang, program menjumlahkan harga-harga tersebut untuk mendapatkan total pembayaran.

Akhirnya, program menampilkan total pembayaran kepada pengguna menggunakan fungsi 'print()'.

# 2. Manfaat Penggunaan Fungsi
Penggunaan fungsi dalam pemrograman memiliki beberapa manfaat, antara lain:

Modularitas: Fungsi memungkinkan kita untuk membagi program menjadi bagian-bagian kecil yang lebih mudah dikelola dan dipahami.

Reusabilitas: Fungsi yang telah dibuat dapat digunakan kembali di bagian lain dari program atau di program lain tanpa perlu menulis ulang kode.

Abstraksi: Fungsi menyembunyikan detail implementasi dan hanya menampilkan antarmuka yang diperlukan, sehingga pengguna fungsi tidak perlu memahami cara kerjanya.

Pengujian dan Debugging: Fungsi dapat diuji secara terpisah, sehingga memudahkan dalam menemukan dan memperbaiki kesalahan.

Cara Kerja Rekursi dalam Menghitung Faktorial:
Rekursi adalah teknik di mana sebuah fungsi memanggil dirinya sendiri untuk menyelesaikan sub-masalah. Dalam konteks menghitung faktorial, faktorial dari suatu bilangan $n$ (dilambangkan dengan $n!$)
Dengan menggunakan definisi ini, kita dapat membuat fungsi rekursif yang menghitung faktorial dengan memanggil dirinya sendiri untuk menghitung faktorial dari bilangan yang lebih kecil hingga mencapai kasus dasar.

Penjelasan Program:

Definisi Fungsi: Fungsi 'faktorial(n)' didefinisikan untuk menghitung faktorial dari bilangan bulat non-negatif n.

Kasus Dasar: Jika n sama dengan 0, fungsi mengembalikan 1, sesuai dengan definisi faktorial.

Rekursi: Jika n lebih besar dari 0, fungsi memanggil dirinya sendiri dengan argumen n-1 dan mengalikan hasilnya dengan n.

Input Pengguna: Program meminta pengguna untuk memasukkan angka yang ingin dihitung faktorialnya.

Menampilkan Hasil: Hasil faktorial yang dihitung oleh fungsi ditampilkan kepada pengguna.

# 3. truktur kontrol percabangan digunakan untuk mengambil keputusan berdasarkan kondisi tertentu
Dalam kasus pemberian diskon pada sistem e-commerce, percabangan digunakan untuk memeriksa apakah total belanja pelanggan melebihi Rp500.000. Jika kondisi tersebut terpenuhi, maka diskon 10% diberikan, jika tidak maka tidak ada diskon.

Secara logika:
Jika total belanja > 500.000, total bayar = total belanja - (diskon 10% dari total belanja)
Jika tidak, total bayar = total belanja

Penjelasan Program:

Program akan meminta pengguna memasukkan nilai total belanja.

Struktur 'if' memeriksa jika total belanja lebih dari Rp500.000.

Jika benar, maka diskon 10% dihitung dan dikurangkan dari total belanja.

Jika salah, diskon nol.

Program menampilkan total belanja sebelum diskon, nilai diskon, dan total yang harus dibayar setelah diskon.

# 4. Peran Tipe Data dan Operator
1. Tipe Data: Tipe data digunakan untuk menentukan jenis nilai yang akan disimpan dalam variabel. Dalam konteks ini, kita akan menggunakan:

'float' untuk menyimpan nilai mata pelajaran, karena nilai dapat berupa angka desimal.

'str' untuk menyimpan status kelulusan (lulus atau tidak lulus) yang akan ditampilkan sebagai teks.

2. Operator:
   
Operator aritmatika (+, /) digunakan untuk melakukan perhitungan, seperti menjumlahkan nilai dan menghitung rata-rata.

Operator perbandingan (>=) digunakan untuk membandingkan rata-rata nilai dengan batas kelulusan (75) untuk menentukan status kelulusan siswa.

Penjelasan Program:

Input Nilai: Program meminta pengguna untuk memasukkan nilai dari 3 mata pelajaran. Nilai tersebut dikonversi menjadi tipe data 'float' untuk memungkinkan perhitungan desimal.

Menghitung Rata-rata: Rata-rata dihitung dengan menjumlahkan ketiga nilai dan membaginya dengan 3.

Menentukan Status Kelulusan: Menggunakan struktur 'if', program memeriksa apakah rata-rata nilai lebih besar atau sama dengan 75. Jika ya, status kelulusan diatur menjadi "Lulus", jika tidak, diatur menjadi "Tidak Lulus".

Menampilkan Hasil: Program menampilkan rata-rata nilai dan status kelulusan kepada pengguna.

# 5. Penjelasan Penggunaan Perulangan dan Array:
Array (List di Python) digunakan untuk menyimpan nilai dari 5 siswa. Dengan menyimpan nilai-nilai ini dalam sebuah list, kita bisa mengakses, mengelola, dan melakukan operasi seperti menemukan nilai tertinggi dengan mudah.

Perulangan digunakan untuk melakukan input nilai secara berulang sebanyak 5 kali, yaitu untuk masing-masing siswa. Ini menghindari penulisan kode input secara manual berulang kali dan membuat kode lebih ringkas dan mudah dikelola.
Setelah data nilai tersimpan dalam list, kita juga bisa menggunakan perulangan untuk menemukan nilai tertinggi dan indeks siswa yang memiliki nilai tersebut.

Penjelasan Program:

Kita membuat list kosong 'nilai_siswa' untuk menyimpan nilai.

Perulangan 'for' sebanyak 5 kali dijalankan untuk menerima input nilai 5 siswa dan memasukkan nilai tersebut ke dalam list.

Setelah itu, kita mencari nilai tertinggi dengan membandingkan setiap elemen list menggunakan perulangan.

Indeks siswa dengan nilai tertinggi dicatat.

Terakhir, program menampilkan nilai tertinggi beserta nomor siswa yang memperoleh nilai tersebut.
