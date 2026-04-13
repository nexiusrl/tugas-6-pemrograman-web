# Kafe Biru - Template Website

## Deskripsi Template

**Kafe Biru** adalah template website sederhana untuk sebuah kafe yang menampilkan informasi tentang:

- **Tentang Kami** - Deskripsi singkat tentang kafe
- **Menu** - Daftar menu makanan dan minuman dengan gambar
- **Jam Operasional** - Jadwal buka kafe
- **Lokasi** - Alamat lokasi kafe

Template ini menggunakan HTML, CSS, dan Bootstrap 5 untuk tampilan yang responsif dan modern.

## Struktur File

```
tugas-6-pemrograman-web/
├── landing-page.html    # Halaman utama Kafe Biru
├── dashboard.html       # Halaman dashboard
├── form.html            # Halaman form
├── login.html           # Halaman login
├── tabel.html           # Halaman tabel
├── css/
│   ├── style.css        # File CSS umum
│   └── style1.css       # File CSS untuk landing page
└── resource/            # Folder untuk asset gambar
    ├── 1IcedCofee.jpg
    ├── Strawberry Matcha Latte .jpg
    └── tahuCrispy.JPG
```

## Perubahan yang Dilakukan

### 3 Perubahan Menggunakan CSS

1. **Header dengan Gradient Background**
   - Mengubah background header dari warna solid `#280872` menjadi linear gradient
   - Menambahkan `box-shadow` untuk efek kedalaman
   - Properti yang digunakan: `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%)` dan `box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3)`

2. **Animasi Hover pada Menu Items**
   - Menambahkan efek animasi saat mouse hover pada item menu
   - Menu item akan membesar (scale) dengan transisi yang halus
   - Properti yang digunakan: `transition: transform 0.3s ease, box-shadow 0.3s ease` dan `transform: scale(1.05)` pada state hover

3. **Text Shadow pada Heading**
   - Menambahkan efek bayangan pada semua judul section (`<h2>`)
   - Memberikan kesan visual yang lebih menarik dan hierarki yang lebih baik
   - Properti yang digunakan: `text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3)`

### 2 Perubahan Menggunakan Bootstrap

1. **Bootstrap Grid System untuk Layout Menu**
   - Mengganti layout manual dengan Bootstrap grid (`row` dan `col-md-4`)
   - Membuat layout 3 kolom yang responsif untuk menu items
   - Menambahkan class `mb-4` untuk margin bottom yang konsisten

2. **Bootstrap Card Component**
   - Mengubah tampilan menu items menjadi Bootstrap cards
   - Menggunakan class: `card`, `card-img-top`, `card-body`, `card-title`, `card-text`, dan `h-100`
   - Memberikan tampilan yang lebih modern dan terstruktur untuk setiap item menu

### Perubahan Tambahan

- **Penambahan Bootstrap 5 CDN** - Menambahkan link Bootstrap 5.3.0 di `<head>` untuk menggunakan komponen Bootstrap
- **Gambar Menu di Tengah** - Menambahkan `display: block` dan `margin: auto` pada gambar menu agar posisinya berada di tengah

## Cara Menjalankan

1. Buka file `landing-page.html` di browser
2. Atau gunakan Live Server di VS Code untuk pengalaman development yang lebih baik

## Teknologi yang Digunakan

- HTML5
- CSS3
- Bootstrap 5.3.0
