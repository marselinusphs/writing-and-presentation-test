# WRITING AND PRESENTATION TEST WEEK 3

NAMA | MARSELINUS PUTU HARRY SETYAWAN
------------ | -------------
TRACK | BACK-END
KLP TRACK | 3

***

## ARRAY DAN MULTIDIMENSIONAL ARRAY
* Array merupakan sekumpulan variabel yang memiliki tipe data yang sama dan mampu menyimpan beberapa nilai dalam satu variabel. Array merupakan tipe data terstruktur dalam pemrograman, array memungkinkan untuk menyimpan data maupun referensi objek dalam jumlah banyak dan terindeks.
* Index Array dimulai dari 0
* Array dapat menyimpan tipe data String, Number, Boolean, dan lainnya
* Contoh Array
> var siswa = ["Andi", "Budi", "Chika"];
> console.log(siswa[0]); //Output: Andi
* Array memiliki 5 properti yang sering digunakan yaitu constructor, length, index, input, dan prototype.
* Array memiliki method atau biasa disebut built-in methods. Artinya Javascript sudah memudahkan kita dengan menyediakan function/method umum yang bisa kita gunakan.
* Multidimensional array adalah array yang menyimpan array lain pada setiap indeks, bukan elemen tunggal. Dengan kata lain, kita dapat mendefinisikan array multi dimensi sebagai array dari suatu array
* Contoh MD Array
> const data = [[1, 2, 3], [1, 3, 4], [4, 5, 6]];

## OBJECT
* Pada programming, object adalah sebuah tipe data pada variabel yang menyimpan properti dan fungsi (method)
* Properti adalah data lengkap dari sebuah object.
* Method adalah action dari sebuah object. Apa saja yang dapat dilakukan dari suatu object.
* Cara menginisialisasi object
> const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
* Sama seperti array, didalam object kita dapat menyimpan properti dengan tipe data apapun.
* Jika kita ingin menampilkan seluruh object properti. Kita bisa menggunakan looping. Jadi tidak perlu mengakses secara manual memanggil setiap propertinya. Perulangan menggunakan syntax for in
* Object sama seperti Array yang bisa menyimpan banyak data. Kita dapat menggunakan array of object untuk data yang lebih dari satu.
* Update/menambah properties object
> person.haircolor: "black";
* Menghapus property object
> delete person.haircolor;

## Rekursif
* Recursive adalah function yang memanggil dirinya sendiri sampai kondisi tertentu.
* Fungsi rekursif selalu memiliki kondisi yang menyatakan kapan fungsi tersebut berhenti. Kondisi ini harus dapat dibuktikan akan tercapai, karena jika tidak tercapai maka kita tidak dapat membuktikan bahwa fungsi akan berhenti, yang berarti algoritma kita tidak benar.
* Fungsi rekursif selalu memanggil dirinya sendiri sambil mengurangi atau memecahkan data masukan setiap panggilannya. Hal ini penting diingat, karena tujuan utama dari rekursif ialah memecahkan masalah dengan mengurangi masalah tersebut menjadi masalah-masalah kecil.
* Contoh fungsi rekursif
> function recurse() {  
    // function code  
    recurse();  
    // function code  
}  
  
recurse();  

## WEB STORAGE
* Cookies adalah data kecil yang dikirim dari situs web dan disimpan di komputer kita oleh web browser saat kita menjelajah. Disebut data kecil karena maksimum data yang dapat disimpan dalam cookies adalah 4096 bytes (4 KB). Biasanya data yang disimpan di cookies adalah access token pengguna saat login atau data pencarian saat melakukan pencarian pada situs web tertentu. Hal ini yang biasanya dilakukan oleh situs pencarian untuk melacak pencarian kita dan menampilkan iklan yang berhubungan dengan pencarian kita sebelumnnya.
* session storage adalah sebuah penyimpanan data yang hanya bertahan ketika browser tidak ditutup atau tab tidak ditutup, Apabila browser ditutup maka secara otomatis data yang disimpan di session storage akan hilang. Biasanya data yang disimpan disini adalah data yang dimaksudkan agar setelah browser ditutup atau tab didutup data akan hilang. 
* local storage adalah sebuah penyimpanan data dimana data ini akan terus ada tidak akan pernah bisa terhapus meskipun browser ditutup, komputer dimatikan, data ini bisa hilang apabila anda menjalankan perintah hapus dan browser dilakukan clear data atau cookie juga uninstall

## ASYNCHRONOUS
* Asynchronous mengizinkan komputer memproses task yang lain sambil menunggu proses yang masih berlangsung.
* Callback function adalah function yang kita letakan di dalam argumen/parameter pada function, dan function tersebut akan dieksekusi setelah function pertama menyelesaikan tugasnya.
* Promise adalah salah satu fitur baru di ES6, biasa digunakan untuk melakukan http request/fetch data dari API.
* Async - await adalah salah satu fitur baru dari javascript yang digunakan untuk menangani hasil dari sebuah Promise. Sedangkan await berfungsi untuk menunda sebuah kode dijalankan sampai proses asynchronous berhasil.
