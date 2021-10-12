# LatihanVCS
Nama: Adrian Fadhali Wiratama<br>
Nim: 312110329<br>
Kelas: TI.21.A.2<br>

Tutorial menggunakan git:<br><br>

Download Git, buka website resminya Git (git-scm.com). 
• Kemudian unduh Git sesuai dengan arsitektur komputer kita. 
Kalau menggunakan 64bit, unduh yang 64bit.
Begitu juga kalau menggunakan 32bit. 
• Selamat, Git sudah terinstal di Windows. 
Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah:
git --version

• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
user.name dan user.email
• konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository. • apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi
kegagalan saat menjalankan perintah git commit
• Config Global Repository
$ git config --global user.name “nama_user”
$ git config --global user.email “email_user”

Perintah dasar git
• git init, perintah untuk membuat repository local
• git add, perintah untuk menambahkan file baru, atau perubahan pada file
pada staging sebelum proses commit. 
• git commit, perintah untuk menyimpan perubahan kedalam database git. 
• git push -u origin master, perintah untuk mengirim perubahan pada
repository local menuju server repository. 
• git clone [url], perintah untuk membuat working directory yang diambil dari
repositry sever. 
• git remote add origin [url], perintah untuk menambahkan remote
server/reopsitory server pada local repositry (working directory)
• git pull, perintah untuk mengambil/mendownload perubahan terbaru dari
server repository ke local repository

Membuat reposiory local
• Buka direktory aktif, misal: d:\labs_pemrograman1 (buka
menggunakan Windows Explorer)
• klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,
sehingga muncul git bash commad
• Buat direktory project praktikum pertama dengan nama latihan1
$ mkdir latihan1
$ cd latihan1
• Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya
masuk kedalam direktori tersebut dengan perintah cd (change
directory)
• direktory aktif menjadi: d:\labs_pemrograman1\latihan1

