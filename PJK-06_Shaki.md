# _Post-Test_ PJK-06
Asisten Praktikum: Shaki S. Putra, S.T., M.Eng.

_Deadline_: Jumat, 10 November 2023 18:00 WIB
#
Setelah melaksanakan praktikum PJK-06, demi memperdalam pemahaman Anda terkait I2C dan SPI, Anda diminta untuk merancang bangun sebuah sistem komunikasi yang terdiri dari sebuah Laptop, tiga buah Arduino, dan tiga buah PSoC5. Sistem komunikasi ini bertujuan untuk mengirimkan data dari sebuah PSoC5 dan membaginya menjadi dua jalur komunikasi yang masing-masing terdiri dari sebuah Arduino dan PSoC5 untuk kemudian disatukan kembali pada sebuah Arduino. Sistem bekerja dengan algoritma sebagai berikut:

1. PSoC5(1) akan berperan sebagai SPI _Master_ dan mengirimkan dua buah data berupa karakter "J" dan "K" ke dua buah Arduino yang berpersan sebagai SPI _Slave_ secara terpisah.
2. Data pada _Slave_: Arduino(1) = "J", Arduino(2) = "K"
3. Masing-masing Arduino(1) dan Arduino(2) lantas juga akan berperan menjadi I2C _Master_ dan mengirimkan data ke PSoC5(2) dan PSoC5(3) yang berperan sebagai I2C _Slave_ dengan hubungan: Arduino(1)-PSoC5(2) dan Arduino(2)-PSoC5(3)  
4. Arduino(3) kemudian akan berperan menjadi I2C _Master_ dan mengakses data dari PSoC5(2) dan PSoC5(3)
5. Data yang diterima oleh Arduino(3) dari kedua PSoC5 tersebut kemudian digabungkan dan ditampilkan pada _serial monitor_ di Arduino IDE

Selamat bermain, jangan lupa dinikmati prosesnya :)
#