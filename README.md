
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


**Membuat Repositor Baru**


Ini adalah tampilan pertama setelah kalian selesai membuat akun git

![screenshot2](https://user-images.githubusercontent.com/115804283/196388731-def02551-be25-4d96-8115-b1cc006badc2.png)


Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.
![screenshot3](https://user-images.githubusercontent.com/115804283/196389031-f038828a-a64e-404e-893e-8d9b3c7bdf1e.png)


Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
![Screenshot4](https://user-images.githubusercontent.com/115804283/196390135-b996fd7a-4b84-4f97-bd86-d0ae5f87bfe4.png)


**Membuat Repository Local**

Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . ![Screenshot5](https://user-images.githubusercontent.com/115804283/196390940-a4003b6c-8aed-4632-b93d-73e7625be28d.png)


Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email “email_user” $ git config --global user.name “nama_user”

![Screenshot6](https://user-images.githubusercontent.com/115804283/196391226-6abfb950-a06a-4da4-a67e-40678daf1f57.png)


Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman1 ![Screenshot7](https://user-images.githubusercontent.com/115804283/196391943-4a475aab-dc76-44d4-ba72-23dde4af99d0.png)
".

**Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local**

Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

![screemshot8](https://user-images.githubusercontent.com/115804283/196392470-f135a7ed-b838-43d4-921c-c6e79412299e.png)




Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

![screenshot9](https://user-images.githubusercontent.com/115804283/196393086-a02f514a-c776-400a-8705-7d22503e4d8d.png)


**Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit**
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status. ![sreenshot10](https://user-images.githubusercontent.com/115804283/196393795-6f27549d-552f-45be-a8e9-8672edb99254.png)


Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit![screenshot11](https://user-images.githubusercontent.com/115804283/196394368-be1acdf7-4aed-4b24-b6cb-8445869a25a0.png)



**File berhasil tersimpan**
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_

**Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)**

Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/iki020904/latihangit1/edit/master/README.md ![12](https://user-images.githubusercontent.com/115804283/196395228-295e12c3-1f0e-44a8-b775-20fa4b52f722.png)

**Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository**

Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. git_push

![13](https://user-images.githubusercontent.com/115804283/196395876-109e11ae-4bca-4e63-80b5-11d78e067cd5.png)


#**Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.**


Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/iki020904/latihangit1/edit/master/README.md . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1" 
![14](https://user-images.githubusercontent.com/115804283/196396611-4342faf3-6540-4af3-bb1b-82b6488854cc.png)


Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
Terimakasih


