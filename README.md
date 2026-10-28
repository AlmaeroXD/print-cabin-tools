# Print Cabin Tools — HPP Stiker Logo Prototype v0.3

Isi folder:
- `index.html` — Kalkulator Jasa Formatting
- `cetak-foto.html` — Kalkulator Jasa Cetak Foto
- `stiker.html` — Kalkulator HPP Stiker Logo berdasarkan draft database HPP v0.1

## Jalankan lokal
Buka `index.html` atau `stiker.html` di browser. Halaman statis dan tidak membutuhkan server/backend.

## Publikasikan ke GitHub Pages
Unggah/commit ketiga file HTML ke root repository yang sama. Pastikan nama file `index.html`, `cetak-foto.html`, dan `stiker.html` persis sama. Navigasi antarhalaman sudah tersedia.

## Data HPP yang diterapkan
- Produk: `PRD-STICKER-LOGO`, Cetak Stiker Logo Jualan.
- Ukuran acuan: A4, stiker 3,2 × 4 cm, target awal 40 stiker/A4 (masih perlu verifikasi).
- Kertas stiker glossy V-Tec A4 100 gsm: Rp20.000/pack 20 lembar = Rp1.000/lembar (`ACTUAL`).
- Laminasi dingin GreatStar A4 120 gsm: Rp28.000/pack 20 lembar = Rp1.400/lembar; kompatibilitas pada stiker masih `PENDING_TEST`.
- Tinta referensi per A4: Rp95,33; ini bukan konsumsi tinta aktual desain stiker.
- Price Book: tanpa cutting Rp3.000/A4 (`WORKING`); cutting manual Rp5.000/A4 (`WORKING`); laminasi tanpa cutting Rp4.500/A4 (`PROPOSED`); laminasi + cutting Rp6.500/A4 (`PROPOSED`).
- Harga stiker/layanan laminasi belum final; pembuatan logo dari awal dan edit desain kompleks tidak otomatis termasuk. Cutting mengacu pada pemisahan label persegi panjang manual, bukan contour cut.

## Cara kalkulator menghitung
- Lembar dasar = pembulatan ke atas jumlah pesanan ÷ target output stiker per A4.
- Total lembar = lembar dasar + cadangan lembar yang secara manual ditambahkan.
- Subtotal dasar per A4 = kertas + tinta aktual yang dimasukkan; bila tinta aktual kosong, kalkulator memakai referensi Rp95,33/A4; untuk varian laminasi ditambah Rp1.400/A4.
- Subtotal dasar bukan HPP lengkap. Tenaga kerja, kemasan, penyusutan, listrik, reject, serta konsumsi tinta aktual belum tersedia secara default dan tidak boleh dianggap Rp0.
- Kalkulator memungkinkan masukan biaya tambahan; biaya tenaga kerja dihitung hanya jika tarif jam dan waktu proses yang relevan sudah diisi.
- `Sisa sebelum biaya yang belum diketahui` = tarif jual dikurangi subtotal dasar material yang terhitung. Angka ini bukan laba bersih atau margin final.
- Status HPP `INCOMPLETE`, `ESTIMATED`, atau `VALIDATED` bergantung pada kelengkapan input dan penanda verifikasi. `VALIDATED` merupakan penanda berdasarkan input pengguna, bukan validasi teknis otomatis. Status harga jual tetap `WORKING`/`PROPOSED` hingga persetujuan bisnis.

## Data referensi lain yang ditampilkan
- Tinta Brother original: Cyan/Magenta/Yellow 48,8 ml per botol Rp130.000; Black 108 ml per botol Rp130.000. Harga per ml hanya referensi matematis dan tidak menyatakan konsumsi per lembar.
- Printer Brother DCP-T520W: harga perolehan Rp2.744.600; tanggal beli, umur manfaat, total lembar produktif, maintenance dan penyusutan masih belum diketahui.
- Waktu awal: layout+cetak A4 lebih dari 5 menit (perlu dipisah); cutting 40 stiker 5–10 menit; laminasi dan pengemasan belum diukur.

## Batasan
Prototipe belum terhubung ke database EcoFin. Data input bersifat lokal selama halaman terbuka dan tidak disimpan otomatis. Target 40 pcs/A4, konsumsi tinta, proses, kompatibilitas laminasi, biaya overhead dan hasil produksi perlu diverifikasi sebelum HPP lengkap atau harga jual final ditetapkan.
