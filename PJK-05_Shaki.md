# _Post-Test_ PJK-05
Asisten Praktikum: Shaki S. Putra, S.T., M.Eng.

_Deadline_: Rabu, 1 November 2023 18:00 WIB
#
Setelah melaksanakan praktikum PJK-05, demi memperdalam pemahaman Anda terkait UART dan MODBUS, Anda diminta untuk merancang bangun sebuah sistem komunikasi yang terdiri dari dua buah laptop, dua buah Arduino, dan sebuah PSoC5. Sistem komunikasi ini bertujuan untuk mengenkripsi karakter yang dikirimkan oleh Laptop1 dan menampilkannya pada Laptop2. Sistem bekerja dengan algoritma sebagai berikut:

1. Laptop1 menerima masukan dari _user_ berupa satu buah karakter
2. Karakter yang diterima dari _user_ dienkripsi menjadi 8 digit bilangan biner dari kode ASCII karakter tersebut
3. Hasil enkripsi pada poin 2 kemudian dikirimkan ke Arduino1 yang berperan sebagai _slave_ melalui protokol MODBUS dengan panjang kabel 2 meter
4. Hasil enkripsi yang berupa 8 digit angka tersebut masing-masing akan dituliskan oleh Laptop1 sebagai nilai dari 8 register awal yang terdapat pada _slave_
5. Arduino1 kemudian akan menyalakan 8 buah LED yang merepresentasikan data biner tersebut berurutan berdasarkan urutan 8 register awal dari _slave_
6. Data tersebut kemudian dikirimkan ke PSoC5 melalui UART
7. PSoC5 kemudian mengirimkan data tersebut ke Arduino2 melalui UART
8. Arduino2 akan berperan sebagai MODBUS _slave_ untuk Laptop2 dengan kabel sepanjang 1 meter
9. Data yang diterima oleh Arduino2 dari PSoC5 tersebut akan digunakan sebagai nilai dari 8 register terakhir pada _slave_
10. Laptop2 akan membaca 8 register terakhir dari _slave_ dan kemudian akan mengonversi 8 digit angka tersebut kembali menjadi karakter
11. Laptop2 kemudian akan menampilkan karakter hasil konversi tersebut pada terminal (Anda dapat menggunakan terminal pada VS Code, _Command Prompt_, atau _Powershell_).

Selamat bermain, jangan lupa bahagia :)
#