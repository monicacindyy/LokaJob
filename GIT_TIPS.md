# 📘 Tips Penggunaan Git untuk Pemula

Panduan singkat menggunakan Git dalam pengembangan harian.

---

## ✅ Inisialisasi Git
git init

## 🔍  Cek Status Perubahan
git status

## 📂 Menambahkan Perubahan ke Staging
| Aksi                   | Perintah             |
| ---------------------- | -------------------- |
| Tambah semua perubahan | `git add .`          |
| Tambah file tertentu   | `git add index.html` |

## 💬 Commit Perubahan
git commit -m "Pesan commit yang jelas"
git commit -m "Update tampilan homepage dan perbaiki footer"

## 🚀 Push ke GitHub
git push origin main
Jika pertama kali:
git push --set-upstream origin main

## 📥 Menarik Perubahan (Pull)
git pull origin main --rebase

## 🔁 Membatalkan Perubahan
| Aksi                           | Perintah                  |
| ------------------------------ | ------------------------- |
| Batalkan semua perubahan lokal | `git restore .`           |
| Batalkan satu file             | `git restore nama_file`   |
| Reset commit terakhir          | `git reset --hard HEAD~1` |
⚠️ Hati-hati saat menggunakan --hard, karena akan menghapus perubahan permanen.

## 🕒 Cek Riwayat Commit
git log --oneline --graph --all

## 🗑️ Menghapus File atau Folder
rm -r folder/
git rm nama_file
