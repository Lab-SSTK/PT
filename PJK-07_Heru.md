# Post-Test PJK-07
## Asisten Praktikum: Heru Pranoto Yudo

### Soal 01
Bilbil sedang mengerjakan sebuah proyek IoT. Ia lupa beberapa hal dasar mengenai protokol komunikasi IoT, sehingga ia meminta tolong kepada teman-teman untuk membantunya. Proyek yang sedang ia kerjakan adalah proyek komunikasi data dari sebuah laptop menuju sebuah perangkat. Namun ia ingin menguji terlebih dahulu alur komunikasi datanya, sehingga ia mengganti perangkat tersebut menjadi sebuah laptop. Alur komunikasi data yang ia harapkan ditunjukkan pada gambar di bawah ini.

![Soal PT PJK-07](Blok%20diagram%20PT%20PJK-07.png)

Ketentuan sistem yang Bilbil rancang adalah sebagai berikut:
1. Data yang dikirim dari laptop 01 adalah NIM masing-masing anggota praktikum teman-teman.
2. Laptop 02 menerima data dari laptop 01 tanpa adanya perubahan data.
3. Laptop 02 menambahkan data nama lengkap dari pemilik masing-masing NIM, kemudian dipasangkan antara nama lengkap dengan pemilik NIM-nya. Setelah data dipasangkan, maka data baru tersebut dikirimkan ke broker.
4. Laptop 03 menerima data dari broker dan mengubah data tersebut menjadi bentuk json, kemudian data dikirimkan ke API dengan metode POST dan GET
5. Laptop 04 mengambil data dari API dengan metode GET.
6. Laptop 04 mengolah data pada poin 5 dengan mengurutkan pasangan nama lengkap dan NIM-nya mulai dari NIM terkecil hingga terbesar.
7. Data pada laptop 04 ditampilkan pada terminal laptop 04
8. Waktu maksimal data terkirim dari laptop 01 hingga laptop 04 adalah 2 detik. 

Bilbil meminta seluruh dokumentasi pengerjaan proyek ini lengkap dan jelas. Dokumen dokumentasi yang diminta Bilbil adalah sebagai berikut:
1. Kode program python laptop 01, laptop 02, laptop 03, dan laptop 04.
2. Kode program Arduino
3. Kode program PSoC
4. Contoh Penamaan file poin 01 hingga 03 adalah sebagai berikut:
> Kode Program_Python_Laptop 01 (Sesuaikan kembali)
1. Masing-masing folder poin 01 hingga 03 dibuat menjadi file .zip / .rar dengan format penamaan berikut ini:
> PT PJK-07_Kode Program_Keseluruhan
1. Batas waktu pengumpulan file post-test adalah sama seperti batas waktu pengumpulan laporan praktikum

Nikmati proses pembelajarannya. Salam Sehat.