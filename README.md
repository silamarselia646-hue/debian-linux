# debian-linux
Materi pembelajaran Debian 12 yang mencakup instalasi sistem operasi, perintah terminal Linux, konfigurasi IP Address, dan administrasi server.1. Pengenalan Debian 12

Debian 12 merupakan sistem operasi berbasis Linux yang bersifat open source dan dapat digunakan secara gratis. Debian 12 memiliki nama kode Bookworm. Sistem operasi ini dapat digunakan pada komputer pribadi maupun server untuk menjalankan berbagai kebutuhan komputasi dan layanan jaringan.

Debian 12 dikenal sebagai salah satu distribusi Linux yang memiliki stabilitas sistem serta dukungan berbagai perangkat lunak.

2. Sejarah Debian

Debian pertama kali diperkenalkan oleh Ian Murdock pada tanggal 16 Agustus 1993. Debian dikembangkan sebagai sistem operasi bebas yang dapat digunakan dan dikembangkan oleh masyarakat.

Nama Debian berasal dari gabungan nama Debra dan Ian. Seiring perkembangannya, Debian menjadi salah satu distribusi Linux yang banyak digunakan untuk kebutuhan komputer dan server.

Debian 12 dengan nama kode Bookworm dirilis pada tanggal 10 Juni 2023.

3. Fungsi Debian 12

Debian 12 memiliki beberapa fungsi dalam bidang teknologi informasi, antara lain:

Sebagai sistem operasi komputer dan server.

Mengelola sumber daya perangkat keras dan perangkat lunak.

Menjalankan berbagai aplikasi berbasis Linux.

Mengelola pengguna dan hak akses.

Menyediakan layanan jaringan komputer.

Menjalankan layanan web server dan database server.

Mendukung kegiatan administrasi sistem dan jaringan.

4. Instalasi Debian 12

Instalasi Debian 12 merupakan proses pemasangan sistem operasi Debian pada komputer atau mesin virtual.

Tahapan umum instalasi Debian 12 meliputi:

Mengunduh file ISO Debian 12 dari situs resmi Debian.

Menyiapkan media instalasi.

Melakukan booting melalui media instalasi.

Memilih metode instalasi.

Menentukan bahasa dan lokasi.

Mengatur konfigurasi jaringan.

Mengatur partisi penyimpanan.

Membuat akun pengguna dan kata sandi.

Memilih perangkat lunak yang diperlukan.

Menyelesaikan proses instalasi dan melakukan restart.

5. Perintah Dasar Terminal

Terminal merupakan antarmuka berbasis teks yang digunakan untuk menjalankan perintah dan mengelola sistem operasi Linux.

Berikut beberapa perintah dasar terminal Debian 12:

Perintah

Fungsi

pwd

Menampilkan lokasi direktori aktif

ls

Menampilkan isi direktori

cd

Berpindah direktori

mkdir

Membuat direktori baru

touch

Membuat file kosong

cp

Menyalin file

mv

Memindahkan atau mengganti nama file

rm

Menghapus file

clear

Membersihkan tampilan terminal

whoami

Menampilkan nama pengguna aktif

date

Menampilkan tanggal dan waktu

6. Manajemen File dan Direktori

Manajemen file dan direktori merupakan kegiatan mengatur, membuat, memindahkan, menyalin, serta menghapus file dan folder pada sistem operasi Debian.

Beberapa perintah yang digunakan:

mkdir: Membuat direktori baru.

touch: Membuat file kosong.

ls: Melihat isi direktori.

cd: Berpindah direktori.

cp: Menyalin file atau direktori.

mv: Memindahkan atau mengganti nama file.

rm: Menghapus file.

rmdir: Menghapus direktori kosong.

Manajemen file dan direktori bertujuan untuk menjaga susunan data agar lebih teratur dan mudah dikelola.

7. Manajemen User dan Group

Manajemen user dan group merupakan proses pengelolaan akun pengguna dan kelompok pengguna pada sistem operasi Debian.

Perintah yang digunakan antara lain:

Perintah

Fungsi

adduser

Membuat akun pengguna baru

userdel

Menghapus akun pengguna

passwd

Mengubah kata sandi pengguna

groupadd

Membuat grup baru

groupdel

Menghapus grup

id

Melihat identitas pengguna

groups

Melihat grup pengguna

Pengelolaan user dan group bertujuan untuk mengatur hak akses serta meningkatkan keamanan sistem.

8. Manajemen Paket APT

APT (Advanced Package Tool) merupakan sistem pengelolaan paket pada Debian yang digunakan untuk memasang, memperbarui, dan menghapus perangkat lunak.

Beberapa perintah APT yang umum digunakan:

Perintah

Fungsi

apt update

Memperbarui daftar paket

apt upgrade

Memperbarui paket terpasang

apt install

Memasang aplikasi

apt remove

Menghapus aplikasi

apt search

Mencari paket

apt show

Menampilkan informasi paket

apt autoremove

Menghapus paket yang tidak diperlukan

APT memudahkan pengguna dalam mengelola perangkat lunak melalui terminal.

9. Konfigurasi IP Address

IP Address merupakan alamat numerik yang digunakan untuk mengidentifikasi perangkat dalam suatu jaringan komputer.

Konfigurasi IP Address pada Debian dilakukan agar komputer dapat terhubung dan berkomunikasi dengan perangkat lain dalam jaringan.

Komponen konfigurasi jaringan meliputi:

IP Address: Alamat perangkat dalam jaringan.

Subnet Mask: Menentukan bagian jaringan dan perangkat.

Gateway: Jalur penghubung menuju jaringan lain.

DNS: Menerjemahkan nama domain menjadi alamat IP.

Network Interface: Antarmuka yang menghubungkan komputer dengan jaringan.

Konfigurasi jaringan dapat dilakukan menggunakan pengaturan jaringan Debian sesuai dengan layanan pengelola jaringan yang digunakan.

10. Konfigurasi SSH Server

SSH (Secure Shell) merupakan protokol jaringan yang digunakan untuk mengakses dan mengelola komputer atau server dari jarak jauh melalui koneksi yang aman.

SSH memungkinkan administrator melakukan pengelolaan server tanpa harus berada langsung di depan komputer server.

Fungsi SSH Server antara lain:

Mengakses server dari jarak jauh.

Menjalankan perintah melalui terminal.

Mengelola sistem server.

Melakukan pemindahan file secara aman melalui layanan yang mendukung SSH.

11. Konfigurasi DNS Server

DNS (Domain Name System) merupakan layanan jaringan yang berfungsi menerjemahkan nama domain menjadi alamat IP.

DNS memudahkan pengguna mengakses suatu layanan jaringan tanpa harus mengingat alamat IP numerik.

Fungsi DNS Server antara lain:

Menerjemahkan nama domain menjadi alamat IP.

Mempermudah akses terhadap layanan jaringan.

Mengelola informasi nama domain.

Mendukung komunikasi antara perangkat dalam jaringan.

12. Konfigurasi DHCP Server

DHCP (Dynamic Host Configuration Protocol) merupakan layanan jaringan yang digunakan untuk memberikan konfigurasi IP Address secara otomatis kepada perangkat klien.

DHCP Server membantu administrator dalam mengelola alamat IP sehingga tidak perlu mengatur alamat IP setiap perangkat secara manual.

Informasi jaringan yang dapat diberikan DHCP Server meliputi:

IP Address.

Subnet Mask.

Default Gateway.

DNS Server.

Masa penggunaan alamat IP atau lease time.

13. Konfigurasi Web Server

Web Server merupakan layanan yang berfungsi menyimpan, memproses, dan mengirimkan halaman web kepada pengguna melalui jaringan komputer.

Pada Debian 12, web server dapat dijalankan menggunakan perangkat lunak seperti Apache atau Nginx.

Fungsi Web Server antara lain:

Menyimpan file halaman web.

Memproses permintaan dari browser.

Mengirimkan halaman web kepada pengguna.

Menyediakan layanan website melalui jaringan lokal maupun internet.

14. Kesimpulan

Debian Linux 12 merupakan sistem operasi berbasis Linux yang dapat digunakan untuk berbagai kebutuhan administrasi sistem dan jaringan. Melalui pembelajaran Debian 12, pengguna dapat memahami proses instalasi sistem operasi, penggunaan perintah terminal, manajemen file, pengelolaan pengguna, serta konfigurasi berbagai layanan server.

Materi ini memberikan dasar pengetahuan dan keterampilan dalam bidang Teknik Komputer dan Jaringan, khususnya dalam memahami sistem operasi Linux dan penerapannya pada administrasi server.

