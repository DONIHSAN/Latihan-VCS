# Latihan-VCS

## Instalasi Git 

**1. Download File Git**

Untuk menginstall Git, Anda perlu mengunduh file-nya terlebih dahulu di situs resminya. Download sesuai tipe sistem operasi pada komputer Anda. Apabila tipe sistem operasi komputer Anda 64bit,  pilih Git yang mendukung Windows 64bit. Tujuannya adalah agar tidak terjadi error saat proses instalasi.

![gambar 1](screenshot/ss%201.png)

**2. Install Git**

Setelah selesai mengunduh file Git, buka setup aplikasi Git untuk memulai proses instalasi. Halaman awal setelah Anda membuka setup aplikasi Git adalah tampilan Document License dari Git. Klik Next untuk melanjutkan instalasi.

![gambar 2](screenshot/ss%202.png)

**3. Tentukan Lokasi Instalasi Git**

Selanjutnya, pilih lokasi untuk install Git pada komputer Anda. Pada tutorial ini kami menginstall di lokasi C:\Program Files\Git. Setelah menentukan lokasi instalasi Git, klik Next untuk melanjutkan .

![gambar 3](screenshot/ss%203.png)

**4. Pilih Komponen Tambahan**

Kemudian pilih komponen tambahan untuk install Git. Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar. Sesuaikan komponen tambahan yang dipilih seperti pada gambar di bawah ini. Jika sudah klik Next untuk melanjutkan instalasi.

![gambar 4](screenshot/ss%204.png)

**5. Tentukan Nama Aplikasi Git**

Sebenarnya Anda bebas mengganti nama aplikasi Git yang akan ditampilkan pada Start Menu. Akan tetapi, demi kemudahan saat mencari aplikasi ini, sebaiknya gunakan nama Git saja.  

![gambar 5](screenshot/ss%205.png)

**6. Tentukan File Editor**

Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Pada tutorial ini, kami menggunakan Vim Editor. Klik Next apabila Anda sudah menentukan file editor yang akan Anda gunakan.

![gambar 6](screenshot/ss%206.png)

**7. Atur Path Environment**

Selanjutnya adalah pengaturan Path Environment. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih Git from the command line and also from 3rd-party software agar saat menjalankan perintah Git dapat dikenali di Command Prompt (CMD) pada Windows.

![gambar 7](screenshot/ss%207.png)

**8. Pilih Aplikasi SSH**

Kemudian untuk mengeksekusi SSH, Anda bisa menggunakan aplikasi dari Git atau  dari platform lain seperti PuTTY dan Bitvise. Pada tutorial ini kami menggunakan Use OpenSSH, aplikasi default SSH dari Git. Klik Next untuk melanjutkan instalasi.

![gambar 8](screenshot/ss%208.png)

**9. Pilih Line Ending**

Selanjutnya, Anda perlu memilih pengaturan line ending. Pada tutorial ini kami memilih Checkout Windows-style, commit Unix-style line endings. Klik Next untuk melanjutkan instalasi.

![gambar 9](screenshot/ss%209.png)

**10. Pilih Emulator Terminal**

Setelah itu, Anda perlu memilih emulator terminal yang akan digunakan. Anda bisa menggunakan Command Prompt atau MinTTY. Karena ingin menggunakan Command Prompt, pada tutorial ini kami memilih Use Windows default console windows. Klik Next untuk melanjutkan instalasi.

![gambar 10](screenshot/ss%2010.png)

**11. Tentukan Opsi Ekstra**

Terdapat beberapa opsi ekstra yang bisa Anda pilih. Pertama, pilih Enable File System Caching agar Git memiliki fungsi system caching. Kedua, pilih Enable Git Credential Manager agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub. Klik Next untuk melanjutkan instalasi.

![gambar 11](screenshot/ss%2011.png)

**12. Mulai Proses Instalasi**

Setelah menambahkan konfigurasi ekstra pada Git, Anda bisa memulai proses instalasi Git. Klik Install untuk melanjutkan proses.

![gambar 12](screenshot/ss%2012.png)

Berikut ini adalah tampilan proses instalasi Git. Tunggu hingga proses selesai dan Anda bisa menggunakan Git pada Windows.

![gambar 13](screenshot/ss%2013.png)

**13. Cek Versi Git**

Setelah proses instalasi selesai, Anda perlu mengecek apakah instalasi Git berhasil atau tidak. Anda bisa mengeceknya melalui Command Prompt. Klik Win+R lalu ketik CMD untuk membuka Command Prompt seperti di bawah ini.

![gambar 14](screenshot/ss%2014.png)

Selanjutnya masukkan perintah berikut untuk cek versi git dan cek apakah Git sudah terinstall di komputer Anda.

git --version

Jika Git berhasil terinstall, Anda akan melihat tampilan seperti di bawah ini yang menunjukkan versi Git. 

![gambar 15](screenshot/ss%2015.png)

## Cara Penggunaan Git

Setelah berhasil install ke Git, selanjutnya kami akan memberikan 10 langkah menggunakan Git. Berikut ini adalah sembilang langkah menggunakan Git.

**1. Login Git**

Untuk login ke Git, Anda bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum memiliki akun dari ketiga platform tersebut, Anda bisa mendaftarkan diri terlebih dahulu. Selanjutnya Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows) atau Command Line (Linux) . Kemudian masukkan perintah-perintah yang akan kami jelaskan di bawah ini.

Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.

$ git config --global user.name "UsernameAnda"

Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.

$ git config --global user.email IsiDenganEmailAnda@gmail.com

Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.

$ git config --list

![gambar 16](screenshot/ss%2016.png)

**2. Login Github**

Langkah kedua dalam belajar menggunakan Git adalah Anda harus login ke dalam website GitHub. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman.

Setelah Anda login, akan muncul tampilan dashboard dari GitHub seperti  gambar di bawah ini.

![gambar 17](screenshot/ss%2017.png)

**3. Buat Respitory**

Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.

![gambar 18](screenshot/ss%2018.png)

Kemudian Anda akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.

Anda perlu mengisi detail informasi berikut:

- Nama Repository : digunakan untuk identitas repository yang dibuat.
- Deskripsi Repository : berfungsi untuk deskripsi dari repository yang dibuat.
- Jenis Repository   : jenis repository  dibagi menjadi Public dan Private. Ketika Anda mengatur repository menjadi Public, orang lain dapat melihat repository yang Anda buat. Sebaliknya, jika Anda mengaturnya sebagai Private, repository tersebut hanya bisa diakses oleh Anda.

Setelah mengisi detail informasi di atas, klik Create Repository.

**4. Buat Folder Pada Windows**

Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.

![gambar 19](screenshot/ss%2019.1.png)

**5. Buka Folder Dengan Menggunakan Git Bash**

![gambar 20](screenshot/ss%2019.png)

Setelah berhasil membuat folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini. 

![gambar 21](screenshot/ss%2020.png)

**6. Ubah Folder Menjadi Repository**

Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:

$ git init

![gambar 22](screenshot/ss%2021.png)

**7. Tambahkan File ke Repository**

Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini:

- Buat file di folder yang sudah dibuat (Test Git). Contohnya, di sini kami membuat file index.php
- Buka GitBash lalu masukkan perintah berikut:

$ git add index.php

Perintah tersebut tidak akan menghasilkan output apa pun.

**8. Buat Commit**

Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:

$ git commit -m "first commit"

Pada tutorial ini kami membuat first commit sebagai Commit pertama kami. Anda bebas membuat membuat nama Commit apa saja.

![gambar 23](screenshot/ss%2022.png)

**9. Remote Repository Github**

Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:

$ git remote add origin git@github.com:UserNameGit/NamaRepository.git

Perintah di atas tidak akan menghasilkan output apa pun.

![gambar 24](screenshot/ss%2023.png)

**10. Push ke GitHub** 

Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:

git push -u origin master

Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub.

![gambar 25](screenshot/ss%2024.png)

Jika proses login berhasil, akan muncul tampilan Command Prompt seperti di bawah:

![gambar 26](screenshot/ss%2025.png)

**11. Cek File** 

Setelah itu, cek repository yang telah Anda buat. Anda akan mendapati file-file yang telah ditambahkan sebelumnya. Pada tutorial ini kami menambahkan tiga file, yaitu index.php, single.php, dan README.txt.

![gambar 27](screenshot/ss%2026.png)

## Kesimpulan

Cara menggunakan Git ini wajib diketahui dan dikuasai oleh semua developer karena akan sangat membantu dalam mengerjakan project pembuatan website.

Demikian penjelasan tentang cara menggunakan Git. Jika masih ada pertanyaan, jangan sungkan untuk meninggalkan di kolom komentar. Jangan lupa juga subscribe untuk mendapatkan informasi terbaru dari kami.


