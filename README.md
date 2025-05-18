# github-docs
![image](https://github.com/user-attachments/assets/570475bf-7ba4-4d06-bf03-48556f647a96)


# melakukan push untuk pertama kali
git init

git add . (menambahkan file yang telah di ubah)

git commit -m "pesan code yang dilakukan" (melakukan commit dan memberikan pesan

git push -u origin nama_branch (melakukan push ke branch yang diinginkan)



# fungsi untuk menimpa semua code development ke branch yang aktif
git checkout development -- .


# menimpa isi branch yang sedang aktif dengan development
git reset --hard origin/development


# Buat branch baru
git checkout -b nama_branch

# Pindah ke branch lain
git checkout nama_branch

# Lihat daftar branch
git branch                  ( Branch lokaln )
git branch -a               ( Semua branch (termasuk remote) )

# Hapus branch lokal
git branch -d nama_branch   (Hapus jika sudah di-merge)

git branch -D nama_branch   ( Hapus paksa (belum di-merge) )


#mengambil perubahan dari remote
git fetch (melakukan remote ke branch origin/branch saat melakukan clone)

git fetch --all (melakukan remote ke semua branch)

git fetch nama_remote_lain (remote ke branch spesifik)
