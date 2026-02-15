# 🎓 SISTEM PAKAR PENENTUAN JURUSAN KULIAH

## React.js - Metode Certainty Factor (CF)

---

## ✨ INSTALASI SUPER MUDAH - 3 LANGKAH!

### 📥 **Langkah 1: Extract Folder**
```
Klik kanan file ZIP → Extract All
Pilih lokasi → Extract
```

### 📦 **Langkah 2: Install Dependencies**
```bash
# Buka folder di terminal/command prompt
cd sistem-pakar-jurusan-react-complete

# Install
npm install
```

### 🚀 **Langkah 3: Jalankan Aplikasi**
```bash
npm run dev
```

**Browser otomatis terbuka di:** `http://localhost:3000`

---

## ✅ SUDAH TERMASUK:

- ✅ **20 Kriteria** lengkap dengan CF pakar
- ✅ **8 Jurusan** dengan icon, deskripsi, prospek karir
- ✅ **40+ Rules** mapping kriteria-jurusan
- ✅ **Logika CF** lengkap (perhitungan + kombinasi)
- ✅ **Landing Page** modern
- ✅ **Form Data Diri** dengan validasi
- ✅ **Kuesioner Interaktif** dengan slider CF user
- ✅ **Hasil Rekomendasi** TOP 3 + ranking
- ✅ **Detail Perhitungan** step-by-step
- ✅ **Print PDF** hasil konsultasi
- ✅ **Responsive** mobile-friendly
- ✅ **CSS Lengkap** sudah rapi

---

## 🎯 FITUR UTAMA:

### 1. **Landing Page**
- Hero section dengan CTA
- Features & benefits
- How it works
- Statistics

### 2. **Konsultasi**
- **Data Diri**: Nama, sekolah, gender
- **Kuesioner**: 20 pertanyaan interaktif
  - Pilih Ya/Tidak
  - Slider tingkat keyakinan (20%-100%)
  - Progress bar real-time
  - Pagination 5 pertanyaan/halaman

### 3. **Hasil**
- **Winner Card**: Jurusan terbaik dengan:
  - Icon & nama jurusan
  - Persentase kecocokan
  - Status (Sangat Cocok/Cocok/dll)
  - Rekomendasi aksi
  - Prospek karir lengkap
- **TOP 3 Ranking** dengan visual menarik
- **Tabel Lengkap** semua 8 jurusan

### 4. **Detail Perhitungan**
- CF per kriteria
- CF pakar × CF user
- Kombinasi CF step-by-step
- Formula matematika jelas

---

## 📊 DATA YANG TERSEDIA:

### 20 Kriteria (G01-G20):
1. ✅ Suka matematika dan logika (CF: 0.80)
2. ✅ Suka menganalisis (CF: 0.90)
3. ✅ Kreatif dan imajinatif (CF: 0.85)
4. ✅ Suka berbicara di depan umum (CF: 0.70)
5. ✅ Teliti (CF: 0.80)
... (15 kriteria lagi)

### 8 Jurusan Lengkap:
1. 💻 **Teknik Informatika** - Software Dev, Data Scientist, dll
2. 💼 **Manajemen** - Manager, Entrepreneur, dll
3. 📊 **Akuntansi** - Akuntan, Auditor, dll
4. 📚 **Pendidikan** - Guru, Dosen, dll
5. 🎨 **Desain Komunikasi Visual** - UI/UX Designer, dll
6. 🏗️ **Teknik Sipil** - Civil Engineer, dll
7. 🧠 **Psikologi** - Psikolog, HR, dll
8. ⚖️ **Hukum** - Pengacara, Notaris, dll

---

## 🧠 METODE CERTAINTY FACTOR

### Formula:
```
CF[H,E] = CF_pakar × CF_user
CF_combine = CF_old + CF_new × (1 - CF_old)
```

### Contoh:
User jawab YA untuk:
- G01 (Matematika) dengan keyakinan 80% → CF = 0.80 × 0.80 = 0.64
- G02 (Analisis) dengan keyakinan 90% → CF = 0.90 × 0.90 = 0.81
- Kombinasi → CF_combine = 0.64 + 0.81 × (1 - 0.64) = 0.93

---

## 📁 STRUKTUR FOLDER:

```
sistem-pakar-jurusan-react-complete/
├── src/
│   ├── data/
│   │   ├── kriterias.js      (20 kriteria)
│   │   ├── jurusans.js        (8 jurusan)
│   │   └── rules.js           (40+ rules)
│   ├── utils/
│   │   └── certaintyFactor.js (Logika CF)
│   ├── pages/
│   │   ├── Home.jsx           (Landing page)
│   │   ├── DataDiri.jsx       (Form data)
│   │   ├── Kuesioner.jsx      (20 pertanyaan)
│   │   ├── Hasil.jsx          (Rekomendasi)
│   │   ├── DetailPerhitungan.jsx
│   │   ├── Tentang.jsx
│   │   └── DaftarJurusan.jsx
│   ├── App.jsx                (Main app)
│   ├── App.css                (All styles)
│   └── main.jsx               (Entry point)
├── package.json
├── vite.config.js
└── index.html
```

---

## 🔧 TROUBLESHOOTING:

### ❌ Error: npm not found
**Solusi:**
```
1. Download Node.js: https://nodejs.org
2. Install seperti biasa
3. Restart terminal
4. Cek: npm --version
```

### ❌ Error: Cannot find module
**Solusi:**
```bash
# Hapus node_modules dan install ulang
rm -rf node_modules
npm install
```

### ❌ Port 3000 sudah digunakan
**Solusi:**
```bash
# Edit vite.config.js
# Ganti port: 3000 ke 3001 atau port lain
```

### ❌ Error saat npm install
**Solusi:**
```bash
# Gunakan --legacy-peer-deps
npm install --legacy-peer-deps
```

---

## 🚀 BUILD UNTUK PRODUCTION:

```bash
# Build
npm run build

# Folder hasil: dist/

# Preview build
npm run preview

# Upload folder dist/ ke:
# - Netlify (gratis)
# - Vercel (gratis)  
# - GitHub Pages (gratis)
```

---

## 🎓 UNTUK SKRIPSI:

### BAB 1: Latar Belakang
> "Banyak siswa SMA bingung memilih jurusan kuliah yang sesuai. Sistem pakar dengan metode Certainty Factor dapat memberikan rekomendasi berdasarkan minat, bakat, dan kepribadian..."

### BAB 2: Landasan Teori
- **Sistem Pakar**: Definisi, karakteristik, komponen
- **Certainty Factor**: Formula, cara kerja, kelebihan
- **React.js**: SPA, Virtual DOM, Component-based

### BAB 3: Analisis & Perancangan
- Use Case Diagram (User & System)
- Flowchart konsultasi
- Struktur data (kriteria, jurusan, rules)
- Component architecture

### BAB 4: Implementasi
- Source code React
- Screenshot semua halaman
- Contoh perhitungan CF manual
- Testing hasil

### BAB 5: Testing & Evaluasi
- Testing fungsional
- User Acceptance Test
- Perbandingan hasil dengan pakar

---

## 💡 PENJELASAN KE DOSEN:

**Q: Kenapa pakai React?**
> "React dipilih karena modern, cepat (SPA), dan mudah maintenance dengan component-based architecture."

**Q: Dimana data disimpan?**
> "Data kriteria, jurusan, dan rules di-hardcode di file JavaScript. Hasil konsultasi disimpan di React state (session-based)."

**Q: Bagaimana perhitungan CF?**
> "Ada utility function `certaintyFactor.js` yang mengimplementasikan formula CF: CF[H,E] = CF_pakar × CF_user dan kombinasi dengan CF_combine = CF_old + CF_new × (1 - CF_old)"

**Q: Kenapa tidak pakai database?**
> "Untuk kemudahan deployment dan karena data bersifat statis (tidak sering berubah). Bisa ditambahkan Firebase/MongoDB jika perlu."

---

## ✅ CHECKLIST INSTALASI:

- [ ] Download & extract folder
- [ ] Install Node.js (jika belum)
- [ ] Buka terminal di folder project
- [ ] Run: `npm install`
- [ ] Run: `npm run dev`
- [ ] Buka browser: http://localhost:3000
- [ ] Test semua fitur
- [ ] Sukses! 🎉

---

## 📞 BANTUAN:

Jika ada error:
1. Screenshot error nya
2. Cek console (F12 di browser)
3. Pastikan Node.js sudah terinstall
4. Coba hapus `node_modules` dan `npm install` ulang

---

## 📄 LICENSE:

Project ini dibuat untuk keperluan akademis/skripsi.

---

**Developed with ❤️ using React.js + Vite**

**GOOD LUCK DENGAN SKRIPSIMU! 🚀📚**
