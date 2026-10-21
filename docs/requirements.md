# Dokumen Kebutuhan — Clean & Fresh Laundry

## Studi Kasus

| Komponen | Keterangan |
|---|---|
| Usaha | Clean & Fresh Laundry |
| Pengguna sasaran | Mahasiswa dan pekerja di sekitar kampus |
| Situasi penggunaan | Membuka website dari ponsel sebelum mengantar cucian |
| Kebutuhan pengguna | Mengetahui layanan, harga, lokasi, dan jam buka |
| Tujuan usaha | Memudahkan calon pelanggan memperoleh informasi |
| Tindakan utama | Melihat daftar layanan dan menemukan kontak |
| Ruang lingkup | Tiga halaman statis (beranda, layanan, pesanan) |
| Di luar ruang lingkup | Login, keranjang, pembayaran, database pesanan |

---

## Kebutuhan Fungsional

| ID | Kebutuhan | Kriteria Penerimaan |
|---|---|---|
| F-01 | Pengguna dapat melihat tiga layanan | Nama, deskripsi, dan harga tampil di opsi_layanan.html |
| F-02 | Navigasi menuju halaman dan bagian | Semua tautan dan anchor menuju tujuan yang benar |
| F-03 | Kontak mudah ditemukan | Alamat, jam buka, dan tautan WhatsApp tersedia |

---

## Kebutuhan Nonfungsional

| ID | Kebutuhan | Kriteria Penerimaan |
|---|---|---|
| NF-01 | Layout responsif | Tidak ada scroll horizontal pada viewport uji |
| NF-02 | Navigasi dapat digunakan melalui keyboard | Tautan dapat difokuskan dan diaktifkan |
| NF-03 | Markup valid | Tidak ada error HTML pada validator |
| NF-04 | Proyek mudah dipelihara | CSS terpisah dan README tersedia |

---

## Kebutuhan Teknis

- Viewport uji: 360 px, 390 px, 768 px, 1366 px
- Peramban uji: Chrome dan Firefox
- HTML dan CSS tanpa framework
- Gambar milik sendiri atau memiliki izin penggunaan

---

## Data Konten

| Layanan | Deskripsi | Harga |
|---|---|---|
| Cuci Kiloan Reguler | Cuci, kering, dan lipat, selesai 2 hari | Rp7.000/kg |
| Cuci Express | Layanan cepat, selesai 6 jam | Rp12.000/kg |
| Cuci Satuan | Sepatu, bed cover, dan karpet | Mulai Rp25.000/pasang |

| Info | Keterangan |
|---|---|
| Alamat | Jl. Margonda No. 99, Depok |
| Jam buka | Senin–Sabtu, 08.00–20.00 WIB |
| WhatsApp | 0898-7651-874 |
