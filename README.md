## Deskripsi
Selamat datang di Wonderland! Program ini adalah sebuah program manajemen sistem yang  penjualan tiket sederhana yang dibuat menggunakan bahasa pemrograman Java. Program ini dirancang untuk memudahkan proses penjualan tiket dan pengelolaan data tiket.

## Menu Utama
Saat program dijalankan akan menampilkan menu utama yang terdiri dari 3 pilihan yaitu:

![Menu Utama](https://github.com/user-attachments/assets/0b9b1c41-dd43-4afa-9f3c-1df72dfaccf2)

Berikut adalah penjelasan hasil output dari tiap menu pada program Wonderland:

## Menu Admin
Setelah pengguna memilih mode Admin dari menu utama dengan memasukkan angka 1, maka program akan menampilkan Menu Admin yang dapat digunakan oleh administrator untuk mengelola sistem penjualan tiket. Menu ini berisi beberapa pilihan yang dapat digunakan oleh administrator untuk melakukan tugas-tugas, berikut tampilan dan penjelasan dari masing-masing pilihan di menu admin:
![Menu Admin](https://github.com/user-attachments/assets/c8f75d8e-714a-4324-b20e-a54292f908c4)
### 1. Menambah Tiket
Pilihan ini digunakan oleh admin untuk menambahkan tiket baru ke sistem. Setelah memilih opsi ini, admin akan diminta untuk memasukkan detail tiket, seperti:
- id tiket
- Nama tiket
- Harga tiket

![Menambah Tiket](https://github.com/user-attachments/assets/1dd535f0-137d-48d2-b22a-3d83f4e7aabd)
### 2. Menampilkan Tiket
Admin dapat memilih opsi ini untuk melihat daftar semua tiket yang sudah ditambahkan ke dalam program. Program akan menampilkan informasi setiap tiket, termasuk nama tiket, harga tiket, dan id tiket.
![Menampilkan Tiket](https://github.com/user-attachments/assets/b901ece7-daa7-436b-936b-0692c95418bf)
### 3. Memperbarui Tiket
Opsi ini memungkinkan admin untuk memperbarui informasi dari tiket yang sudah ada. Admin akan diminta untuk memilih tiket yang ingin diperbarui berdasarkan id tiket, dan kemudian dapat memperbarui detail seperti harga atau nama tiket.
![Memperbarui Tiket](https://github.com/user-attachments/assets/f1c1d160-603c-4bd8-bb53-b7bd21c4d155)
### 4. Menghapus Tiket
Admin dapat menghapus tiket dari daftar, dengan memilih opsi ke 4 ini. Program akan meminta admin memasukkan id tiket yang ingin dihapus, dan tiket tersebut akan dihapus dari program.
![Menghapus Tiket](https://github.com/user-attachments/assets/09175195-3157-4c92-b490-f26dda841920)
### 5. Kembali ke Menu Utama
Opsi ini digunakan untuk kembali ke Menu Utama. Setelah memilih opsi ini, program akan menampilkan kembali Menu Utama dan admin bisa memilih mode lain atau keluar dari program.
![Kembali](https://github.com/user-attachments/assets/fe859a39-44c9-4f91-9fc5-5cd77d0d42f2)

## Menu Pembeli
Jika pengguna memilih mode Pembeli dari menu utama dengan memasukkan angka 2, program akan menampilkan Menu Pembeli dengan dua opsi yang dapat dilakukan oleh pembeli, yaitu membeli tiket dan kembali ke menu utama. Berikut adalah tampilan dan penjelasan dari setiap pilihan yang ada di dalam Menu Pembeli:
![Menu Pembeli](https://github.com/user-attachments/assets/915bfab1-1fc1-4f84-a8d1-1a0ff939db7a)

### 1. Beli Tiket
Menu ini digunakan oleh pembeli untuk melakukan transaksi pembelian tiket. Setelah memilih opsi ini, program akan memandu mereka melalui beberapa langkah untuk menyelesaikan pembelian. Setelah pembeli memilih tiket yang diinginkan, sistem akan mencatat transaksi dan tiket tersebut dianggap sudah terjual.
![Beli Tiket](https://github.com/user-attachments/assets/b32bf2f9-c6ad-4ffd-831a-a0aa06c8cdb1)

### 2. Kembali ke Menu Utama
Setelah tiket berhasil dibeli, program akan kembali ke Menu Pembeli atau Menu Utama, tergantung pada implementasi. Pembeli kemudian dapat melanjutkan untuk membeli tiket lain atau kembali ke menu utama untuk keluar.

## Keluar
Ketika pengguna memilih opsi 3 dari Menu Utama, program akan menampilkan pesan perpisahan dan menghentikan eksekusi. Berikut adalah tampilan yang muncul saat pengguna memilih untuk keluar:
![Keluar](https://github.com/user-attachments/assets/3188a0b2-c381-4ce1-98b8-c34d061495b4)

## Else
Jika pengguna memasukkan menu selain ketiga opsi diatas (tidak valid), maka program akan menampilkan pesan "Menu yg anda masukkan tidak valid!".

## Struktur Program
- Main.java: Program utama yang menampilkan menu dan menjalankan operasi berdasarkan input pengguna. Dengan menggunakan loop, program tetap berjalan hingga pengguna memilih untuk keluar.
- Ticket.java:  Kelas ini merepresentasikan objek tiket yang memiliki beberapa atribut penting, seperti nama tiket, harga, dan id tiket.
- TicketSales.java:  Kelas ini bertanggung jawab untuk mengelola seluruh aspek penjualan tiket. Kelas ini biasanya menggunakan struktur data seperti ArrayList untuk menyimpan daftar tiket dan menyediakan metode untuk mencari, memperbarui, atau menghapus tiket berdasarkan ID.
