# Print Cabin Tools — Kalkulator Formatting

Aplikasi web statis untuk menghitung estimasi harga jasa formatting dokumen Print Cabin.

## Menjalankan secara offline

Buka `index.html` menggunakan browser modern seperti Chrome, Edge, atau Firefox. Tidak membutuhkan server, package manager, atau koneksi internet untuk menghitung harga.

## Menerbitkan dengan GitHub Pages

1. Buat repositori GitHub bernama `print-cabin-tools`.
2. Unggah `index.html` ke direktori utama repositori (root).
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu proses deployment selesai. Alamat proyek biasanya berbentuk `https://USERNAME.github.io/print-cabin-tools/`.

## Catatan privasi dan penggunaan

- GitHub Pages adalah website publik; jangan masukkan data pelanggan, data pribadi, atau informasi rahasia ke dalam repositori.
- Untuk akun GitHub Free, GitHub Pages tersedia dengan repositori publik. Periksa ketentuan penggunaan GitHub Pages sebelum menjadikan aplikasi bisnis ini sebagai layanan produksi.
- Aplikasi ini menghitung estimasi saja. Periksa kondisi dokumen dan kompleksitas pekerjaan sebelum mengunci harga, terutama untuk kategori Complex.
- Semua nilai harga dan aturan diskon berada di JavaScript pada `index.html`; perubahan tarif harus diuji setelah diedit.
