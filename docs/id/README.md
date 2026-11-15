![BrowserMirrorAgents](../../assets/banner.png)

# BrowserMirrorAgents

**Hubungkan OpenCode dan Codex ke agen AI berbasis browser.**

BrowserMirrorAgents adalah lapisan integrasi yang dihosting sendiri yang menghubungkan alat pengkodean AI ke layanan AI berbasis browser.

Gunakan lingkungan pengkodean AI favorit Anda dengan Bitrix24, Qwen, dan DeepSeek melalui sesi browser yang ada — tanpa perlu membeli kunci API terpisah untuk setiap penyedia.

[🌐 Situs Web Resmi](https://agent.p5g.ru/)

---

## 🚀 Integrasi yang Didukung

### Alat Pengkodean AI

| Integrasi | Status |
|---|---|
| OpenCode | Didukung |
| Codex | Didukung |

### Penyedia AI Berbasis Browser

| Penyedia | Dukungan |
|---|---|
| Bitrix24 | Didukung |
| Qwen | Didukung |
| DeepSeek | Didukung |
| Google AI | Didukung |

---

## ✨ Mengapa BrowserMirrorAgents?

- **Tidak perlu kunci API terpisah** — gunakan sesi browser daripada membeli akses API individual.
- **Banyak penyedia AI** — hubungkan ke berbagai layanan AI berbasis browser.
- **Integrasi OpenCode** — gunakan agen AI berbasis browser dalam alur kerja OpenCode Anda.
- **Integrasi Codex** — hubungkan Codex ke layanan AI browser yang didukung.
- **Dihosting sendiri** — jalankan aplikasi di server Anda sendiri.
- **Penyebaran Docker** — instalasi sederhana menggunakan Docker Compose.
- **Pembayaran satu kali** — tidak ada langganan berulang.

## 🔌 Cara Kerjanya

BrowserMirrorAgents bertindak sebagai lapisan integrasi antara alat pengkodean AI dan layanan AI berbasis browser.

1. Terapkan BrowserMirrorAgents di server Anda.
2. Hubungkan sesi AI berbasis browser Anda.
3. Konfigurasikan OpenCode atau Codex.
4. Mulai bekerja dengan penyedia AI yang didukung.

Akses aktual, batas penggunaan, dan ketersediaan Anda bergantung pada penyedia AI yang bersangkutan dan sesi browser Anda.

---

## 🐳 Instalasi

Terapkan BrowserMirrorAgents menggunakan Docker.

Ganti `YOUR_LICENSE_KEY` dengan kunci lisensi pribadi Anda yang diterima setelah pembelian.

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

Setelah kontainer berjalan, buka:

**[http://localhost:8000](http://localhost:8000)**

Selesai! BrowserMirrorAgents siap digunakan.

---

## 💳 Harga

### $18.88 — Pembayaran satu kali

- Pembelian lisensi satu kali
- Tidak ada langganan bulanan
- Tidak ada pembayaran berulang
- Penyebaran yang dihosting sendiri

[Dapatkan Lisensi Anda](https://agent.p5g.ru/)

## 🌍 Dukungan Multibahasa

BrowserMirrorAgents mendukung 21 bahasa:
- [English](../../README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [Italiano](../it/README.md)
- [简体中文](../zh_CN/README.md)
- [繁體中文](../zh_TW/README.md)
- [Português (Brasil)](../pt_BR/README.md)
- [日本語](../ja/README.md)
- [한국어](../ko/README.md)
- [العربية](../ar/README.md)
- [हिन्दी](../hi/README.md)
- [Türkçe](../tr/README.md)
- [Bahasa Indonesia](README.md)
- [Polski](../pl/README.md)
- [Tiếng Việt](../vi/README.md)
- [ไทย](../th/README.md)
- [Nederlands](../nl/README.md)
- [Svenska](../sv/README.md)
- [Norsk](../no/README.md)
- [Русский](../ru/README.md)

## 🤖 Pemantauan Antarmuka Berbasis AI

**Jangan khawatir tentang perubahan antarmuka. Kami memantaunya untuk Anda.**

Pemantauan berbasis AI berjalan di sisi kami, melacak perubahan dalam layanan AI yang didukung dan antarmuka browser mereka.

Ketika elemen antarmuka atau pemilih berubah, sistem kami mendeteksi pembaruan dan menerbitkan pemilih yang diperbarui serta penyesuaian kompatibilitas hampir segera.

- **Pemantauan berkelanjutan** — antarmuka yang didukung dipantau secara teratur.
- **Deteksi berbasis AI** — perubahan diidentifikasi secara otomatis.
- **Pembaruan cepat** — pemilih yang diperbarui dan penyesuaian antarmuka diterbitkan dengan cepat.
- **Lebih sedikit perawatan** — tidak perlu melacak perubahan antarmuka secara manual atau terus-menerus memperbarui pemilih sendiri.

**Kami memantau antarmuka. Anda fokus pada pekerjaan Anda.**

## 💬 Komunitas & Dukungan

Repositori ini adalah tempat pusat untuk melaporkan masalah, mendiskusikan masalah, dan berbagi solusi terkait BrowserMirrorAgents.

Anda dipersilakan untuk:

- **Melaporkan bug** — buat issue jika Anda mengalami perilaku yang tidak diharapkan atau kesalahan.
- **Meminta fitur** — sarankan perbaikan dan integrasi baru.
- **Mendiskusikan solusi** — bagikan ide, solusi sementara, dan solusi dengan pengguna lain.
- **Mengajukan pertanyaan** — diskusikan konfigurasi, kompatibilitas, dan penggunaan.
- **Melacak pembaruan** — ikuti diskusi tentang perbaikan, peningkatan, dan perubahan kompatibilitas.

Sebelum membuat issue baru, silakan periksa issue yang ada untuk menghindari duplikat.

**Menemukan masalah? Buka issue dan mari kita selesaikan bersama!**

---

## ❓ FAQ

### Apakah saya perlu kunci API terpisah?

Tidak. BrowserMirrorAgents dirancang untuk bekerja melalui sesi browser yang ada, jadi Anda tidak perlu membeli kunci API terpisah untuk setiap penyedia yang didukung.

### Alat pengkodean AI mana yang didukung?

OpenCode dan Codex.

### Penyedia AI mana yang didukung?

Bitrix24, Qwen, DeepSeek, Google AI.

### Bisakah saya menghostingnya di server saya sendiri?

Ya. BrowserMirrorAgents didistribusikan sebagai image Docker dan dapat diterapkan menggunakan Docker Compose.

### Apakah ada biaya bulanan?

Tidak. BrowserMirrorAgents tersedia dengan pembelian lisensi satu kali.

### Apakah layanan AI tidak terbatas?

Penggunaan tergantung pada ketersediaan, kebijakan, dan batas setiap penyedia AI dan sesi browser Anda.

Anda juga dapat menghubungkan beberapa akun browser dan beralih antar sesi, tunduk pada ketentuan layanan masing-masing penyedia.

---

## 🔗 Tautan

- **Situs web:** https://agent.p5g.ru/
- **Lisensi:** Tersedia di situs web resmi.
- **Dukungan:** Informasi kontak tersedia di situs web resmi.

---

## ⚖️ Penyangkalan

BrowserMirrorAgents adalah produk perangkat lunak independen dan tidak berafiliasi, didukung, atau secara resmi terkait dengan OpenAI, OpenCode, Bitrix24, Alibaba Cloud, DeepSeek, atau pemilik masing-masing.

Semua nama produk pihak ketiga dan merek dagang adalah milik pemilik masing-masing.

Penggunaan layanan AI pihak ketiga tunduk pada ketentuan layanan, kebijakan, dan batasan penggunaan masing-masing.

---

**BrowserMirrorAgents**

*Satu lapisan integrasi. Banyak agen AI berbasis browser.*
