# UTS PEMWEB

### Oleh  
## 20230801535 — Anggi Gunawan

---

# PROSES RQ

## Rumpun Ilmu  
**Bisnis Digital / Web Development**

## Deskripsi Penelitian  
Membangun aplikasi web untuk membantu perusahaan layanan internet (ISP) dalam membuat, mengelola, dan mengirim quotation (penawaran harga) kepada calon pelanggan secara online. Sistem ini mempermudah proses pembuatan penawaran, perhitungan biaya, dan pengarsipan quotation.

---

## PICOS

- **P (Platform):**  
  Aplikasi Web untuk pembuatan quotation layanan internet (ISP Quotation System)

- **I (Intervention):**  
  Penggunaan teknologi **Laravel + Filament** dengan multi peran (admin, sales, calon pelanggan) untuk membuat dan mengelola quotation secara digital.

- **C (Comparison):**  
  Proses pembuatan quotation manual menggunakan dokumen Word/Excel, chat, atau email tanpa sistem terintegrasi.

- **O (Outcome):**  
  Sistem web yang memungkinkan pembuatan quotation lebih cepat, otomatis menghitung harga, arsip rapi, serta memudahkan pengelolaan status follow-up quotation.

- **S (Suspect):**  
  Perusahaan / ISP / UMKM penyedia layanan internet yang ingin melakukan transformasi digital pada proses penawaran harga.

---

## Riset Question (RQ)

**RQ1:**  
Bagaimana merancang dan membangun aplikasi web berbasis Laravel dan Filament yang mampu mempermudah proses pembuatan dan pengelolaan quotation layanan internet?

---

## Perkiraan Judul Penelitian

**Pengembangan Sistem Quotation Layanan Internet Berbasis Laravel dan Filament untuk Meningkatkan Efisiensi Proses Penawaran**

---

# SLR

Terlampir file SLR berdasarkan BRD dengan nama file:  
**SLR.pdf**

*(Berisi tinjauan literatur sistematis terkait sistem quotation berbasis web, digitalisasi proses penawaran, penggunaan Laravel dan Filament, serta pengelolaan data calon pelanggan.)*

---

# BRD

Terlampir file BRD berdasarkan SLR dengan nama file:  
**BRD.pdf**

*(Berisi kebutuhan bisnis, ruang lingkup, stakeholder, fitur fungsional & non-fungsional, arsitektur sistem, dan estimasi pengembangan aplikasi.)*

---

# IMPLEMENTASI WEBSITE

### Persiapan Folder & Struktur File

1. `cd /root/boilerplate`
2. `./start.sh uts-pemweb`
3. `cd /root/perkuliahan/uts-pemweb`
4. `cd src`
5. `code .`

### Template Website  
- Template diambil dari:  
  **https://themewagon.com/themes/polk/**

### Membuat Struktur View

6. `cd resource/views`
7. `mkdir layouts && mkdir pages && mkdir partials`

#### Layouts
8. `cd layouts`
9. `touch app.blade.php`

#### Pages
10. `cd ..`
11. `cd pages`
12. `touch home.blade.php`

#### Partials
13. `cd ..`
14. `cd partials`
15. `touch about.blade.php`
16. `touch banner.blade.php`
17. `touch client.blade.php`
18. `touch company.blade.php`
19. `touch contact.blade.php`
20. `touch design.blade.php`
21. `touch footer.blade.php`
22. `touch header.blade.php`
23. `touch new.blade.php`
24. `touch script.blade.php`