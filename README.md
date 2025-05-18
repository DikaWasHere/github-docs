# GitHub Docus

<div align="center">
  <img src="https://github.com/user-attachments/assets/570475bf-7ba4-4d06-bf03-48556f647a96" width="300" alt="GitHub Workflow">
</div>

## Git Command Fav 

### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 🔄  INISIALISASI & PUSH PERTAMA  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```bash
# Inisialisasi repo baru
git init

# Menambahkan semua file yang diubah
git add . 

# Melakukan commit dengan pesan
git commit -m "Pesan commit"  

# Push ke branch yang diinginkan (pertama kali)
git push -u origin nama_branch 
```

### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 🛠️  OPERASI FILE & BRANCH  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```bash
# Menimpa kode dari branch development ke branch aktif
git checkout development -- .   

# Reset penuh ke development branch
git reset --hard origin/development  

# Buat dan pindah ke branch baru
git checkout -b nama_branch     

# Pindah ke branch yang ada
git checkout nama_branch        

```

### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 🌳  MANAJEMEN BRANCH  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
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

### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
### 🌐  SINKRONISASI REMOTE  
### ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```bash
# Update branch origin default
git fetch                 

# Update semua remote branch
git fetch --all           

# Update specific remote
git fetch nama_remote
```

