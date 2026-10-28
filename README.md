# Print Cabin Tools — Prototype Kalkulator Stiker

Isi folder:
- `index.html` — Kalkulator Jasa Formatting
- `cetak-foto.html` — Kalkulator Jasa Cetak Foto
- `stiker.html` — Kalkulator Stiker (prototype)

## Jalankan lokal
Buka `index.html` atau `stiker.html` di browser. Semua halaman statis dan tidak membutuhkan server/backend.

## Publikasikan ke GitHub Pages
Unggah/commit ketiga file HTML ke root repository yang sama. Pastikan nama file `index.html`, `cetak-foto.html`, dan `stiker.html` persis sama. Navigasi antarhalaman sudah ditambahkan.

## Catatan penting
Nilai awal biaya bahan, cetak, potong, markup/margin, dan cadangan lembar pada kalkulator stiker hanya contoh yang dapat diedit. Kalkulator membedakan kebutuhan lembar dasar, cadangan lembar produksi, dan cadangan waste biaya. Pilihan rumus harga tersedia untuk markup atas biaya atau target margin laba kotor. Nilai tersebut bukan harga jual resmi Print Cabin. Perhitungan tata letak menggunakan grid sederhana dan belum memperhitungkan bleed, area non-printable printer, contour cut, atau efisiensi nesting bentuk kompleks.


## Rumus perhitungan
- Lembar dasar = pembulatan ke atas jumlah pesanan ÷ kapasitas stiker per lembar.
- Total lembar biaya = lembar dasar + cadangan lembar produksi.
- Biaya langsung = (bahan + cetak + laminasi + potong) per lembar × total lembar biaya.
- Waste biaya = persentase waste × biaya langsung; biaya persiapan tidak ikut dikenai persentase ini. Pastikan tidak menghitung risiko yang sama sebagai cadangan lembar sekaligus waste biaya.
- Total biaya = biaya langsung + biaya persiapan + waste biaya.
- Harga markup = total biaya × (1 + persentase markup).
- Harga target margin laba kotor = total biaya ÷ (1 − persentase margin). Untuk margin laba kotor, input dibatasi maksimum 99,9%.
- Biaya per buah dipesan = total biaya ÷ jumlah pesanan. Biaya per buah kapasitas = total biaya ÷ (total lembar biaya × stiker per lembar).

Harga jual tetap simulasi dan belum ditetapkan sebagai tarif resmi.
