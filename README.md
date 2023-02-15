# git-learn

Belajar menggunakan git 

git clone : untuk mendownload repository di git melalui https atau url

git add : untuk menambahkan data sementara ke dalam repository 

git commit : untuk menambahkan comment pada data yang telah diubah

git push : untuk memasukkan data permanen di git

git status : untuk melakukan pengecekan data yang diubah pada lokal data yang akan dimasukkan ke git

git checkout/switch : untuk mengganti posisi branch

git branch : untuk mengecek branch yang ada pada repository

git pull : untuk menarik data asal branch ke branch lainnya

git stash: untuk mengembalikan perubahan ke awal atau undo

Prakteknya:
- git clone https://github.com/marioviegash/git-learn.git
- setelah menambahkan perubahan data sementara bisa menggunakan git add . (untuk ditambahkan semua perubahan datanya)
- git status (untuk mengecek perubahan data yang dilakukan)
- git commit -m "Masukkan_Comment"
- git push (untuk memasukkan seluruh isinya ke git)

Untuk menambahkan dan memindahkan branch
- git branch nama_branch_baru
- git switch nama_branch
- git pull origin nama_branch (isi branch yang mau ditarik ke salah satu branch)
- git push origin nama_branch (untuk memasukkan data permanen ke branch)

Untuk menghapus branch di lokal
- git branch -d nama_branch

Untuk menghapus branch di git
- git push origin -d nama_branch