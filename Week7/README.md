# WRITING AND PRESENTATION TEST WEEK 7 BACKEND

NAMA | MARSELINUS PUTU HARRY SETYAWAN
------------ | -------------
TRACK | BACK-END
KLP TRACK | 18

***

## MYSQL BASIC
*	Database atau basis data adalah kumpulan informadi yang disimpan di dalam komputer secara sistematik sehingga dapat diperiksa menggunakan suatu program komputer untuk memperoleh informasi dari basis data tersebut.  
*	ADatabase relasional adalah kumpulan item data dengan hubungan yang telah ditentukan sebelumnya. Berbagai item ini disusun menjadi satu set tabel dengan kolom dan baris. Tabel digunakan untuk menyimpan informasi tentang objek yang akan direpresentasikan dalam database  
*	Tipe Data pada Javascript: Number, String, Boolean, Date, Blob, Enum
*	Contoh Query Sederhana untuk menampilkan seluruh data dari tabel books: SELECT * FROM books

## MYSQL LANJUTAN
* one to one: setiap baris data pada tabel pertama dihubungkan hanya ke satu baris data pada tabel ke dua. Hubungan antara file pertama dan file kedua adalah satu berbanding satu.  
* one to many: setiap baris data dari tabel pertama dapat dihubungkan ke satu baris atau lebih data pada tabel ke dua. Hubungan antara file pertama dan file kedua adalah satu berbanding banyak atau banyak berbanding satu
* many to many: Satu baris atau lebih data pada tabel pertama bisa dihubugkan ke satu atau lebih baris data pada tabel ke dua. Artinya ada banyak baris di tabel satu dan tabel dua yang saling berhubungan satu sama lain. Hubunga tabel pertama dan tabel kedua adalah banyak berbanding banyak  
* Fungsi agregasi adalah fungsi menghitung jumlah nilai numerik dalam sebuah kolom. Menghitung jumlah nilai dalam kolom yang tidak kosong. Mengembalikan nilai numerik terbesar dalam sebuah kolom. Mengembalikan nilai terbesar dari serangkaian ekspresi yang dievaluasi ke atas tabel.
* COntoh: Select count(*) From books

## AUTHENTICATION & AUTHORIZATION
* Authentication adalah proses dimana seorang user (melalui berbagai macam akses fisik berupa komputer dll) mendapatkan hak akses kepada suatu entity. Contohnya pada saat login. Jenis-jenis autentication yaitu single auth dan multi auth.
* Authorization adalah proses penentuan apakah user tersebut diizinkan / ditolak untuk melakukan satu atau beberapa action akses terhadap resources tertentu dalam sistem. Contohnya yaitu role admin dan user.
* Enkripsi adalah proses teknis yang mengonversikan informasi menjadi kode rahasia, sehingga mengaburkan data yang Anda kirim, terima, atau simpan. Tujuan dari proses enkripsi adalah untuk memberikan proteksi pada informasi terkait. Dengan memberikan enkripsi pada informasi atau pesan, maka potensi kebocoran pesan dapat diminimalisir.

## SEQUELIZE
* Sequelize adalah Node.js promise-based ORM untuk MySQL, PostgreSQL, SQLite, MSSQL dan database SQL lainnya. Sequelize berfungsi untuk bekerja dengan database dan relasi-relasi di dalamnya
