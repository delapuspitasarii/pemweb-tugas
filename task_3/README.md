## Informasi Pembuat
- **Nama:** Dela Puspita Sari
- **NIM:** 123140080
- **Mata Kuliah / Kelas Praktikum:** Pemrograman Web / RB
- **Dosen Pengampu:** Muhammad Habib Algifari, S.Kom., M.TI.



# Aplikasi Formulir Pendaftaran Mahasiswa Baru & Detail Informasi

## Deskripsi
Aplikasi Formulir Pendaftaran Mahasiswa Baru adalah aplikasi berbasis web sederhana yang dirancang untuk memfasilitasi proses pendaftaran calon mahasiswa secara daring. Aplikasi ini terdiri dari dua halaman utama: halaman formulir pendaftaran (`index.html`) yang dilengkapi dengan validasi otomatis berbasis HTML5 & Regular Expression (Regex), serta halaman detail pendaftar (`detail.html`) yang menyajikan data pendaftaran secara terstruktur dalam bentuk tabel responsif.

- **Tujuan Pembuatan:** Memfasilitasi pendaftaran mahasiswa secara digital dengan antarmuka yang ramah pengguna, memastikan keshahihan data masukan melalui validasi otomatis pada sisi *client*, serta menyajikan ringkasan informasi pendaftaran secara rapi.
- **Studi Kasus:** Sistem pendaftaran mahasiswa baru di lingkungan kampus (ITERA), mencakup pengisian data pribadi (Nama, NIM, Email, Jenis Kelamin, Program Studi, dan Alamat) serta verifikasi status pendaftaran.

## Fitur Utama
1. Formulir pendaftaran interaktif dengan beragam jenis kontrol input (Text, Email, Radio Button, Dropdown Select, dan Textarea)
2. Validasi input otomatis berbasis Regular Expression (Regex) untuk memastikan Nama hanya diisi huruf/spasi dan NIM khusus angka
3. Pengalihan dan pengiriman data formulir ke halaman detail menggunakan metode `GET` via *query string*
4. Penyajian data pendaftaran yang terstruktur menggunakan komponen tabel HTML pada halaman detail
5. Desain antarmuka modern, simetris, dan responsif menggunakan CSS Flexbox, Box Model, serta kombinasi berbagai jenis *selector*

## Screenshot Aplikasi

### Tampilan Utama (State Kosong & Terisi)
![Form Pendaftaran Awal Kosong](<Dokumentasi Aplikasi/Form Pendaftaran Awal (State Kosong).png>)  
*Tampilan awal formulir pendaftaran mahasiswa baru dalam keadaan kosong.*

![Form Pendaftaran Terisi](<Dokumentasi Aplikasi/Form Pendaftaran (State Terisi).png>)  
*Formulir pendaftaran yang telah diisi lengkap dengan data calon mahasiswa.*

### Form Validasi Error
![Error Format Nama](<Dokumentasi Aplikasi/Error Format Nama.png>)  
*Pesan peringatan tooltip saat format input Nama Lengkap mengandung karakter selain huruf dan spasi.*

![Error Format NIM](<Dokumentasi Aplikasi/Error Fomat NIM.png>)  
*Pesan peringatan tooltip saat format input NIM mengandung karakter selain angka.*

### Tampilan Halaman Detail Informasi
![Halaman Detail Informasi Pendaftar](<Dokumentasi Aplikasi/Halaman Detail Informasi Pendaftar.png>)  
*Tampilan tabel ringkasan data pendaftar beserta status verifikasi pada halaman detail.html.*

## Cara Menjalankan Aplikasi
1. Pastikan seluruh file *project* (`index.html`, `detail.html`, `style.css`) berada dalam satu folder yang sama
2. Buka file `index.html` menggunakan peramban web (*web browser*)
3. Isikan data pada formulir pendaftaran lalu klik tombol **Daftar Sekarang** untuk menuju ke halaman `detail.html`

Alternatif lain menggunakan Live Server pada Visual Studio Code:
1. Buka folder *project* di Visual Studio Code
2. *Install extension* **Live Server** jika belum terpasang
3. Klik kanan pada file `index.html`
4. Pilih **Open with Live Server**

## Daftar Fitur yang Telah Diimplementasikan

| No | Fitur | Status | Keterangan |
|---|---|---|---|
| 1 | Pengaturan Form & Method GET | Selesai | Mengarahkan form ke `detail.html` melalui metode `GET` |
| 2 | Validasi Input Nama (Regex) | Selesai | Membatasi input nama hanya huruf dan spasi (`[A-Za-z\s]+`) |
| 3 | Validasi Input NIM (Regex) | Selesai | Membatasi input NIM khusus angka (`[0-9]+`) |
| 4 | Kontrol Input Variatif | Selesai | Menyediakan input text, email, radio button, select dropdown, dan textarea |
| 5 | Tabel Detail Informasi | Selesai | Menampilkan ringkasan data pendaftar secara terstruktur pada `detail.html` |
| 6 | Penataan CSS Selector | Selesai | Menggunakan Element Selector, Class Selector, ID Selector, dan Pseudo-Class |
| 7 | Layout Flexbox | Selesai | Menata posisi kontainer utama agar simetris dan rapi di tengah layar |
| 8 | Styling Box Model | Selesai | Penerapan `padding`, `border-radius`, dan `box-shadow` untuk tampilan *card* modern |
| 9 | Tampilan Responsif | Selesai | Tampilan antarmuka menyesuaikan berbagai ukuran layar perangkat |

