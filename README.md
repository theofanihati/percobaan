# 🧪 Airbnb.com Web Testing Project – Kelompok F4

![Airbnb Logo](./public/img/airbnblogo.png)

Selamat datang di repository pengujian aplikasi web **Airbnb**! Proyek ini dilakukan oleh **Kelompok F4** sebagai bagian dari studi dan praktik pengujian perangkat lunak, dengan fokus pada aplikasi **Airbnb versi web (v25.22)**. Pengujian mencakup metode **manual** dan **automated** untuk memastikan kualitas dan konsistensi fitur-fitur utama.

---

## 👥 Anggota Kelompok F4

| Nama Lengkap                         | NIM          | Peran         |
|-------------------------------------|--------------|----------------|
| Fadhil Abdul Fattah                 | 2215061019   | Ketua Kelompok |
| Arnora Mardiansyah                  | 2215061015   | Anggota        |
| Laurentius Nicholas Christmarines  | 2215061059   | Anggota        |
| Theofani Hati Kusumawardani        | 2255061004   | Anggota        |

---

## 🏢 Informasi Umum

Airbnb adalah platform online global yang menghubungkan pemilik properti dengan penyewa, baik untuk jangka pendek maupun panjang. Layanan ini memungkinkan pengguna menjadi **host** atau **guest**, dalam sistem ekonomi berbagi modern.

| Elemen        | Deskripsi                                          |
|---------------|----------------------------------------------------|
| Nama Aplikasi | Airbnb (Web) v25.22                                |
| URL           | [https://www.airbnb.com](https://www.airbnb.com)  |
| Kantor Pusat  | San Francisco, California, Amerika Serikat         |
| Pendiri       | Brian Chesky, Joe Gebbia, Nathan Blecharczyk       |

---

## 🔍 Jenis Pengujian

### 1. Manual Testing
Dilakukan untuk memeriksa:
- Pencarian & Penemuan Properti
- Manajemen Pengguna
- Detail Properti
- Customer Support  
Fokus pada interaksi UI/UX, validasi input, dan alur pengguna.

### 2. Automated Testing
Menggunakan:
- **Selenium IDE**
- **TestCase Studio (Chrome Extension)**  
Automasi untuk skenario **end-to-end** pada fitur inti, dengan tujuan efisiensi dan konsistensi.

---

## 💻 Lingkungan Pengujian

### Hardware:
- **Server Pengujian**: Terpisah dari lingkungan produksi
- **Client**: PC, Mac, dan perangkat mobile (fisik & emulator)

### Software:
- **OS**: Windows 10, macOS Ventura/Sonoma, Linux
- **Browser**: Chrome, Firefox, Edge, Safari
- **Tools Pendukung**: IDE, GitHub, VPN, Browser Extension

---

## 🧰 Tools yang Digunakan

| Kategori            | Tools                                   |
|---------------------|-----------------------------------------|
| Automation Tools    | Selenium IDE, Selenium WebDriver        |
| Communication Tools | Discord                                  |
| Web Extensions      | TestCase Studio                         |
| VCS (Version Control)| GitHub                                  |

---

## 📎 Dokumen Terkait

- 📄 [System Requirements](#)
- 📄 [Test Strategy](#)
- 📄 [Test Plan](#)
- 📄 [Test Scenario](#)
- 📄 [Test Case](#)

---

## 🚨 Masalah yang Ditemukan

1. OTP tetap dikirim meskipun nomor telepon tidak valid.
2. Rating properti tidak ditampilkan pada card hasil pencarian.
3. Hasil pencarian tidak konsisten dengan input filter.

---

## ✅ Rekomendasi Perbaikan

- **Validasi nomor telepon** lebih ketat sebelum pengiriman OTP.
- Tampilkan **rating properti** langsung di card pencarian.
- Pastikan **filter dan hasil pencarian** sinkron secara akurat.

---

## 📌 Tujuan Proyek

Meningkatkan kualitas dan keandalan situs Airbnb melalui praktik pengujian yang terstruktur, dengan pendekatan manual dan otomatis, untuk menciptakan pengalaman pengguna yang lebih baik.

---

> 🔧 Proyek ini dibuat sebagai bagian dari pembelajaran pengujian perangkat lunak dan pengembangan kualitas sistem berbasis web.

