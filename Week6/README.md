# WRITING AND PRESENTATION TEST WEEK 6 BACKEND

NAMA | MARSELINUS PUTU HARRY SETYAWAN
------------ | -------------
TRACK | BACK-END
KLP TRACK | 3

***

## WEB SERVER AND RESTFUL API
*	Server yang dapat menjalankan program dan dapat diakses melalui internet atau intranet. Web service berjalan di dalam web server sehingga ia dapat diakses melalui internet. Melalui web service inilah aplikasi Front-End (client) dan Back-End dapat bertransaksi.  
*	API RESTful adalah antarmuka yang digunakan oleh dua sistem komputer untuk bertukar informasi secara aman melalui internet. Sebagian besar aplikasi bisnis harus berkomunikasi dengan aplikasi internal dan pihak ketiga lainnya untuk melakukan berbagai tugas  

## INTRO NODE JS
* Node.js adalah runtime environment untuk JavaScript yang bersifat open-source dan cross-platform. Dengan Node.js kita dapat menjalankan kode JavaScript di mana pun, tidak hanya terbatas pada lingkungan browser.  
* Karakteristik Node JS ialah 
> Single Thread: Javascript menggunakan konsep single thread, yang berarti hanya memiliki satu tumpukan panggilan yang digunakan untuk menjalankan program.
> Even Loop: event loop akan memeriksa terus menerus, ketika antrian kosong di call stack maka akan menambah antrian baru dari event queue sampai semua perintah selesai di eksekusi.  
> Server side scripting: dengan menggunakan NodeJS kita dapat menjalankan javascript di server side menggunakan terminal command line menggunakan perintah “node”. 
* Build In Module Node JS: Console, Process, OS, Util, Event, Error, Buffer, FS, timers
* Node.js memiliki built-in modul yang disebut HTTP, built-in modul ini memungkinkan Node JS mentransfer data melalui Hyper Text Transfer Protocol (HTTP). Modul HTTP dapat membuat server HTTP yang mendengarkan port server dan memberikan respons kembali ke klien.

## EXPRESS JS
*	Back end app adalah aplikasi yang berjalan di server-side yang bekerja untuk memberikan informasi berupa data sesuai request dari client / browser / front end app. Umumnya server-side app membuat REST API  
*	Routes adalah sebuah end point yang diapat kita akses menggunakan URL di website. Didalam routes kita perlu menentukan method API, alamat dan response apa saja yang akan dikeluarkan
* Middleware function adalah sebuah fungsi yang memiliki akses ke object request (req), object response (res), dan sebuah fungsi next didalam request-response cycle.  

## DESIGN DATABASE
*	Pada Sistem Perkuliahan, yang menjadi entitas adalah dosen dan mahasiswa, matkul
*	Attributnya yaitu: Pada Dosen: NIDN, Nama, TTL, Alamat. Pada Mahasiswa: NIM, prodi, fakultas, nama, dll
*	Relasinya yaitu antara dosen dan matkul adalah one to many. antara mahasiswa dan matkul adalah many to many
