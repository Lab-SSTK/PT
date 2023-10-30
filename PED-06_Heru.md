# Post Test PED-06
## Asisten Praktikum: Heru Pranoto Yudo

### Soal 01
Billy Pandjaitan yang telah menyelesaikan studi S1 TF UGM dan juga merupakan sobatnya Al-Payed. Karena saat ini ia sedang banyak waktu luang maka ia merancang soal Post-Test PED-06 untuk teman-teman. Ia merancang sebuah rangkaian running LED untuk diaplikasikan pada sebuah lampu sein mobil mewah yang dijual di Indonesia. Ia menentukan beberapa ketentuan sebagai berikut:

1. Rangkaian dibuat di PSoC Creator dan diuji coba pada PSoC 5LP
2. Lampu sein direpresentasikan dengan 8 buah LED
3. Rangkaian **hanya** terdiri dari blok komponen flip-flop, gerbang logika, multiplexer, demultiplexer, dan pin digital input dan ouput.
4. Masukan berupa saklar
5. Saklar berjumlah 3 buah.
6. Hanya 1 saklar yang menyala secara bersamaan
7. Ketika saklar 1 ditekan maka LED akan menyala secara bergantian dari kiri ke kanan
8. Ketika saklar 2 ditekan maka LED akan menyala secara bergantian dari kanan ke kiri
9. Ketika saklar 3 ditekan maka LED akan menyala secara bergantian dari tengah ke kiri dan dari tengah ke kanan.
10. Jumlah masing-masing blok komponen yang digunakan dibebaskan kepada perancang.
11. Frekuensi clock yang digunakan adalah antara 5 sampai 10 Hz.

<div style="page-break-after: always"></div>

### Soal 02
Kembali lagi dengan Al-Payed, ia sekarang membuat sebuah rangkaian lampu lalu lintas di sebuah simpang 4. Sayangnya, ia lupa beberapa materi elektronika digital yang telah ia pelajari selama belajar S1 TF UGM. Ia meminta bantuan teman-teman selaku praktikan praktikum elektronika digital 2023. Ketentuan yang ia inginkan untuk merancang bangun sistem tersebut adalah sebagai berikut:

1. Rangkaian dibuat di PSoC Creator dan dicoba menggunakan PSoC 5LP
2. Rangkaian hanya terdiri dari blok komponen flip-flop, gerbang logika, multiplexer, demultiplexer, pin digital input output, dan clock.
3. Jumlah masing-masing blok komponen yang digunakan dibebaskan kepada teman-teman
4. Ketika waktu ke-0 atau *initial condition*-nya adalah semua lampu di persimpangan berwarna merah.
5. Ketika waktu ke-1 maka lampu merah dan kuning sisi utara persimpangan akan menyala.
6. Ketika waktu ke-2 maka lampu hijau sisi utara persimpangan akan menyala.
7. Ketika waktu ke-3 maka lampu hijau dan kuning sisi utara persimpangan akan menyala.
8. Urutan poin 4 hingga 7 akan terus berlanjut secara berurutan dengan arah putaran berlawanan arah jarum jam hingga satu siklus putaran APILL selesai. 