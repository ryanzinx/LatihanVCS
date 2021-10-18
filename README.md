# LatihanVCS
Nama: Adrian Fadhali Wiratama<br>
Nim: 312110329<br>
Kelas: TI.21.A.2<br>

Tutorial menggunakan git:<br><br>

Download Git, buka website resminya Git (git-scm.com). <br>
• Kemudian unduh Git sesuai dengan arsitektur komputer kita. <br>
Kalau menggunakan 64bit, unduh yang 64bit.<br>
Begitu juga kalau menggunakan 32bit. <br>
• Selamat, Git sudah terinstal di Windows. <br>
Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah:<br>
git --version<br><br>

• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi<br>
user.name dan user.email<br>
• konfigurasi ini bisa dilakukan untuk global repostiry atau individual<br>
repository. • apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi<br>
kegagalan saat menjalankan perintah git commit<br>
• Config Global Repository<br>
$ git config --global user.name “nama_user”<br>
$ git config --global user.email “email_user”<br><br>

Perintah dasar git<br>
• git init, perintah untuk membuat repository local<br>
• git add, perintah untuk menambahkan file baru, atau perubahan pada file<br>
pada staging sebelum proses commit. <br>
• git commit, perintah untuk menyimpan perubahan kedalam database git. <br>
• git push -u origin master, perintah untuk mengirim perubahan pada<br>
repository local menuju server repository. <br>
• git clone [url], perintah untuk membuat working directory yang diambil dari<br>
repositry sever. <br>
• git remote add origin [url], perintah untuk menambahkan remote<br>
server/reopsitory server pada local repositry (working directory)<br>
• git pull, perintah untuk mengambil/mendownload perubahan terbaru dari<br>
server repository ke local repository<br><br>

Membuat reposiory local<br>
• Buka direktory aktif, misal: d:\labs_pemrograman1 (buka<br>
menggunakan Windows Explorer)<br>
• klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,<br>
sehingga muncul git bash commad<br>
• Buat direktory project praktikum pertama dengan nama latihan1<br>
$ mkdir latihan1<br>
$ cd latihan1<br>
• Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya<br>
masuk kedalam direktori tersebut dengan perintah cd (change<br>
directory)<br>
• direktory aktif menjadi: d:\labs_pemrograman1\latihan1<br><br>

Membuat Reposiory Local<br>
• Jalankan perintah git init, untuk membuat repository local.<br> 
• Repository baru berhasil di inisialisasi, dengan terbentuknya satu<br>
direktori hidden dengan nama .git<br>
• Pada direktori tersebut, semua perubahan pada working directory
akan disimpan.<br><br>

Menambahkan File baru pada repository<br>
• Untuk membuat file dapat menggunakan text editor, lalu menyimpan<br>
filenya pada direktori aktif (repository)<br>
• disini kita akan coba buat satu file bernama README.md (text file)<br>
• File README.md berhasil dibuat.<br><br>

Menambahkan File baru pada repository<br>
• Untuk menambahkan file yang baru saja dibuat tersebut gunakan<br>
perintah git add. <br>
• File README.md berhasil ditambahkan.<br><br>

Commit (Menyimpan perubahan ke database)<br>
• Untuk menyimpan perubahan yang ada kedalam database repository<br>
local, gunakan perintah git commit -m “komentar commit”<br>
• Perubahan berhasil disimpan. $ git commit -m “File pertama saya”<br><br>

Membuat repository server<br>
• Server reopsitory yang akan kita gunakan adalah http://github.com<br>
• Anda harus membuat akun terlebih dahulu. <br>
• Pada laman github, klik tombol start a project, atau<br>
• Dari menu (icon +) klik New Repository<br><br>

Membuat repository server
• Isi nama repositorynya, misal: labpy1.<br>
• Lalu klik tombol create repositorynya<br>



