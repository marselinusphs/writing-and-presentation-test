# WRITING AND PRESENTATION TEST WEEK 1

NAMA | MARSELINUS PUTU HARRY SETYAWAN
------------ | -------------
TRACK | BACK-END
KLP TRACK | 3

***

## JAVASCRIPT DASAR: SCOPE DAN FUNCTION
* Scope adalah konsep dalam flow data variabel.
* Global scope berarti variabel yang kita buat dapat diakses dimanapun dalam suatu file. Agar menjadi Global Scope, suatu variabel harus dideklarasikan diluar Blocks.
* Local scope berarti kita mendeklarasikan variabel didalam blocks seperti function, conditional, dan looping. Maka variabel hanya bisa diakses didalam blocks saja. Tidak bisa diakses diluar blocks.
* Function adalah sebuah blok kode dalam sebuah grup untuk menyelesaikan 1 task/1 fitur. Saat kita membutuhkan fitur tersebut nantinya, kita bisa kembali menggunakannya.
* Membuat function
> function tes(a) {  
    console.log(a)  
  }
* Memanggil function
> tes("halo")
* Dengan parameter, function dapat menerima sebuah inputan data dan menggunakannya untuk melakukan task/tugas. Saat membuat function/fitur, kita harus tahu data-data yang dibutuhkan. Misalnya saat membuat function penambahan 2 buah nilai. Data yang dibutuhkan adalah 2 buah nilai tersebut.
Pada fungsi di atas, a adalah parameter dan b adalah argumen
* Default paramaters digunakan untuk memberikan nilai awal/default pada parameter function. Default parameters bisa digunakan jika kita ingin menjaga function agar tidak error saat dipanggil tanpa argumen
* Jenis-jenis error: Reference error, Syntax error, Range error, dan type error. Untuk mengetahui jenis-jenis error yang lebih spesific dan cara penanganannya dapat mengunjungi halaman dokumentasi di https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error

## JAVASCRIPT DASAR: SCOPE DAN FUNCTION
* Tipe data pada javascript dibagi menjadi 2, yaitu primitive dan non-primitive.
* Tipe data primitif hanya dapat menyimpan satu nilai pada satu waktu dan tidak dapat diubah menggunakan cara yang sama seperti tipe data non-primitif. Tipe data Primitif akan dianggap sama jika nilainya sama. Contoh: Number, String, boolean, null
* Tipe data non-primitif dapat menyimpan lebih dari satu nilai pada satu waktu dan dapat diubah. Tipe data non-primitif akan dianggap berbeda meskipun nilainya sama dan dalam urutan yang sama. COntoh: map, array, object

## JAVASCRIPT DASAR: SCOPE DAN FUNCTION
* DOM merupakan kependekan dari Document Object Model, DOM ini yakni object model standar bagi XML dan HTML yang memiliki sifat platform independent. Saat membuka sebuah halaman web pada browser, maka file HTML dari web akan dimuat serta ditampilkan pada layar perangkat. Nah, saat proses render file HTML berlangsung, browser akan membuat DOM atau model objek dokumen yang merupakan model berorientsi objek dari struktur logicnya.
* Event listener adalah sebuah konsep untuk merespon kegiatan yang terjadi didalam suatuobjek. Event listener merupakan implementasi penyampaian message antar objek. Objek yang mendapat message akan melakukan suatu action yang telah ditentukan didalam program.
