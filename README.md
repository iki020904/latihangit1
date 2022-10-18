
Hallo nama saya Muhammad Rifqi aziz. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah Applikasi git , akun git. Sebelum itu saya akan kasih tutorial cara penginstalan GIT.

**Cara penginstalan GIT**

Pertama anda harus mendownload Aplikasi Git, buka website resminya Git di git-scm.com .
![git hub](https://user-images.githubusercontent.com/115804283/196384038-a1f9e84f-45d6-4ac0-8872-d88d21baa5d0.png)
 Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal

Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

![1](https://user-images.githubusercontent.com/115804283/196384510-5299a3a5-400a-43af-8c8a-cc2f41cf17dc.png)



Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1

![195978194-04778e47-f0cd-4d03-9ceb-23394a12b588](https://user-images.githubusercontent.com/115804283/196386681-12116646-e3a6-46ad-9499-f691022fa440.png)


Cara membuat akun git
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com
![screnshot](https://user-images.githubusercontent.com/115804283/196387194-93bbe1d9-3449-4a45-98cc-fcad4d9d88ac.png)


Pada langka selanjutnya anda boleh langsung diskip saja.

Membuat repositori baru
Ini adalah tampilan pertama setelah kalian selesai membuat akun git

Screenshot (13)

Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.
Screenshot (14)

Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
Screenshot (18)

Membuat Repository Local
Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . Screenshot (20)

Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email “email_user” $ git config --global user.name “nama_user”

Screenshot (21)

Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman1Screenshot (22) ".

Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local
Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

![download](https://user-images.githubusercontent.com/115804283/196315401-64cd517e-b21c-493e-ade7-82499027125b.jpg)


Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

Screenshot (24)

Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status. Screenshot (26)

Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit" 67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3

File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/iki020904/latihangit1/edit/master/README.md Screenshot (8-)
Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. git_push
Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/iki020904/latihangit1/edit/master/README.md . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1" git_push

Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
Terimakasih


