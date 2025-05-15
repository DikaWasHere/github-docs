# github-docs

#n melakukan push untuk pertama kali
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
git branch                  # Branch lokal
git branch -a               # Semua branch (termasuk remote)

# Hapus branch lokal
git branch -d nama_branch   # Hapus jika sudah di-merge
git branch -D nama_branch   # Hapus paksa (belum di-merge)
