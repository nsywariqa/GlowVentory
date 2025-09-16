# Glowventory
**Sistem Manajemen Inventori untuk Skincare Store (MVP)**

---

## Tim
- Nasywa Ariqa Ridha
- Adha Gusti Harmadhan
- A'lieyya Maysarah 
- Putri Balqis

---

## 1. Latar Belakang

Industri kosmetik di Indonesia menunjukkan pertumbuhan yang signifikan. Pada tahun 2019, sektor industri kimia, farmasi, dan obat tradisional mengalami kenaikan sebesar 18,57%, dengan nilai produk domestik bruto (PDB) mencapai Rp22,26 triliun pada kuartal IV tahun 2019. Sebagian besar dari sektor ini didominasi oleh industri kecil dan menengah (IKM), yang berjumlah lebih dari 760 perusahaan. Namun, Seiring dengan pertumbuhan tersebut, toko skincare menghadapi berbagai tantangan dalam mengelola stok barang, antara lain:

- **Over-stok**: Produk menumpuk dan mendekati tanggal kedaluwarsa, meningkatkan risiko kerugian.  
- **Kehabisan stok produk populer**: Menurunkan kepuasan pelanggan dan potensi penjualan.  
- **Data stok yang tidak akurat**: Pencatatan manual yang rawan kesalahan, menghambat pengambilan keputusan yang tepat.

Glowventory hadir sebagai solusi digital untuk membantu pemilik dan staf toko dalam memantau, mencatat, dan mengelola stok secara **real-time, efisien, dan terstruktur**, serta memungkinkan pelanggan **melihat ketersediaan produk melalui katalog**.

---

## 2. Ruang Lingkup MVP
- **Admin (Pemilik Toko)**: full akses (manajemen produk, stok, laporan, manajemen user)  
- **Staff**: input barang masuk/keluar, update stok, melihat laporan stok terbatas  
- **Pelanggan**: hanya dapat melihat **katalog produk** dan menggunakan **fitur pencarian**  
- **Transaksi stok** dimasukkan manual oleh staff (tidak ada integrasi POS)  


---

## 3. Fitur Utama

### 3.1 Manajemen Produk
- Tambah, edit, hapus produk skincare  
- Data produk meliputi: nama, kategori, harga, stok, tanggal kedaluwarsa  
- Upload gambar produk untuk identifikasi lebih mudah  

### 3.2 Manajemen Stok
- Update stok secara manual saat barang masuk/keluar  
- Pencatatan riwayat stok untuk monitoring  
- Notifikasi stok rendah bagi admin/staff  

### 3.3 Laporan & Analitik
- Laporan stok harian, mingguan, dan bulanan  
- Statistik produk terlaris dan kurang laku  
- Grafik pergerakan stok  

### 3.4 Multiuser Role
- **Admin**: akses penuh  
- **Staff**: akses terbatas (input transaksi, update stok, lihat laporan)  
- **Pelanggan**: akses terbatas ke **katalog produk** dan **pencarian produk**  

### 3.5 Pencarian & Filter Produk
- Pencarian produk berdasarkan nama atau kategori  
- Filter produk berdasarkan stok tersedia, kategori, atau harga
### 3.6 Notifikasi

- **Admin & Staff:**  
  - Pemberitahuan ketika stok suatu produk mencapai batas minimum (stok menipis).  
  - Membantu staf/admin mengambil tindakan cepat untuk restock.

- **Pelanggan:**  
  - Pemberitahuan jika produk yang sebelumnya kosong sudah tersedia kembali.  
  - Memberikan kemudahan bagi pelanggan untuk memantau ketersediaan produk favorit melalui katalog.
  

---

## 4. Arsitektur Teknis

### Backend Stack
- Laravel 12 (PHP Framework)  
- MySQL (Database)  

### Frontend Stack
- Blade Templating  
- Tailwind CSS  

### Package Tambahan
- Spatie Laravel Permission (manajemen role & permission)  
- Laravel Excel (ekspor laporan stok)  
- Chart.js (visualisasi data stok & laporan)  

---

## 5. Manfaat

### Bagi Pemilik Toko / Admin
- Memantau stok dengan lebih mudah dan akurat  
- Mengurangi risiko kerugian akibat produk menumpuk atau kedaluwarsa  
- Memudahkan pengambilan keputusan berbasis data  

### Bagi Staff
- Input transaksi lebih cepat, pencatatan digital minim kesalahan  
- Monitoring stok menjadi lebih mudah  

### Bagi Pelanggan
- Bisa melihat ketersediaan produk sebelum datang ke toko  
- Pencarian produk membuat pengalaman browsing lebih efisien  

---

## 6. Ringkasan
Glowventory adalah sistem manajemen inventori yang dirancang untuk toko skincare. MVP ini memungkinkan pengelolaan stok, pencatatan transaksi, laporan analitik, dan **katalog produk untuk pelanggan**, tanpa integrasi POS atau fitur belanja online. Sistem ini membantu pemilik toko dan staff mengelola usaha dengan lebih efektif, serta memberikan pelanggan akses terbatas untuk melihat produk yang tersedia.
