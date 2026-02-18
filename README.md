# WormGPT Python Script

Script ini adalah klien terminal berbasis Python untuk berinteraksi dengan persona AI. Script ini menyediakan antarmuka percakapan dengan warna teks yang dapat disesuaikan untuk respons pengguna dan AI.

## Fitur

- Persona AI dengan karakter yang telah ditentukan.
- Antarmuka chat interaktif.
- Warna teks yang dapat disesuaikan untuk kenyamanan membaca.

---

## Prasyarat

Untuk menjalankan script ini, Anda perlu menginstal dependensi berikut:

### Persyaratan Python

- Python 3.6 atau lebih tinggi
- Library Python yang diperlukan:
  - `requests`
  - `colorama`

### Lingkungan yang Didukung

- Termux (Android)
- Terminal Ubuntu
- Terminal Kali Linux

---

## Panduan Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/Danarfr27/WORM-PY.git
cd WORM-PY
```

### 2. Instal Python

Pastikan Python telah terinstal di sistem Anda. Untuk Termux, Ubuntu, atau Kali Linux, gunakan perintah berikut:

#### Termux:

```bash
pkg install python
```

#### Ubuntu/Kali Linux:

```bash
sudo apt update
sudo apt install python3
```

### 3. Instal Library yang Diperlukan

Instal library Python yang diperlukan menggunakan `pip`:

```bash
pip install requests colorama
```

---

## Cara Penggunaan

### 1. Jalankan Script

Untuk memulai script, gunakan perintah berikut:

```bash
python3 worm.py
```

### 2. Berinteraksi dengan AI

- Ketik pesan Anda dan tekan Enter untuk berinteraksi dengan AI.
- Gunakan perintah berikut:
  - `exit` atau `keluar` untuk keluar dari script.
  - `reset` untuk mereset percakapan.

---

## Catatan

- Pastikan Anda memiliki koneksi internet yang stabil karena script ini berinteraksi dengan API eksternal.
- URL API telah ditentukan di dalam script. Perbarui jika diperlukan.

---

## Pemecahan Masalah

### Masalah Umum

1. **Library `requests` tidak ditemukan:**
   - Pastikan Anda telah menginstal library `requests` menggunakan `pip install requests`.

2. **Permission Denied:**
   - Pastikan script memiliki izin eksekusi:
     ```bash
     chmod +x worm.py
     ```

3. **Kesalahan Koneksi:**
   - Periksa koneksi internet Anda.
   - Verifikasi URL API di dalam script.

---

Selamat menggunakan WormGPT!
