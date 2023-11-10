# _Post-Test_ PJK-07
Asisten Praktikum: Shaki S. Putra, S.T., M.Eng.

_Deadline_: Jumat, 17 November 2023 18:00 WIB
#
Setelah melaksanakan praktikum PJK-07, demi memperdalam pemahaman Anda terkait HTTP, WS dan MQTT, Anda diminta untuk merancang bangun sebuah sistem jaringan komunikasi. Sistem ini bertujuan untuk mengirimkan data posisi terkini dari pengendara yang bergerak dari sebuah lokasi keberangkatan menuju sebuah lokasi tujuan. Sistem bekerja dengan algoritma sebagai berikut:

1. Pengendara akan memberikan titik koordinat dari lokasi keberangkatan dan lokasi tujuan melalui sebuah API yang menerima masukan berupa koordinat (lintang dan bujur) dari titik-titik tersebut dan akan memberikan sebuah id untuk setiap data baru yang masuk, _server_ akan memberikan _response_ berupa data yang telah dimasukkan tadi dan id dari data tersebut
2. Server lantas menyimpan data tersebut pada sebuah berkas dengan ekstensi .txt
3. Ketika pengendara mulai bergerak, Ia akan mengirimkan koordinat terkini melalui MQTT setiap 30 detik dengan topik "otw/id data"
4. Anda tidak diperkenankan untuk memasukkan data koordinat pengendara tersebut secara manual maupun menggunakan perangkat lunak yang berfungsi sebagai _dashboard_ MQTT
5. Koordinat yang dikirimkan melalui MQTT tadi lantas akan diolah untuk dihitung jarak posisi pengendara terhadap lokasi tujuan (dalam meter) berdasarkan data yang tersimpan pada berkas dengan ekstensi .txt pada poin (2)
6. Data hasil pengolahan tersebut kemudian akan dikirimkan melalui WS dan akan ditampilkan pada terminal
7. Saat pengendara telah sampai di lokasi tujuan, sistem akan memunculkan informasi "Pengendara telah sampai di tujuan" pada terminal
8. _Log history_ perjalanan akan tersimpan pada sebuah berkas dengan ekstensi .txt 

Selamat bermain, jangan lupa bahagia dan nikmati prosesnya :)
#