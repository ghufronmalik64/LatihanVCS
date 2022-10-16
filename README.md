# Latihan VCS


## 1. Dwonload Git

Pastikan kalian sudah mendwonload Git terlebih dahulu

- *https://git-scm.com/downloads*

![img 1](image/image1.png)


## 2. Configurasi Nama atau Email

Lalu masukan nama atau email agar tidak terjadi kesalahan saat kalian melakukan perintah git commit.

* $git config --global user.name "username anda"
* $git config --global user.email "email anda"

![img 2](image/image2.png)


## 3. Login

Sebelumnya pastikan anda sudah terdaftar atau memiliki akun GitHub, lalu Login GitHub

![img 3](image/image3.png)


## 4. Membuat Repositori Baru

Setelah berhasil Login anda bisa membuat Repositori dengan cara klik tombol "New" pada tampilan awal GitHub

![img 4](image/image4.png)

Kemudian kalian akan di arahkan pada halaman New Repositori

![img 5](image/image5.png)


## 5. Membuat Folder Pada Lokal Disk

Buat folder baru di lokal disk anda

![img 6](image/image6.png)

Setelah membuat folder baru, klik kanan pada folder tersebut, lalu klik "Git Bash Here". Maka akan muncul aplikasi Pop-up Git Bash

![img 7](image/image7.png)


## 6. Membuat Folder Pada Git Bash

Buat folder baru dan arahkan Git Bash pada file direktori

* $mkdir tutorial
* $cd tutorial

![img 8](image/image8.png)


## 7. Menambahkan Judul Dalam File README.md

Tambahkan judul atau Header ke dalam file README.md yang nantinya akan dimasukan ke dalam Repositori yang kita buat

* $echo "#latihanvcs" >> README.md

![img 9](image/image9.png)


## 8. Membuat Repositori Lokal

Kemudian buat Repositori lokal menggunakan perintah *git init*

* $git init

![image 10](image/image10.png)


## 9. Memasukan file README.md ke Repositori

Masukan file README.md yang diberi judul tadi kedalam Repositori menggunakan perintah *git add*

* $git add README.md

![image 11](image/image11.png)


## 10. Mengonfirmasi Perubahan

Bila sudah ditambahkan, simpan dan konfirmasi perubahan dengan komentar menggunakan perintah *git commit -m "contoh commit"*

* $git commit -m "commit pertama"

![image 12](image/image12.png)


## 11. Menambahkan Repositori Jarak Jauh

Remote Repositori merupakan server repositori yang akan digunakan untuk menyimpan setiap perubahan pada repositori lokal, sehingga dapat diakses oleh banyak pengguna. caranya gunakan perintah *git remote add origin 'url'

* $git remote add origin https://github.com/ghufronmalik64/latihanvcs.git

![image 13](image/image13.png)

## 12. Mengirim perubahan

Untuk mengirim perubahan pada Repositori lokal ke server gunakan perintah *git push -u origin 'branch'*

* $git push -u origin master

![image 14](image/image14.png)

## Dan terakhir anda bisa cek hasil Repositori pada Website GitHub


# _____________________________________________________
# DI KASIH TUGAS HARI SENIN. TERIMAKASIH SUDAH NEMENIN. 
