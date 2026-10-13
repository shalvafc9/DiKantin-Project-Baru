# Tutorial memperbarui DiKantin di VS Code

Tutorial ini untuk memasukkan perubahan desain ke folder proyek GitHub yang sudah kamu buka di VS Code.

## File yang perlu diganti

- Ganti seluruh isi **app.js** dengan file app.js dari paket pembaruan.
- Ganti seluruh isi **style.css** dengan file style.css dari paket pembaruan.
- Tambahkan **logo-dikantin.jpeg** ke folder **assets**.
- Jangan hapus **index.html** atau foto makanan yang sudah ada.

## Cara memasukkan file pembaruan

1. Unduh **DiKantin-Mobile-VSCode-Update.zip**, klik kanan, lalu pilih **Extract All...**. Ekstrak ke folder sementara.
2. Buka folder proyek lama di File Explorer, yaitu folder yang berisi **index.html**, **app.js**, dan folder **assets**.
3. Dari folder hasil ekstrak, salin **app.js** dan **style.css** ke folder proyek lama. Saat Windows bertanya, pilih **Replace the files in the destination**.
4. Dari folder hasil ekstrak, salin **assets/logo-dikantin.jpeg** ke folder **assets** di proyek lama. Jika Windows bertanya, pilih **Replace the file in the destination**.
5. Kembali ke VS Code. Pastikan file **app.js**, **style.css**, dan **assets/logo-dikantin.jpeg** terlihat di Explorer.
6. Tekan **Ctrl + S** untuk menyimpan. Jika Live Server sedang berjalan, halaman akan dimuat ulang otomatis.

## Perubahan yang dibuat

- Logo huruf “D” diganti dengan logo DiKantin yang kamu kirim.
- Tulisan halaman masuk berubah menjadi “Selamat datang di kantin!”
- Beranda berhenti setelah kartu tips; bagian “Kantin dekat kamu” dihapus.
- Navigasi bawah hanya menampilkan **Beranda** dan **Profil**.
- Judul pemilihan kantin menjadi “Pilih kantin fakultas favoritmu”.
- Di halaman tenant, filter hanya menampilkan **Semua tenant**. Pilih tenant dan pilih menu memakai dua bagian yang bisa dibuka-tutup. Masing-masing punya kotak pencarian.
- Jika memilih **Ambil sendiri**, setelah memilih kantin alur langsung ke tenant tanpa halaman scan meja.
- Di alur **Makan di tempat**, kotak nomor meja di halaman scan dihapus. Tombol simulasi tetap memakai meja demo nomor 14, yang terlihat di halaman konfirmasi.

## Periksa tampilan di VS Code

1. Buka **index.html** di VS Code.
2. Klik **Go Live** di pojok kanan bawah.
3. Coba masuk sebagai tamu, pilih mode, lalu pilih kantin.
4. Pada halaman tenant, buka **Pilih tenant**, cari warung, lalu pilih. Setelah itu buka **Pilih menu** dan gunakan pencarian menu.

## Kirim pembaruan ke GitHub Pages

1. Di panel **Source Control**, stage file yang berubah dengan tombol **+**.
2. Isi pesan commit, misalnya **Perbarui tampilan DiKantin**, lalu klik **Commit**.
3. Klik **Sync Changes** atau pilih **Git: Push** dari Command Palette.
4. Tunggu proses **Pages build and deployment** selesai di tab **Actions** GitHub. Setelah tanda centang hijau muncul, muat ulang alamat situsmu.

## Catatan

Login, scan QR, pembayaran QRIS, dan status pesanan masih berupa simulasi di browser. Meja demo untuk dine-in tetap nomor 14 setelah tombol scan disimulasikan.
