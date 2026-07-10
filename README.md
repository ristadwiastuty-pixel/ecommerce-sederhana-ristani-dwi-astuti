# 🍩 Bite Me Bakery — Website E-Commerce

**Maniskan harimu tanpa ragu.**

🔗 **Live Demo:** [https://ristadwiastuty-pixel.github.io/ristani_Bite-me-bakery_ABI-1/](https://ristadwiastuty-pixel.github.io/ristani_Bite-me-bakery_ABI-1/)

---

## 📑 Daftar Isi

1. [Dokumentasi Bisnis](#-bagian-1--dokumentasi-bisnis)
2. [Dokumentasi Teknis](#-bagian-2--dokumentasi-teknis)
3. [Tangkapan Layar](#-tangkapan-layar)
4. [Catatan & Batasan](#️-catatan--batasan-teknis)
5. [Kontak](#-kontak)

---

## 🧁 BAGIAN 1 — Dokumentasi Bisnis

### Profil Usaha

**Bite Me Bakery** adalah usaha rumahan (home bakery) yang bergerak di bidang kuliner, khususnya produksi kue, cookies, dan pastry rumahan dengan kualitas premium namun harga terjangkau. Usaha ini melayani pemesanan secara online melalui website dan media sosial, dengan sistem pemesanan pre-order (PO).

| Keterangan | Detail |
|---|---|
| Nama Usaha | Bite Me Bakery |
| Jenis Usaha | Home Bakery / Kuliner Online |
| Tagline | "Maniskan harimu tanpa ragu" |
| Alamat | Kp. Pongporang, RT 09/RW 04, Ds. Srirahayu, Kec. Cikancung, Kab. Bandung, Jawa Barat 40396 |
| Kontak | 083844266007 (WhatsApp) |
| Email | ristadwiastuty@gmail.com |
| Instagram | [@ristani.da_](https://instagram.com/ristani.da_) |

### Visi

Menjadi bakery rumahan pilihan utama masyarakat yang menghadirkan kue dan jajanan manis berkualitas premium dengan pelayanan yang ramah dan mudah diakses secara online.

### Misi

- Menyediakan produk bakery dengan bahan berkualitas dan rasa yang konsisten.
- Memberikan kemudahan pemesanan melalui platform digital (website).
- Membangun kepercayaan pelanggan melalui pelayanan responsif dan transparansi harga.
- Terus berinovasi mengikuti tren jajanan yang digemari pasar.

### Target Pasar & Segmentasi

- **Demografis**: Remaja hingga dewasa muda (15–35 tahun), mayoritas perempuan, dengan daya beli menengah.
- **Geografis**: Wilayah Kabupaten Bandung dan sekitarnya, dengan potensi pengiriman luar kota melalui jasa kirim.
- **Psikografis**: Konsumen yang menyukai jajanan kekinian (seperti Dubai Chewy Cookie, Cromboloni), gemar memesan online, dan aktif di media sosial (khususnya Instagram).
- **Occasion-based**: Pelanggan yang membutuhkan kue untuk acara khusus (ulang tahun, gathering, hadiah).

### Produk & Harga

| Kategori | Produk | Harga |
|---|---|---|
| Mochi & Cookies | Bite Mochi | Rp 40.000 |
| Mochi & Cookies | Dubai Chewy Cookie 🔥 *Best Seller* | Rp 99.000 |
| Cake & Brownies | Birthday Bite 🔥 *Best Seller* | Rp 200.000 |
| Cake & Brownies | Cromboloni | Rp 50.000 |
| Cake & Brownies | Bite Brownies 🔥 *Best Seller* | Rp 100.000 |
| Cake & Brownies | Bite Lava Cake | Rp 50.000 |
| Pastry | Pie Buah | Rp 35.000 |
| Pastry | Donut | Rp 50.000 |
| Cupcake | Cupcake | Rp 50.000 |

> 

### Keunggulan / Value Proposition

- Produk kekinian dengan cita rasa yang disesuaikan dengan tren pasar (contoh: Dubai Chewy Cookie).
- Sistem pemesanan online yang praktis, tanpa perlu chat manual satu per satu di awal.
- Transparansi harga dan metode pembayaran yang beragam (Cash, QRIS, Transfer Bank, E-Wallet).
- Konfirmasi pembayaran yang terhubung langsung ke WhatsApp toko, mempercepat proses verifikasi pesanan.
- Rating dan ulasan pelanggan yang membangun kepercayaan calon pembeli baru.

### Model Bisnis & Alur Pemesanan

1. Pelanggan membuka website dan menjelajahi katalog produk (bisa memakai fitur pencarian atau kategori di sidebar).
2. Pelanggan menambahkan produk ke keranjang (bisa lebih dari satu jenis produk).
3. Pelanggan mengisi form pemesanan: nama, alamat, username Instagram, dan nomor HP.
4. Pelanggan memilih metode pembayaran (Cash/COD, QRIS, Transfer BNI, atau DANA).
5. Sistem menampilkan rincian pembayaran (nomor rekening/QR code) beserta total tagihan.
6. Pelanggan melakukan pembayaran, lalu mengunggah bukti transfer dan mengirimkannya langsung ke WhatsApp toko melalui tombol yang tersedia.
7. Admin Bite Me Bakery memverifikasi pembayaran dan memproses pesanan.

### Strategi Pemasaran & Branding

- **Branding visual**: tema warna coklat muda yang hangat dan homey, dipadukan dengan font playful/cute agar sesuai dengan citra "bakery rumahan yang menyenangkan".
- **Ciri khas visual**: bentuk katalog produk bulat dengan efek "bite mark" (gigitan) sebagai representasi literal dari nama brand "Bite Me".
- **Media sosial**: Instagram sebagai kanal utama promosi dan showcase produk (foto, testimoni, proses pembuatan).
- **Word of mouth & ulasan**: menampilkan rating dan ulasan pelanggan langsung di website untuk membangun kepercayaan (social proof).
- **Program Best Seller**: menonjolkan produk paling laris (Dubai Chewy Cookie, Birthday Bite, Bite Brownies) di hero banner agar mudah ditemukan pelanggan baru.

---

## 💻 BAGIAN 2 — Dokumentasi Teknis

### Ringkasan Teknologi

Website ini dibangun sebagai **single-page application (SPA)** statis menggunakan:

- **HTML5** — struktur halaman
- **CSS3** (murni, tanpa framework) — styling, layout responsif, animasi transisi
- **JavaScript (Vanilla JS)** — logika interaktif (keranjang, slider, pencarian, modal, dsb.)
- **Google Fonts**: `Baloo 2` (judul, playful) dan `Quicksand` (teks isi)
- Tidak menggunakan backend/server maupun database — seluruh data (keranjang, form) berjalan di sisi client (browser) selama sesi berlangsung
- Gambar produk & QR code pembayaran ditanam langsung ke dalam kode dalam format **base64**, sehingga file tetap satu kesatuan tanpa folder aset terpisah

### Fitur Website

- ✅ Katalog produk berbentuk bulat dengan efek "bite mark" khas branding
- ✅ Rating bintang & ulasan pelanggan di setiap produk
- ✅ Badge **Best Seller** dan deskripsi singkat untuk produk unggulan
- ✅ Hero banner (slider) untuk produk rekomendasi, bisa digeser & diklik langsung ke katalog
- ✅ Search bar dengan auto-scroll & highlight ke produk yang dicari
- ✅ Keranjang belanja (tambah, ubah jumlah, hapus, reset)
- ✅ Form pemesanan (nama, alamat, username Instagram, no HP)
- ✅ 4 metode pembayaran: Cash, QRIS (QR code asli toko), Transfer BNI, E-Wallet DANA
- ✅ Popup rincian pembayaran otomatis (nomor rekening/QR + total tagihan)
- ✅ Upload bukti pembayaran + kirim konfirmasi otomatis ke WhatsApp toko
- ✅ Navigasi kategori di sidebar kiri
- ✅ Bagian kontak (WhatsApp, Email, Instagram, Alamat) yang bisa langsung diklik
- ✅ Tampilan responsif penuh untuk smartphone, tablet, dan desktop

### Struktur File

```
bite-me-bakery.html   → seluruh website (HTML + CSS + JS dalam satu file)
README.md             → dokumen ini
screenshots/          → folder untuk tangkapan layar (buat manual di VS Code)
  ├─ desktop-beranda.png     → tampilan Beranda & Hero Banner (desktop)
  ├─ desktop-katalog.png     → tampilan Katalog Produk (desktop)
  ├─ desktop-keranjang.png   → tampilan Keranjang & Form Pemesanan (desktop)
  ├─ desktop-kontak.png      → tampilan Kontak (desktop)
  ├─ mobile-beranda.png      → tampilan Beranda & Hero Banner (seluler)
  ├─ mobile-katalog.png      → tampilan Katalog Produk (seluler)
  ├─ mobile-keranjang.png    → tampilan Keranjang & Form Pemesanan (seluler)
  └─ mobile-kontak.png       → tampilan Kontak (seluler)
```

### Cara Menjalankan Secara Lokal

1. Buka file `bite-me-bakery.html` langsung di browser (double click), **atau**
2. Gunakan Live Server di VS Code:
   - Install extension **Live Server**
   - Klik kanan pada `bite-me-bakery.html` → **Open with Live Server**

Tidak diperlukan instalasi dependency, Node.js, atau build tool apa pun — murni HTML/CSS/JS statis.

### Cara Deploy

Website ini sudah aktif melalui **GitHub Pages** di:
🔗 [https://ristadwiastuty-pixel.github.io/ristani_Bite-me-bakery_ABI-1/](https://ristadwiastuty-pixel.github.io/ristani_Bite-me-bakery_ABI-1/)

Langkah deploy ulang (jika ada perubahan file):
1. Push perubahan file `bite-me-bakery.html` (atau `index.html`) ke repository GitHub.
2. Masuk ke **Settings → Pages** pada repository.
3. Pastikan source diarahkan ke branch `main` folder `/root` (atau `/docs` jika disesuaikan).
4. Tunggu beberapa menit hingga GitHub Pages selesai mem-build ulang halaman.

**Alternatif hosting statis lain**: Netlify, Vercel, atau Cloudflare Pages — tinggal drag & drop file HTML-nya, tanpa konfigurasi tambahan.

### Panduan Kustomisasi

| Yang ingin diubah | Lokasi di kode |
|---|---|
| Nama produk & harga | Cari tag `<h3>` dan `class="price"` di bagian `<section class="catalog">` |
| Foto produk | Cari `src="data:image/jpeg;base64,..."` pada kartu produk terkait, ganti dengan foto baru (di-encode ke base64) |
| Nomor rekening BNI / DANA | Cari `1980211429` dan `083844266007` di fungsi `goToPayment()` pada `<script>` |
| Gambar QR QRIS | Cari `<img src="data:image/jpeg;base64,..." width="220" alt="QRIS Bite Me Bakery">` di fungsi `goToPayment()` |
| Nomor WhatsApp tujuan konfirmasi | Cari `https://wa.me/6283844266007` di fungsi `sendProofToWhatsapp()` dan bagian kontak |
| Email & Instagram toko | Cari `ristadwiastuty@gmail.com` dan `ristani.da_` di bagian `<section class="contact">` |
| Ulasan pelanggan | Cari `<section class="reviews">` |
| Rating & jumlah ulasan produk | Cari `class="rating"` pada tiap kartu produk |
| Warna tema | Ubah nilai di `:root { --light-brown, --mid-brown, --deep-brown, ... }` pada bagian `<style>` |
| Produk baru | Duplikasi salah satu blok `<div class="product-card">`, sesuaikan `id`, nama, harga, gambar, dan rating |

---

## 📸 Tangkapan Layar

### 1. Beranda & Hero Banner
| Desktop | Seluler |
|---|---|
| ![Beranda Desktop](screenshots/desktop-beranda.png) | ![Beranda Mobile](screenshots/mobile-beranda.png) |

### 2. Katalog Produk
| Desktop | Seluler |
|---|---|
| ![Beranda Desktop](screenshots/desktop-beranda.png) | ![Beranda Mobile](screenshots/mobile-beranda.png) |

### 3. Keranjang 
| Desktop | Seluler |
|---|---|
| ![Katalog Desktop](screenshots/desktop-katalog.png) | ![Katalog Mobile](screenshots/mobile-katalog.png) |

### 4. Form Pemesanan
| Desktop | Seluler |
|---|---|
| ![Keranjang Desktop](screenshots/desktop-keranjang.png) | ![Keranjang Mobile](screenshots/mobile-keranjang.png) |

### 5. Kontak
| Desktop | Seluler |
|---|---|
| ![Kontak Desktop](screenshots/desktop-kontak.png) | ![Kontak Mobile](screenshots/mobile-kontak.png) |



---

## ⚠️ Catatan & Batasan Teknis

- **Fitur kirim bukti WhatsApp**: karena keterbatasan browser, foto bukti transfer **tidak bisa otomatis terlampir** ke chat WhatsApp — ini batasan dari WhatsApp/browser, bukan bug. Setelah tombol "Kirim Bukti ke WhatsApp" diklik, WhatsApp akan terbuka dengan pesan pemesanan otomatis, lalu pelanggan tinggal melampirkan foto secara manual di chat tersebut.
- **Tidak menggunakan localStorage**: data keranjang & form tidak tersimpan permanen — akan kembali kosong jika halaman di-refresh. Ini disengaja agar file tetap ringan dan kompatibel di semua platform hosting statis (termasuk GitHub Pages).
- **Tidak ada backend/database**: seluruh proses pemesanan bersifat semi-manual (konfirmasi akhir tetap melalui WhatsApp), karena website ini murni front-end statis.
- Data rating, ulasan, dan status stok pada produk masih berupa **konten contoh (dummy)** — silakan sesuaikan dengan data asli toko.
- Disarankan untuk mengecek tampilan di berbagai ukuran layar (desktop, tablet, smartphone) setiap kali melakukan perubahan pada kode.

## 🔮 Potensi Pengembangan Selanjutnya

- Integrasi backend/database agar data pesanan tersimpan otomatis (tidak hanya lewat WhatsApp manual).
- Integrasi payment gateway otomatis (Midtrans/Xendit) untuk verifikasi pembayaran real-time.
- Halaman admin untuk mengelola stok, harga, dan status pesanan secara langsung.
- Sistem akun pelanggan agar riwayat pesanan tersimpan.

---

## 📞 Kontak

- WhatsApp: [083844266007](https://wa.me/6283844266007)
- Email: [ristadwiastuty@gmail.com](mailto:ristadwiastuty@gmail.com)
- Instagram: [@ristani.da_](https://instagram.com/ristani.da_)
- Alamat: Kp. Pongporang, RT 09/RW 04, Ds. Srirahayu, Kec. Cikancung, Kab. Bandung, Jawa Barat 40396
- Live Website: [ristadwiastuty-pixel.github.io/ristani_Bite-me-bakery_ABI-1](https://ristadwiastuty-pixel.github.io/ristani_Bite-me-bakery_ABI-1/)

---
*Dibuat dengan 🤎 oleh Bite Me Bakery — Maniskan harimu tanpa ragu!*
