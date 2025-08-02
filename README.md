# Website Toko Habib

Website static untuk toko Habib yang menjual baju dan frozen food. Website ini dibuat dengan HTML, CSS, dan JavaScript murni tanpa framework.

## 🛍️ Fitur Utama

- **Responsive Design** - Tampilan yang optimal di desktop, tablet, dan mobile
- **Modern UI/UX** - Desain yang menarik dan user-friendly
- **Smooth Animations** - Animasi scroll dan hover yang halus
- **Google Maps Integration** - Peta lokasi toko yang interaktif
- **Product Gallery** - Galeri produk baju dan frozen food
- **Mobile Navigation** - Menu hamburger untuk tampilan mobile

## 📁 Struktur File

```
toko habib/
├── index.html          # Halaman utama website
├── styles.css          # File CSS untuk styling
├── script.js           # File JavaScript untuk interaktivitas
├── images/             # Folder untuk gambar
│   ├── toko-habib.jpg  # Gambar toko utama
│   ├── baju1.jpg       # Gambar produk baju
│   ├── baju2.jpg       # Gambar produk baju
│   ├── baju3.jpg       # Gambar produk baju
│   ├── baju4.jpg       # Gambar produk baju
│   ├── baju5.jpg       # Gambar produk baju
│   ├── baju6.jpg       # Gambar produk baju
│   ├── frozen1.jpg     # Gambar produk frozen food
│   ├── frozen2.jpg     # Gambar produk frozen food
│   ├── frozen3.jpg     # Gambar produk frozen food
│   ├── frozen4.jpg     # Gambar produk frozen food
│   ├── frozen5.jpg     # Gambar produk frozen food
│   └── frozen6.jpg     # Gambar produk frozen food
└── README.md           # Dokumentasi website
```

## 🎨 Halaman Website

### 1. Beranda (Hero Section)
- Banner utama dengan gradient background
- Call-to-action buttons
- Gambar toko utama

### 2. Tentang Kami
- Informasi tentang toko Habib
- Fitur-fitur unggulan
- Ikon dan deskripsi layanan

### 3. Koleksi Baju
- Grid layout produk baju
- 6 produk baju dengan gambar dan harga
- Hover effects dan animasi

### 4. Frozen Food
- Grid layout produk frozen food
- 6 produk frozen food dengan gambar dan harga
- Background section yang berbeda

### 5. Lokasi
- Informasi kontak toko
- Google Maps embed
- Link langsung ke Google Maps

### 6. Footer
- Link sosial media
- Informasi tambahan
- Copyright

## 🚀 Cara Menjalankan

1. **Download semua file** ke folder lokal
2. **Tambahkan gambar** ke folder `images/` dengan nama yang sesuai
3. **Buka file `index.html`** di browser

### Opsi 1: Buka langsung di browser
```
Double click file index.html
```

### Opsi 2: Menggunakan Live Server (VS Code)
1. Install extension "Live Server"
2. Right click pada `index.html`
3. Pilih "Open with Live Server"

### Opsi 3: Menggunakan Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Kemudian buka `http://localhost:8000`

## 📱 Responsive Design

Website ini responsive dan akan menyesuaikan dengan berbagai ukuran layar:

- **Desktop** (> 768px): Layout penuh dengan sidebar
- **Tablet** (768px - 480px): Layout menyesuaikan
- **Mobile** (< 480px): Layout single column dengan hamburger menu

## 🎯 Fitur JavaScript

- **Mobile Navigation Toggle**
- **Smooth Scrolling**
- **Scroll Animations**
- **Google Maps Integration**
- **Hover Effects**
- **Back to Top Button**
- **Active Navigation Highlighting**
- **Loading Animation**

## 🎨 Customization

### Mengubah Warna
Edit file `styles.css` dan ubah variabel warna:
```css
/* Primary Color */
#3498db

/* Secondary Color */
#667eea

/* Dark Color */
#2c3e50
```

### Mengubah Konten
Edit file `index.html` untuk mengubah:
- Nama toko
- Deskripsi produk
- Harga produk
- Informasi kontak

### Menambah Produk
Untuk menambah produk baru, copy template product card:
```html
<div class="product-card">
    <img src="images/nama-gambar.jpg" alt="Nama Produk" class="product-image">
    <div class="product-info">
        <h3>Nama Produk</h3>
        <p>Deskripsi produk</p>
        <span class="price">Rp 100.000</span>
    </div>
</div>
```

## 📸 Gambar yang Diperlukan

Pastikan Anda memiliki gambar berikut di folder `images/`:

### Gambar Toko
- `toko-habib.jpg` - Gambar utama toko (disarankan 800x600px)

### Gambar Produk Baju
- `baju1.jpg` - Baju Pria Casual
- `baju2.jpg` - Dress Wanita
- `baju3.jpg` - Kaos Anak
- `baju4.jpg` - Celana Jeans
- `baju5.jpg` - Kemeja Formal
- `baju6.jpg` - Hijab Modern

### Gambar Produk Frozen Food
- `frozen1.jpg` - Nugget Ayam
- `frozen2.jpg` - Sosis Premium
- `frozen3.jpg` - Dimsum Frozen
- `frozen4.jpg` - Kentang Goreng
- `frozen5.jpg` - Ikan Salmon
- `frozen6.jpg` - Udang Frozen

**Catatan:** Semua gambar produk disarankan berukuran 400x300px untuk konsistensi.

## 🔧 Troubleshooting

### Gambar Tidak Muncul
- Pastikan nama file gambar sesuai dengan yang ada di HTML
- Periksa path folder `images/`
- Pastikan ekstensi file benar (.jpg, .png, dll)

### Animasi Tidak Berfungsi
- Pastikan JavaScript diaktifkan di browser
- Periksa console browser untuk error
- Pastikan file `script.js` ter-load dengan benar

### Layout Rusak di Mobile
- Pastikan viewport meta tag ada di HTML
- Periksa CSS media queries
- Test di berbagai ukuran layar

## 📞 Support

Jika ada pertanyaan atau masalah, silakan hubungi:
- Email: info@tokohabib.com
- Telepon: +62 21 1234 5678

## 📄 License

Website ini dibuat untuk toko Habib. Semua hak cipta dilindungi.

---

**Dibuat dengan ❤️ untuk Toko Habib** 