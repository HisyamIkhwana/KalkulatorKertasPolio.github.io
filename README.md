# Kalkulator Kertas Folio

Sebuah aplikasi web sederhana namun canggih untuk menghitung secara akurat jumlah lembar kertas folio (F4) yang dibutuhkan untuk sebuah naskah. Berbeda dari kalkulator biasa, aplikasi ini mensimulasikan tata letak teks berdasarkan konten, font, dan margin untuk memberikan estimasi yang paling mendekati kenyataan.

Aplikasi ini dibuat untuk membantu mahasiswa, penulis, atau siapa saja yang perlu mencetak dokumen dengan aturan spesifik, seperti jumlah baris yang berbeda pada halaman pertama karena adanya kop surat atau logo.

## ✨ Fitur Utama

- **Perhitungan Berbasis Konten**: Cukup tempelkan seluruh naskah Anda, dan aplikasi akan menghitung total baris secara otomatis.
- **Simulasi Tata Letak Akurat**: Menggunakan lebar kertas, margin, jenis font (Arial), dan ukuran font untuk menyimulasikan bagaimana teks akan tersusun di halaman.
- **Aturan Halaman Kustom**: Diprogram secara spesifik untuk aturan:
    - Halaman pertama memuat **34 baris** (untuk mengakomodasi logo/kop surat).
    - Halaman selanjutnya memuat **40 baris**.
- **Pengaturan Fleksibel**: Pengguna dapat mengubah **ukuran font** dan **total margin** untuk menyesuaikan dengan kebutuhan dokumen mereka.
- **Antarmuka Modern**: Tampilan yang bersih, responsif, dan mudah digunakan, dibangun dengan HTML5 & CSS3 modern.
- **Tanpa Server**: Sepenuhnya berjalan di sisi klien (browser), tidak memerlukan backend atau koneksi internet setelah halaman dimuat.

## 🚀 Cara Menggunakan

1.  **Buka Aplikasi**: Buka file `index.html` di browser web favorit Anda (Chrome, Firefox, Safari, dll).
2.  **Tempelkan Naskah**: Salin dan tempel (paste) seluruh isi dokumen atau naskah Anda ke dalam area teks yang tersedia.
3.  **Atur Parameter**:
    - Sesuaikan **Ukuran Font** (dalam `pt`).
    - Masukkan **Total Margin** gabungan kiri dan kanan (dalam `cm`). Contoh: jika margin kiri 2.5cm dan kanan 2.5cm, masukkan `5`.
4.  **Hitung**: Klik tombol **"✨ Hitung Kebutuhan Kertas"**.
5.  **Lihat Hasil**: Hasil estimasi jumlah baris total dan jumlah lembar kertas folio yang dibutuhkan akan langsung ditampilkan di bagian bawah.

## 🛠️ Teknologi yang Digunakan

- **HTML5**: Untuk struktur dasar dan konten halaman web.
- **CSS3**: Untuk styling, tata letak modern (Flexbox/Grid), dan responsivitas.
-   **Google Fonts**: Menggunakan font 'Poppins' untuk antarmuka yang lebih baik.
- **JavaScript (Vanilla)**: Untuk semua logika perhitungan, simulasi DOM, dan interaktivitas tanpa memerlukan library atau framework eksternal.

## 📂 Struktur Proyek
.
└── index.html      # Satu file yang berisi semua HTML, CSS, dan JavaScript.
Proyek ini sengaja dibuat dalam satu file untuk portabilitas dan kemudahan penggunaan.

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Anda bebas menggunakan, memodifikasi, dan mendistribusikan kode ini untuk tujuan apa pun.

---
*Dibuat dengan ❤️ untuk membantu mempermudah pekerjaan tulis-menulis.*
