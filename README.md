# 📓 X Journal

> *Journaling app yang aman, privat, dan menawan untuk mencatat perjalanan hidupmu.*

![X Journal](https://img.shields.io/badge/X%20Journal-v1.0-blueviolet?style=for-the-badge)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-success?style=for-the-badge)
![Offline](https://img.shields.io/badge/Mode-Offline%20First-blue?style=for-the-badge)

---

## ✨ Fitur Unggulan

| Fitur | Deskripsi |
|-------|-----------|
| 🔒 **100% Privat** | Data tersimpan lokal di perangkat (IndexedDB), tidak ada yang terkirim ke server |
| 📱 **PWA Ready** | Install sebagai aplikasi native di Android & iOS |
| 🎨 **Tema Eksklusif** | 7 gradient + 27 background gambar alam & kota |
| 😊 **Mood Tracking** | Pilih emoji untuk setiap entry |
| 📊 **Statistik Lengkap** | Analisis journaling habit dengan visualisasi menarik |
| 🔗 **Auto Link** | URL otomatis jadi button yang bisa diklik |
| 📤 **Export/Import** | Backup & restore data dalam format JSON |
| 🎭 **Onboarding Template** | 4 persona template untuk memulai cepat |

---

## 🚀 Cara Menggunakan

### 1. Buka Langsung di Browser
```
Buka file: x-journal.html
```

### 2. Install sebagai Aplikasi (PWA)
1. Buka di Chrome/Safari
2. Klik menu **⋮** → "Install" / "Add to Home Screen"
3. Nikmati pengalaman fullscreen!

### 3. Gunakan Template Data (Onboarding)
Saat pertama kali membuka, pilih salah satu persona:
- 🎓 **Mahasiswa** - Jurnal kuliah, skripsi, hijrah
- 💼 **Profesional** - Karir, keluarga, investasi syariah
- 🛍️ **Emak Olshop** - Bisnis online, parenting, komunitas
- 💻 **Emak Digital Creator** - Produk digital, marketing, Lynk.id

---

## 📱 Screenshot

### Empty State & Onboarding
```
┌─────────────────────────────┐
│            📖               │
│   Mulai Perjalananmu        │
│                             │
│  [📦 Pilih Template]        │
└─────────────────────────────┘
```

### Journaling Interface
```
┌─────────────────────────────┐
│ 📓 X Journal           [👤] │
├─────────────────────────────┤
│ 📝 My Journal      [+]  [▼] │
│ • Entry 1 (😊)              │
│ • Entry 2 (🤔)              │
├─────────────────────────────┤
│ 😊😢😡🤔🥰😴🤩😎🤯           │
│ [Tulis entry di sini...]    │
│ [    + Add Entry    ]       │
└─────────────────────────────┘
```

---

## 📦 File dalam Repository

```
repo/kimi/
├── 📄 x-journal.html           # Aplikasi utama (single file)
├── 📄 README.md                # Dokumentasi ini
├── 📊 dummy-data-mahasiswa.json   # Template: Mahasiswa
├── 📊 dummy-data-profesional.json # Template: Profesional
├── 📊 dummy-data-emak-olshop.json # Template: Emak Olshop
├── 📊 dummy-data-emak-lynk.json   # Template: Emak Digital Creator
├── 👦 miqdad-playful.html      # Portfolio: Playful Visionary
└── 👔 miqdad-portfolio.html    # Portfolio: Professional
```

---

## 🔧 Tech Stack

- **Frontend**: HTML5, Tailwind CSS (CDN)
- **Database**: IndexedDB (browser local storage)
- **Animation**: Framer Motion (via CDN)
- **Icons**: Heroicons
- **Fonts**: Plus Jakarta Sans

---

## 💾 Data & Privasi

```
✅ Data tersimpan 100% di perangkat
✅ Tidak ada akun/login yang diperlukan
✅ Export JSON untuk backup
✅ Import JSON untuk restore
```

---

## 🎯 Keyboard Shortcuts

| Shortcut | Aksi |
|----------|------|
| `Enter` | Buat jurnal baru (saat input focus) |

---

## 🐛 Troubleshooting

### PWA Install Tidak Muncul?
- Pastikan dibuka via HTTPS atau localhost
- Chrome memblokir PWA install dari file:// (file lokal)
- Solusi: Upload ke GitHub Pages / Netlify

### Data Hilang?
- Gunakan menu **Database → Export** secara rutin
- Backup file `.json` ke cloud storage

---

## 🤝 Kontribusi

Pull request & saran sangat diterima!

---

## 📄 Lisensi

MIT License - Bebas digunakan, dimodifikasi, dan didistribusikan.

---

## 🙏 Credits

Dibuat dengan ❤️ oleh **Arief Rachmansyah**

- 🌐 Website: [slugpost.com/arief-rachmansyah](https://slugpost.com/arief-rachmansyah)
- 📸 Instagram: [@arief.drip](https://instagram.com/arief.drip)

---

> *"Setiap entry adalah investasi untuk pemahaman diri yang lebih baik."*
