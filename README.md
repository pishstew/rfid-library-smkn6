# 📚 Sistem Perpustakaan Berbasis RFID — SMKN 6 Malang

![Status](https://img.shields.io/badge/status-prototyping-orange)
![Sekolah](https://img.shields.io/badge/SMKN%206-Malang-blue)
![Jurusan](https://img.shields.io/badge/SIJA-XII-green)

**🇮🇩 Bahasa Indonesia** | [🇬🇧 English](#-english)

---

## 🇮🇩 Bahasa Indonesia

### Sistem Pencatatan Pengunjung dan Peminjaman Buku untuk Siswa di Perpustakaan SMKN 6 Malang Berbasis RFID

Proyek Uji Kompetensi Keahlian (UPK) Kelas XII SIJA (Sistem Informasi, Jaringan, dan Aplikasi), Program Keahlian Pengembangan Perangkat Lunak dan Gim, SMK Negeri 6 Malang, Tahun Ajaran 2026/2027.

### Latar Belakang

Perpustakaan SMKN 6 Malang melayani sekitar 2.510 siswa, tetapi peminjaman buku masih dicatat manual di spreadsheet. Berdasarkan wawancara dengan petugas perpustakaan (3 November 2026), ada tiga masalah utama:

1. **Status dan stok buku tidak akurat**, karena data diketik manual.
2. **Keterlambatan sulit dilacak**, karena petugas mencocokkan tanggal pinjam satu per satu.
3. **Data tidak bisa diakses atau diperbarui saat internet mati.**

### Solusi

Sistem ini mencatat pengunjung dan peminjaman buku secara otomatis menggunakan teknologi **RFID**. Siswa cukup menempelkan kartu pelajar dan buku ke pembaca, tanpa mengetik data.

- **Kartu pelajar dan buku** diberi stiker RFID, sehingga sekolah tidak perlu mencetak kartu anggota baru.
- **Dua pembaca RFID:** satu di pintu untuk mencatat pengunjung masuk dan keluar, satu di meja petugas untuk mencatat peminjaman dan pengembalian buku.
- **Dashboard web** untuk petugas: stok buku, daftar keterlambatan, riwayat transaksi, dan laporan. Siswa dapat melihat riwayat pinjamannya sendiri.
- **Server lokal sekolah** dengan satu alamat IP, sehingga sistem tetap berjalan di jaringan sekolah meski internet terputus.
- **Denda keterlambatan** mengikuti kebijakan perpustakaan, yaitu menyetor satu buku bacaan, dan dicatat otomatis oleh sistem.

### Cakupan

- Tahap awal difokuskan pada **koleksi buku bacaan**.
- Pengguna yang tercatat adalah **siswa dan guru**.
- Batas waktu pinjam berlaku untuk siswa, sedangkan guru tidak dikenai batas waktu pinjam.

### Status Proyek

🚧 **Tahap prototyping.** Repositori ini disiapkan sebagai tempat kode proyek. Source code akan ditambahkan setelah pengembangan di server sekolah berjalan.

### Cara Menjalankan

*Akan diperbarui setelah proyek di-push ke repositori ini.*

### Tim Penyusun (XII SIJA 2)

| No | Nama | Kelas / Absen |
|----|------|---------------|
| 1 | M. Aqil Naufal | XII SIJA 2 / 02 |
| 2 | Nadia Athanaifa Yuono | XII SIJA 2 / 08 |
| 3 | Nadia Chintia Putri | XII SIJA 2 / 09 |
| 4 | Nafis Achmad Ma'ruf | XII SIJA 2 / 10 |
| 5 | Sanny Aulia Syahrani | XII SIJA 2 / 19 |
| 6 | Shelia Fitri Rahmawati | XII SIJA 2 / 21 |
| 7 | Sofi Wulandari | XII SIJA 2 / 26 |
| 8 | Zakiyah Firdausi Abdillah | XII SIJA 2 / 32 |

### Pembimbing

- KK 1 (Web): Dinda Dwita Arianti, S.Pd.
- KK 2 (Jaringan & Server): Dheni Wibawanto, S.Kom.
- KK 3 (IoT): Nur Halim, S.T., Gr.
- Pembimbing Proposal: Sumirah Butet, M.Pd.

---

## 🇬🇧 English

### RFID-Based Visitor Logging and Book Loan System for Students at SMKN 6 Malang Library

A Competency Skills Examination (UPK) project by Grade XII SIJA (Information Systems, Networks, and Applications), Software and Game Development program, SMK Negeri 6 Malang, academic year 2026/2027.

### Background

The SMKN 6 Malang library serves about 2,510 students, yet book loans are still recorded manually in a spreadsheet. An interview with the librarian (3 November 2026) revealed three main problems:

1. **Inaccurate book status and stock**, because data is typed in by hand.
2. **Overdue returns are hard to track**, as staff must match loan dates one by one.
3. **Data cannot be accessed or updated when the internet is down.**

### Solution

This system records visitors and book loans automatically using **RFID**. Students simply tap their student card and the book on a reader, with no manual typing.

- **Student cards and books** get RFID stickers, so the school does not need to print new membership cards.
- **Two RFID readers:** one at the entrance to log visitors in and out, and one at the librarian's desk to record book loans and returns.
- **Web dashboard** for staff: book stock, overdue list, transaction history, and reports. Students can view their own loan history.
- **School-local server** with a single IP address, so the system keeps running on the school network even when the internet is down.
- **Late penalty** follows library policy, which is donating one reading book, and is recorded automatically.

### Scope

- The initial phase focuses on the **general reading book collection**.
- Registered users are **students and teachers**.
- Loan time limits apply to students, while teachers have no loan time limit.

### Project Status

🚧 **Prototyping phase.** This repository is set up to host the project code. Source code will be added once development on the school server is underway.

### How to Run

*To be updated once the project is pushed to this repository.*

### Team (XII SIJA 2)

See the team table in the Indonesian section above.

### Supervisors

- KK 1 (Web): Dinda Dwita Arianti, S.Pd.
- KK 2 (Networking & Server): Dheni Wibawanto, S.Kom.
- KK 3 (IoT): Nur Halim, S.T., Gr.
- Proposal Advisor: Sumirah Butet, M.Pd.

---

<p align="center">SMK Negeri 6 Malang · 2026</p>
