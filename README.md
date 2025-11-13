# GitHub Docus

<div align="center">
  <img src="https://github.com/user-attachments/assets/570475bf-7ba4-4d06-bf03-48556f647a96" width="300" alt="GitHub Workflow">
</div>

<p align="center"><em>Electric Wind God Fist</em></p>



## Git Command Fav 

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🔄  INISIALISASI & PUSH PERTAMA  
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Inisialisasi repo baru
git init

# Menambahkan semua file yang diubah
git add . 

# Melakukan commit dengan pesan
git commit -m "Pesan commit"  

# Push ke branch yang diinginkan (pertama kali)
git push -u origin nama_branch


#untuk menduplikat projek dari repo
git clone link_guthub
```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🛠️  OPERASI FILE & BRANCH  
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Menimpa kode dari branch development ke branch aktif
git checkout development -- .   

# Reset penuh ke development branch
git reset --hard origin/development  

# Buat dan pindah ke branch baru
git checkout -b nama_branch     

# Pindah ke branch yang ada
git checkout nama_branch        

#untuk beralih antar cabang
git switch <nama-cabang>
```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🌳  MANAJEMEN BRANCH  
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# List branch lokal
git branch       

# List semua branch (termasuk remote)
git branch -a    

# Hapus branch yang sudah di-merge
git branch -d nama_branch   

# Hapus paksa branch belum di-merge
git branch -D nama_branch

```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🌐  SINKRONISASI REMOTE  
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Update branch origin default
git fetch                 

# Update semua remote branch
git fetch --all           

# Update specific remote
git fetch nama_remote

# pindah repository
git remote set-url origin https://github.com/team-name/nama-repo-tim.git
```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🔍 INSPEKSI & HISTORI
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Lihat perubahan yang belum di-commit
git status

# Lihat history commit
git log --oneline --graph

# Lihat perubahan spesifik suatu commit
git show <commit-hash>

# Cari perubahan pada kode
git grep "keyword"
```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### ✏️ PERUBAHAN & PEMBETULAN
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Batalkan perubahan file tertentu
git checkout -- nama_file

# Batalkan semua perubahan lokal
git checkout -- .

# Ubah commit terakhir
git commit --amend

# Buat tag versi
git tag -a v1.0.0 -m "Release version 1.0.0"
```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🤝 KOLABORASI & PULL REQUEST
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Ambil perubahan dan merge ke branch aktif
git pull origin nama_branch

# Buat branch tracking dari remote
git checkout --track origin/nama_branch

# Kirim branch ke remote
git push origin nama_branch

# Hapus branch remote
git push origin --delete nama_branch
```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🧹 PEMBERSIHAN & OPTIMISASI
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Hapus file yang tidak ter-track
git clean -fd

# Prune branch remote yang sudah dihapus
git fetch --prune

# Kompres dan optimasi repository
git ggc

#untuk menghapus untracked file/perubahan
git clean -f

```

<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">
### 🧩 STASH & WORKFLOW
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="900">

```bash
# Simpan perubahan sementara
git stash push -m "Pesan stash"

# Lihat daftar stash
git stash list

# Ambil kembali stash terakhir
git stash pop

# Buang perubahan di stash
git stash drop
```
