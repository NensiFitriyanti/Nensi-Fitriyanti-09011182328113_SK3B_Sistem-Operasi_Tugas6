# Nensi-Fitriyanti-09011182328113_SK3B_Sistem-Operasi_Tugas6

## Nama : Nensi Fitriyanti
## Kelas : SK3B
## NIM : 09011182328113

Cara Memasang dan Mengonfigurasi SSH di Ubuntu 22.04

Langkah 1: Persiapan Ubuntu

Pertama, pastikan semua paket apt diperbarui ke versi terbaru. Gunakan perintah berikut untuk melakukan pembaruan:

![Screenshot from 2024-10-02 09-03-12](https://github.com/user-attachments/assets/0e06f01b-58e7-42cf-8e54-a62c7d2927d9)


Langkah 2 Instal SSH Di UBUNTU;
Jika OpenSSH belum terpasang, maka perlu diinstal secara manual. Jalankan perintah berikut untuk memulai proses instalasi:

![Screenshot from 2024-10-02 09-10-26](https://github.com/user-attachments/assets/32efa22f-7621-495e-bac0-30ecd7249e38)

Proses instalasi akan berjalan, dan pastikan untuk menyetujui semua permintaan konfirmasi dari sistem dengan memilih "Ya". Setelah instalasi selesai, lanjut ke langkah berikutnya untuk mengaktifkan layanan SSH.


Langkah 3 Jalankan SSH;

Setelah instalasi selesai, aktifkan layanan SSH yang baru terpasang dengan menjalankan perintah berikut:

![Screenshot from 2024-10-02 09-12-47](https://github.com/user-attachments/assets/7888068d-8885-4580-80fc-5e295023045f)

Setelah itu, periksa apakah layanan SSH sudah aktif dan berjalan dengan perintah ini:

![Screenshot from 2024-10-02 09-14-26](https://github.com/user-attachments/assets/989de73a-3106-4da6-92d5-48a082127d46)

Jika output menampilkan "Aktif: aktif (berjalan)", artinya layanan SSH sudah berhasil dijalankan. Jika sewaktu-waktu perlu menonaktifkannya, gunakan perintah berikut:

![Screenshot from 2024-10-02 09-16-20](https://github.com/user-attachments/assets/27a2b47d-8829-4e8e-98a0-ab1257e6bf4a)


Langkah 4 Konfigurasikan firewall;
Sebelum mencoba koneksi ke server melalui SSH, pastikan firewall sudah dikonfigurasi dengan benar. Jika UFW sudah terpasang, gunakan perintah berikut untuk memeriksa:

![Screenshot from 2024-10-02 09-17-52](https://github.com/user-attachments/assets/dcfd5374-c61b-4bd3-ab04-0e241d278853)

Jika output menunjukkan bahwa lalu lintas SSH diizinkan, berarti konfigurasi sudah benar. Namun, jika belum, perintah berikut bisa digunakan untuk membuka akses SSH:

![Screenshot from 2024-10-02 09-19-25](https://github.com/user-attachments/assets/33461416-616d-4ae2-80df-5242a22319c7)


Langkah 5 Koneksi ke server;
Setelah semua langkah sebelumnya selesai, kini bisa mencoba masuk ke server menggunakan SSH. Diperlukan alamat IP atau nama domain server serta username yang ada di server tersebut. Gunakan perintah ini untuk menghubungkan:

![Screenshot from 2024-09-27 16-45-07](https://github.com/user-attachments/assets/d4444fde-d215-492c-89ed-5e568c10cb34)

Pastikan SSH sudah terpasang dan dikonfigurasi baik di server jarak jauh maupun di komputer yang digunakan untuk memastikan koneksi berjalan dengan baik.
