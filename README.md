pertama buat folder terlebih dahulu 
apabila sudah membuat folder kemudian open git bash lalu start configure
untuk masuk ke folder ketik cd "nama folder yang dibuat/
kemudian ketik git config --global user.name “nama_kalian”
git config --global user.email “nama_user”
lalu buat direktory project menggunakan commmand mkdir 
mkdir latihan vcs
cd latihan vcs
kemudian git init untuk membuat repository
kita akan coba buat satu file bernama README.md (text file)
$ echo “# Latihan 1” >> README.md
kemudian ketik git add README.md untuk mengecek apakah file readme.md ter add menggunakan git status
• Untuk menyimpan perubahan yang ada kedalam database repository 
local, gunakan perintah git commit -m “komentar commit”
buat repository server di github apabila belum membuat akun silahkan daftar terlebih dahulu git remote add origin [url]
Untuk mengirim perubahan pada local repository ke server gunakan 
perintah git push.
command git push -u origin master command untuk perintah memasukan username dan password pada akun github.com
terakhir apabila kalian ingin meng copy repository server secara otomatis 
gunakan command git clone [url]
