# _Post-Test_ PED-07
Asisten Praktikum: Shaki S. Putra, S.T., M.Eng.

_Deadline_: Selasa, 14 November 2023 20:00 WIB
#
Setelah melaksanakan praktikum PED-07, demi memperdalam pemahaman Anda terkait penerapan logika dan implementasi dari setiap blok yang Anda gunakan pada praktikum kali ini, Anda diminta untuk merancang bangun sebuah sistem keamanan dengan rata-rata IPK kelompok Anda (hingga dua angka di belakang koma, contohnya 3.25 = 325) sebagai sandinya. Sistem bekerja dengan algoritma sebagai berikut:

1. Terdapat tiga buah blok _Basic Counter_, tiga buah blok _LUT_, dan tiga buah _seven segment_
2. Masukan pada sistem hanya berupa sebuah _push button_, pastikan Anda menggunakan blok _debouncer_ dengan konfigurasi yang sesuai 
3. Saat _push button_ ditekan, _counter_ pertama akan mulai mencacah dan akan berhenti mencacah saat digit pertama dari sandi sudah muncul pada _seven segment_ pertama dan _counter_ kedua akan mulai mencacah
4. _Counter_ kedua akan berhenti mencacah ketika digit kedua dari sandi telah muncul pada _seven segment_ kedua dan _counter_ ketiga akan mulai mencacah
5. _Counter_ ketiga akan berhenti mencacah ketika digit ketiga dari sandi telah muncul pada _seven segment_ ketiga
6. Saat ketiga _seven segment_ telah menampilkan sandi, sebuah LED akan menyala yang menandakan bahwa sandi benar
7. Ketika _push button_ ditekan kembali setelah kondisi LED menyala, maka sistem akan _reset_ dan setiap _counter_ akan kembali ke kondisi cacah 0
8. Dalam setiap proses pencacahan, setiap _counter_ akan bekerja secara sekuensial / seri, sehingga tidak akan ada kondisi dua atau lebih _counter_ yang bekerja bersamaan
9. Anda diperkenankan untuk menambahkan rangkaian kombinasional maupun _flip-flop_ jika dirasa dapat mempermudah penyelesaian _post test_ kali ini

Selamat bermain, jangan lupa dinikmati prosesnya :)
#