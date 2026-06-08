# FFEINE CLUB Landing Page

Landing page untuk promo free ongkir FFEINE CLUB di Bandung.

## 📋 Deskripsi

Website ini adalah landing page untuk kampanye free ongkir FFEINE CLUB hingga September 2026. Didesain dengan tema classy menggunakan warna ivory putih, dark teal, dan orange.

## 🎨 Fitur

- ✅ Hero section dengan mascot animasi
- ✅ Menu showcase dengan gambar produk
- ✅ Seasonal items section
- ✅ Payment information (QR BCA & Transfer)
- ✅ WhatsApp integration
- ✅ Responsive design (mobile-friendly)
- ✅ Smooth scrolling dan animations
- ✅ Optimized untuk Meta Ads

## 📁 Struktur File

```
ffeine-club-landing/
├── index.html          # Main HTML file
├── style.css           # Styling
├── script.js           # JavaScript interactivity
├── README.md           # Documentation
└── images/             # Folder untuk gambar
    ├── mascot-full.png      # Toucan mascot
    ├─�� MENU.png             # Menu image (490 x 270 mm)
    ├── seasonal-1.png       # Seasonal item 1
    ├── seasonal-2.png       # Seasonal item 2
    └── qr-bca.png           # QR Code BCA
```

## 🚀 Cara Setup

### 1. Upload Gambar

Buat folder `images/` dan upload:
- `mascot-full.png` - Logo/mascot toucan
- `MENU.png` - Menu utama (490 x 270 mm)
- `seasonal-1.png` - Item musiman 1
- `seasonal-2.png` - Item musiman 2
- `qr-bca.png` - QR Code BCA (bisa generate di https://qr-code-generator.com/)

### 2. Deploy ke Vercel

1. Push repository ke GitHub (sudah ada)
2. Buka https://vercel.com
3. Klik "New Project"
4. Connect GitHub account
5. Pilih repository `ffeine-club-landing`
6. Klik "Deploy"
7. Dapatkan URL public (misal: `ffeine-club-landing.vercel.app`)

### 3. Edit Informasi Pembayaran

Di file `index.html`, cari section pembayaran dan update:
```html
<p class="bank-number">No. Rekening: [Masukkan nomor rekening]</p>
<p class="bank-name">Atas Nama: [Masukkan nama]</p>
```

## 🎯 Untuk Meta Ads

Landing page ini sudah dioptimalkan untuk iklan di Facebook/Instagram:
- **Responsive** - terlihat bagus di semua ukuran layar
- **Fast loading** - no heavy libraries
- **Clear CTA** - tombol order dan Whatsapp prominent
- **Trust signals** - payment methods jelas dan menu transparan

### Tips Iklan:
- Highlight: "Free Ongkir Bandung sampai September!"
- Target: Bandung area
- Budget: Mulai dari Rp 50-100k/hari
- Best time: Pagi (6-9am) dan sore (3-6pm)

## 🛠️ Customization

### Ubah Warna
Edit `:root` di `style.css`:
```css
--primary-color: #2c5a7b;      /* Dark teal */
--secondary-color: #ff8c42;    /* Orange */
--ivory-light: #f5f1eb;        /* Ivory */
```

### Ubah WhatsApp Number
Di `index.html`, update link:
```html
<a href="https://wa.me/6282217797270">
```

## 📱 Browser Support

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Mobile browsers ✅

## 📊 Analytics

Untuk tracking, tambahkan Google Analytics ID di `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
```

## 💡 Tips Performa

- Optimize gambar sebelum upload (gunakan TinyPNG atau ImageOptim)
- Gambar menu max 490x270 mm = ~60KB
- Mascot & seasonal items: 100-200KB each
- QR Code: 50KB

## 🤝 Support

Butuh bantuan? Hubungi via WhatsApp: https://wa.me/6282217797270

---

**Created with ❤️ for FFEINE CLUB**
Last updated: June 2026
