# WRITING AND PRESENTATION TEST WEEK 1

NAMA | MARSELINUS PUTU HARRY SETYAWAN
------------ | -------------
TRACK | BACK-END
KLP TRACK | 3

***

## INTRO TO COMPUTER SCIENCE
*	Coding adalah memberi instruksi pada komputer, menggunakan bahasa yang dimengerti komputer. Algoritma adalah upaya dengan urutan operasi yang disusun secara logis dan sistematis untuk menyelesaikan suatu masalah untuk menghasilkan suatu output tertentu.
*	Contoh program sederhana yaitu program perkalian  
> Langkah 1	: Start  
> Langkah 2	: Declare variable num1, num2, and result  
> Langkah 3 	: Read values num1 and num2  
> Langkah 4 	: Kalikan num1 dan num2, simpan hasilnya ke variable result  
> Langkah 5	: Tampilkan result  
> Langkah 6	: Stop  
*	Bahasa pemrograman adalah satu set aturan sintaks dan semantik yang digunakan untuk mendefinisikan program computer, seperti Javascript, Python, Java.
*	Pada compiler, kode sumber akan dikonversi menjadi machine code sebelum program tersebut dijalankan. Sementara, interpreter mengkonversi source code menjadi machine code secara langsung ketika program dijalankan.
*	Karakteristik bahasa pemrograman:
1. Simple (Sederhana)
2. Object-oriented (berorientasi obyek)
3. Distributed (terdistribusi)
4. Robust (kuat)
5. Architecture-Neutral (tidak bergantung platform)
6. Dynamic (dinamis)
* Contoh implementasi perkalian pada Javascript
```
let var1 = 4  
let var2 = 2  
console.log(var1*var2)
```

## INTRO TO COMPUTER SCIENCE
* Web development secara umum mengacu pada tugas-tugas yang berkaitan dengan pengembangan situs web melalui intranet atau internet. Proses web development mencakup desain web, pengembangan konten web, client side atau server-side scripting dan konfigurasi keamanan jaringan serta pemilihan domain terbaik sebelumnya.
* Secara umum, pengguna akan mengakses suatu website berupa URL melalui Web Browser. Kemudian Web Browser tersebut mengirimkan permintaan HTTP request kepada Web Server melalui TCP/IP, sehingga Web Server akan memberikan Web Files yang diminta
* Tools dan bahasa pemrograman dalam pengembangan web: HTML, CSS, Javascript.

## UNIX COMMAND LINE
* PowerShell adalah shell baris perintah berbasis tugas dan bahasa skrip yang dirancang khusus untuk administrasi system
* CLI adalah mekanisme interaksi dengan sistem operasi atau perangkat lunak komputer dengan mengetikkan perintah untuk menjalankan tugas tertentu
* Cara membuka Command Line Interface/Terminal yaitu dengan membuka software Command Prompt pada Windows. Bisa juga menggunakan PowerShell.
* Sebuah filesystem mengatur bagaimana data disimpan di dalam sebuah system. Sistem operasi Windows & Unix-like menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree
* Untuk melihat current working directory dapat menggunakan perintah ‘pwd’
* Untuk melihat isi sebuah directory dapat menggunakan perintah ‘ls’
* Untuk berpindah directory dapat menggunakan perintah ‘cd nama_directory’
* Untuk melihat isi files dapat menggunakan perintah ‘head’, ‘tail’, atau ‘cat’
*	Untuk membuat file & direktori dapat menggunakan perintah ‘touch nama_file’ untuk file atau ‘mkdir nama_direktory’ untuk direktori
*	Untuk menyalin file & direktori dapat menggunakan perintah ‘cp nama_file’ atau ‘cp –R nama_direktori’
*	Untuk memindahkan atau me-rename file dan direktori dapat menggunakan perintah ‘mv nama_file’ atau ‘mv –R nama_direktori’
*	Untuk menghapus file & direktori dapat menggunakan perintah ‘rm nama_file’ atau ‘rm –R nama_direktori’

## GIT & GITHUB DASAR
*	Dengan menggunakan GIT dan Github, kita akan bisa bekerja dalam sebuat tim. Tujuan besarnya adalah kamu bisa berkolaborasi mengerjakan proyek yang sama tanpa harus repot copy paste folder aplikasi yang terupdate. Kita juga tidak perlu menunggu rekan dalam satu tim menyelesaikan suatu program dahulu untuk berkolaborasi. Kita bisa membuat file didalam projek yang sama atau membuat code di file yang sama dan menyatukannya saat sudah selesai.
*	Developer yang menggunakan Git dapat menggunakan command-line tool, yaitu pengubah kode dan dapat digabungkan menuju perangkat lokal. Sedangkan, GitHub menyediakan interface grafis berbasis cloud sebagai tempat untuk melakukan seluruh tugas.
*	Alur kerja git adalah mencatat setiap perubahan pada File (termasuk code yang kita buat) pada suatu proyek baik dikerjakan secara individu maupun tim
*	Untuk membuat Repository Git dapat menggunakan perintah ‘git init <nama repo>’ 
*	Untuk melakukan commit dapat menggunakan perintah ‘git commit –m “nama commit”’
*	Untuk mempublish aplikasi ke Github dapat menggunakan perintah ‘git push origin master’
*	Untuk melakukan cloning Github ke local, kita mengunjungi halaman repo Github yang akan dicloning, lalu klik tombol Clone berwarna hijau

## HTML
*	HTML adalah singkatan dari Hypertext Markup Language. HTML digunakan untuk menampilkan konten pada browser. Contoh konten yang dapat ditampilkan seperti Text, Image, Video, Link, dan masih banyak lainnya.
*	Ada 2 tools utama yang harus dipersiapkan untuk membuat HTML: Browser dan Code Editor
*	Saya telah mampu membuat HTML sederhana 
*	Kita bisa menjalankan HTML dengan mencari lokasi file HTML kita lalu membukanya via browser. Namun kekurangan menggunakan cara ini kita perlu refresh halaman jika ada perubahan content. Kita dapat menggunakan ekstensi dari VSC yaitu Live Server. Jika sudah selesai install “Live Server” kita bisa klik kanan pada file HTML kita dan ada pilihan open with “Live Server” maka HTML kita sudah auto reload
*	Contoh implementasi tag HTML yang popular
1. Image	: <img src=”img/daun.jpg” alt=”daun”>
2. Tabel	: <table> <tr> <td> </td></tr> </table>
*	Elemen semantik adalah elemen-elemen yang menyatakan makna atau tujuan dari elemen itu sendiri. Misalnya tag <footer>, tag ini digunakan untuk membuat elemen footer atau bagian kaki dari web.
*	Deploy adalah sebuah proses untuk menyebarkan aplikasi yang sudah kita kerjakan supaya bisa digunakan oleh orang-orang. Untuk mendeploy HTML dapat menggunakan Netlify

## CSS
*	CSS adalah bahasa yang digunakan untuk mendesain halaman website. Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.
*	Cara menggunakan CSS:
1. Inline – menuliskan perintah CSS langsung pada elemen HTML
2. Internal – menuliskan perintah CSS di bagian <head> HTML
3. Eksternal – menuliskan perintah CSS pada file yang berbeda (eksternal)
* Sintaks CSS terdiri dari tiga bagian: pemilih atau selektor (selector), sifat atau properti (property), dan nilai (value). “Selektor” biasanya adalah elemen atau tag HTML yang akan didefinisikan, “properti” adalah atribut yang akan diganti dengan “nilai” tertentu.
*	Halaman web dapat dilihat menggunakan banyak perangkat berbeda: desktop, tablet, dan ponsel. Halaman web kita akan terlihat bagus, dan mudah digunakan, apa pun perangkatnya. Halaman web tidak boleh meninggalkan informasi agar sesuai dengan perangkat yang lebih kecil, melainkan menyesuaikan kontennya agar sesuai dengan perangkat apa pun. Untuk itu diperlukan Responsive web design untuk membuat halaman web kita terlihat bagus di semua perangkat.
*	Flexbox merupakan konsep pengaturan layout yang mengatur ukuran elemen Child dari suatu Container untuk beradaptasi dengan Parent/Container-nya. Flexbox umumnya digunakan pada sebuah elemen yang tidak pasti ukurannya atau berubah-ubah(dinamis). Hal ini sangat bermanfaat untuk membuat tampilan website responsif.

## Algoritma 
*	Algoritma adalah upaya dengan urutan operasi yang disusun secara logis dan sistematis untuk menyelesaikan suatu masalah untuk menghasilkan suatu output tertentu. Sedangkan data structure adalah cara menyimpan dan mengatur data secara terstruktur pada sistem komputer atau database sehingga lebih mudah diakses.
*	Algoritma merupakan pemeran utama dari programming dalam memecahkan suatu permasalahan. Manfaat dari algoritma yaitu membantu menyederhanakan suatu program yang rumit dan juga besar. Lalu, mempermudah pembuatan program yang dapat menyelesaikan masalah tertentu. Sedangkan manfaat struktur data adalah memberikan kemudahan dalam membuat sebuah program. Struktur data dapat digunakan untuk membuat perintah dengan bahasa pemrograman dengan lebih mudah. Memudahkan dalam menggunakan konsep algoritma. Dengan memahami algoritma pada suatu program maka program akan mudah dijalankan
*	Contoh algoritma perkalian:
> Langkah 1	: Start  
> Langkah 2	: Declare variable num1, num2, and result  
> Langkah 3 	: Read values num1 and num2  
> Langkah 4 	: Kalikan num1 dan num2, simpan hasilnya ke variable result  
> Langkah 5	: Tampilkan result  
> Langkah 6	: Stop  
*	Contoh implementasi perkalian pada Javascript
```
  let var1 = 4
  let var2 = 2
  console.log(var1*var2)
```
*	Big-O Notation adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk Aljabar, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.

## JAVASCRIPT DASAR
*	Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website. Javascript juga dapat membuat website menjadi interaktif dan dinamis.
*	Javascript dapat dijalankan melalui browser pada device setiap user.
*	Ada 6 tipe data fundamental pada Javascript:
1. 	Number		: mengandung semua angka termasuk angka desimal
2. 	String		: grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya
3.  Boolean	: tipe data yang hanya mempunyai 2 buah nilai, True atau False
4. 	Null		: variable/data tidak memiliki nilai
5.	Undefined	: merepresentasikan varibel/data yang tidak memiliki nilai
6.	Object		: koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya).
*	Jenis-jenis operator:
1.	Assignment operator => untuk menyimpan sebuah nilai pada variable
2.	Arithmetic Operator => untuk operasi matematika
3.	Comparison operator => untuk membandingkan 2 buah nilai
4.	Logical Operator => untuk mengoperasikan 2 buah Boolean atau lebih
*	Conditional merupakan statement percabangan yang menggambarkan suatu kondisi. Conditional statement akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut. Yang dicek adalah apakah kondisi tersebut TRUE (benar). Jika TRUE maka code didalam kondisi tersebut dijalankan. Sedangkan looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.
