# 🌷 Form Registrasi Seminar Teknologi 2026

Project **Form Registrasi Seminar Teknologi 2026** merupakan aplikasi pendaftaran seminar berbasis web yang dibuat untuk memenuhi tugas praktikum Desain Web. Aplikasi ini menggunakan HTML dan CSS untuk membangun struktur serta tampilan form pendaftaran.

Form ini dirancang agar peserta dapat mengisi data diri, memilih kategori peserta, menentukan sesi seminar, hingga mengunggah dokumen identitas.

## ✨ Fitur Aplikasi

Beberapa komponen yang tersedia dalam form pendaftaran ini, yaitu:

- **Nama Lengkap:** Mengisi nama peserta seminar.
- **Email:** Memasukkan alamat email aktif.
- **Nomor HP:** Mengisi nomor telepon peserta.
- **Pilihan Program Studi:** Memilih program studi yang tersedia.
- **Radio Button:** Menentukan jenis peserta.
- **Checkbox:** Memilih topik seminar yang diminati.
- **Select Option:** Memilih sesi seminar.
- **Textarea:** Menuliskan alasan mengikuti seminar.
- **File Upload:** Mengunggah dokumen identitas dalam format PDF.
- **Persetujuan:** Konfirmasi persetujuan sebelum mengirim formulir.

## 🛠️ Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| HTML5 | Membuat struktur dan elemen form |
| CSS3 | Mengatur tampilan, warna, dan tata letak |
| Browser | Menampilkan dan menjalankan halaman web |

## 📁 Struktur Folder

```text
Tugas Pertemuan 8/
│
├── index.html
├── css/
│   └── style.css
├── ss/
│   └── (screenshot hasil aplikasi)
└── README.md
```

Keterangan:
- `index.html` berisi struktur halaman dan elemen form.
- `css/style.css` digunakan untuk mengatur desain dan tampilan aplikasi.
- `ss/` merupakan folder untuk menyimpan screenshot hasil pengerjaan.
- `README.md` berisi penjelasan mengenai project.

## 📋 Ketentuan Form dan Validasi

Form pendaftaran memiliki beberapa ketentuan pengisian agar data yang dimasukkan sesuai, di antaranya:

1. Nama lengkap wajib diisi minimal 3 karakter.
2. Email harus menggunakan format yang valid.
3. Nomor HP wajib diisi dengan 10–13 digit angka.
4. Program studi harus dipilih.
5. Jenis peserta wajib ditentukan.
6. Sesi seminar harus dipilih.
7. Alasan mengikuti seminar wajib diisi minimal 20 karakter.
8. Dokumen identitas wajib diunggah dalam format PDF.
9. Peserta harus mencentang persetujuan sebelum mengirim formulir.

## 🚀 Cara Menjalankan Aplikasi

Berikut langkah-langkah untuk menjalankan project:

1. Download atau clone repository project.
2. Buka folder project melalui Visual Studio Code.
3. Cari file `index.html`.
4. Klik kanan pada file tersebut, lalu pilih **Open with Live Server** atau buka langsung menggunakan browser.
5. Form registrasi akan ditampilkan dan siap digunakan.

## 🧪 Pengujian Form

Pengujian dilakukan dengan memasukkan data yang tidak sesuai untuk melihat apakah browser dapat mendeteksi kesalahan pada form.

| No. | Skenario Pengujian | Hasil yang Diharapkan |
|---|---|---|
| 1 | Nama lengkap dikosongkan | Form menampilkan peringatan bahwa nama wajib diisi |
| 2 | Email menggunakan format tidak valid | Form menolak format email tersebut |
| 3 | Nomor HP kurang dari 10 digit | Form menolak nomor yang tidak sesuai ketentuan |
| 4 | Sesi seminar tidak dipilih | Form meminta peserta memilih sesi |
| 5 | Alasan mengikuti seminar kurang dari 20 karakter | Form menolak teks yang terlalu pendek |

## Validasi Form

Validasi pada project ini memanfaatkan fitur validasi bawaan HTML, seperti `required`, `minlength`, `maxlength`, `type="email"`, dan `pattern`.

Validasi tersebut membantu memastikan bahwa data yang dimasukkan sudah sesuai dengan ketentuan sebelum formulir dikirim.

**Catatan:** Project ini masih berupa aplikasi Front-End. Form belum terhubung dengan database atau server, sehingga data pendaftaran belum disimpan secara permanen.

## 🎨 Tampilan Aplikasi

Desain form menggunakan konsep pastel dengan dominasi warna **lilac, lavender, dan putih**. Tampilan dibuat dengan sudut elemen yang membulat serta tata letak yang sederhana agar nyaman digunakan.

Selain tampilan desktop, desain juga dilengkapi pengaturan responsif agar form tetap nyaman dilihat melalui layar perangkat mobile.

## 📸 Hasil Tampilan

<img width="524" height="470" alt="Screenshot 2026-11-09 234031" src="https://github.com/user-attachments/assets/99ed7477-55f9-4566-8b59-04879d95fd19" />
<img width="442" height="449" alt="Screenshot 2026-11-09 234054" src="https://github.com/user-attachments/assets/69e32ebe-68ac-4d21-b399-f98f0949dde0" />


## Informasi Project

- **Nama Project:** Form Registrasi Seminar Teknologi 2026
- **Jenis Project:** Event Registration Form
- **Kategori:** Front-End Web Development
- **Teknologi:** HTML5 dan CSS3
- **Tahun:** 2026

---

*Dibuat untuk memenuhi tugas praktikum Desain Web.* ♥
