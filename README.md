# Kafe Biru - Template Website Tugas 6 Pemrograman Web

## Deskripsi Repository
**Repository ini** dibuat untuk memenuhi tugas matakuliah Pemrograman Web.
- **Nama** : Muhammad Dzul Hannan
- **Kelas** : B
- **Tugas** : 6

## Perubahan yang Dilakukan

### 5 Perubahan Menggunakan CSS

1. **Header dengan Gradient Background**
   - Mengubah background header dari warna solid `#280872` menjadi linear gradient
   - Menambahkan `box-shadow` untuk efek kedalaman
   - Properti yang digunakan: `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%)` dan `box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3)`
   ```
   header {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: #fff;
      padding: 10px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
   }
   ```

2. **Animasi Hover pada Menu Items**
   - Menambahkan efek animasi saat mouse hover pada item menu
   - Menu item akan membesar (scale) dengan transisi yang halus
   - Properti yang digunakan: `transition: transform 0.3s ease, box-shadow 0.3s ease` dan `transform: scale(1.05)` pada state hover
   ```
   .menu-item {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
   }
   .menu-item:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
   }
   ```

3. **Text Shadow pada Heading**
   - Menambahkan efek bayangan pada semua judul section (`<h2>`)
   - Memberikan kesan visual yang lebih menarik dan hierarki yang lebih baik
   - Properti yang digunakan: `text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3)`
   ```
   section h2 {
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
   }
   ```

4. **Footer dengan Gradient Background**
   - Mengubah background footer dari warna solid `#280872` menjadi linear gradient
   - Menambahkan `box-shadow` untuk efek kedalaman
   - Properti yang digunakan: `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%)` dan `box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3)`
   ```
   footer {
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      color: #fff;
      padding: 10px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
   }
   ```

5. **Login page**
   - Mengganti background dari warna solid `#280872` menjadi linear gradient
   - Menambahkan `border-radius` untuk efek rounded
   - Properti yang digunakan: `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);` dan `border-radius: 10px;`
    ```
   body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0;
      min-height: 100vh;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
   }
   .login-box {
      margin-top: 150px;
      flex-basis: 400px;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
   }
   input, select {
      width: 100%;
      padding: 15px 20px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 10px;
   }
   ```

### 2 Perubahan Menggunakan Bootstrap

1. **Bootstrap Grid System untuk Layout Menu**
   - Mengganti layout manual dengan Bootstrap grid (`row` dan `col-md-4`)
   - Membuat layout 3 kolom yang responsif untuk menu items
   - Menambahkan class `mb-4` untuk margin bottom yang konsisten

2. **Bootstrap Card Component**
   - Mengubah tampilan menu items menjadi Bootstrap cards
   - Menggunakan class: `card`, `card-img-top`, `card-body`, `card-title`, `card-text`, dan `h-100`
   - Memberikan tampilan yang lebih modern dan terstruktur untuk setiap item menu
