# 1. Untuk menyelesaikan masalah menghitung total harga pembelian 3 barang, kita dapat mengikuti langkah-langkah algoritma berikut:

Inisialisasi: Siapkan variabel untuk menyimpan harga dari masing-masing barang.

Input Harga: Minta pengguna untuk memasukkan harga dari 3 barang.

Hitung Total: Jumlahkan ketiga harga untuk mendapatkan total pembayaran.

Tampilkan Hasil: Tampilkan total harga kepada pengguna.

# 2. Manfaat Penggunaan Fungsi
Penggunaan fungsi dalam pemrograman memiliki beberapa manfaat, antara lain:

Modularitas: Fungsi memungkinkan kita untuk membagi program menjadi bagian-bagian kecil yang lebih mudah dikelola dan dipahami.

Reusabilitas: Fungsi yang telah dibuat dapat digunakan kembali di bagian lain dari program atau di program lain tanpa perlu menulis ulang kode.

Abstraksi: Fungsi menyembunyikan detail implementasi dan hanya menampilkan antarmuka yang diperlukan, sehingga pengguna fungsi tidak perlu memahami cara kerjanya.

Pengujian dan Debugging: Fungsi dapat diuji secara terpisah, sehingga memudahkan dalam menemukan dan memperbaiki kesalahan.

Cara Kerja Rekursi dalam Menghitung Faktorial:
Rekursi adalah teknik di mana sebuah fungsi memanggil dirinya sendiri untuk menyelesaikan sub-masalah. Dalam konteks menghitung faktorial, faktorial dari suatu bilangan $n$ (dilambangkan dengan $n!$)
Dengan menggunakan definisi ini, kita dapat membuat fungsi rekursif yang menghitung faktorial dengan memanggil dirinya sendiri untuk menghitung faktorial dari bilangan yang lebih kecil hingga mencapai kasus dasar.

# 3. truktur kontrol percabangan digunakan untuk mengambil keputusan berdasarkan kondisi tertentu
Dalam kasus pemberian diskon pada sistem e-commerce, percabangan digunakan untuk memeriksa apakah total belanja pelanggan melebihi Rp500.000. Jika kondisi tersebut terpenuhi, maka diskon 10% diberikan, jika tidak maka tidak ada diskon.

Secara logika:
Jika total belanja > 500.000, total bayar = total belanja - (diskon 10% dari total belanja)
Jika tidak, total bayar = total belanja
