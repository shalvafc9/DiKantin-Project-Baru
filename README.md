# DiKantin — web mobile

Prototipe web pemesanan makanan kantin kampus dengan tampilan khusus ponsel. Warna dan alur mengikuti referensi: latar lembut, oranye hangat, hijau tua, dan teks gelap.

## Menjalankan di VS Code

1. Buka folder proyek melalui **File → Open Folder...**.
2. Pasang ekstensi **Live Server** jika belum ada.
3. Buka **index.html**, lalu klik **Go Live** di pojok kanan bawah.
4. Untuk melihat ukuran ponsel di Chrome atau Edge, tekan **F12**, lalu **Ctrl + Shift + M**. Pilih ukuran sekitar 390 × 844.

Tidak perlu memasang npm atau server backend.

## Alur prototipe

1. Masuk dengan NIM atau pilih **Lanjut jelajah sebagai tamu**.
2. Pilih **Makan di tempat** atau **Ambil sendiri**.
3. Pilih kantin fakultas. Mode dine-in membuka simulasi scan meja; mode ambil sendiri langsung ke pilihan tenant.
4. Pilih tenant dan menu melalui bagian yang bisa dibuka-tutup. Cari warung atau menu memakai kotak pencarian.
5. Atur pesanan di keranjang, lalu lanjutkan ke pembayaran QRIS demo.
6. Simulasikan pembayaran, lihat pelacakan, dan isi ulasan.

Navigasi bawah hanya menampilkan **Beranda** dan **Profil**.

## Struktur file

- **index.html** — titik awal halaman dan pemanggil CSS/JavaScript.
- **style.css** — warna, komponen, tata letak, dan tampilan ponsel.
- **app.js** — data contoh, tampilan layar, dan interaksi prototipe.
- **assets/** — foto makanan, suasana kantin, dan logo DiKantin.
- **Tutorial-VS-Code.md** — panduan mengganti file proyek lama dan memperbarui GitHub Pages.

Foto **es-teh-kampul.png** dan **tahu-krispi.png** melengkapi kartu menu.

## Batasan demo

Login, scan QR, pembayaran QRIS, pelacakan, poin, dan ulasan hanya simulasi di browser. Kode QR pada halaman pembayaran tidak dapat dipindai dan tidak melakukan transaksi.
