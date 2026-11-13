# Ray Kreasi — Website Katalog

Website katalog satu halaman untuk promosi tas handmade dan tas eco-fashion Ray Kreasi.

## Isi website
- Beranda dan hero section dengan identitas Ray Kreasi.
- Dua pintu koleksi: Anyam & Crochet dan Pineapple Fiber.
- Katalog produk dengan filter kategori, filter karakter, pencarian, dan pengurutan.
- Modal detail produk dengan spesifikasi tas serat nanas yang tersedia di dokumen.
- Cerita Ray Kreasi, rangkaian proses pengolahan serat daun nanas, nilai usaha, serta informasi kontak.
- Tombol WhatsApp untuk bertanya/pemesanan dan daftar minat produk.
- Layout responsif untuk desktop, tablet, dan ponsel.

## Menjalankan secara lokal
Cukup buka `index.html` dengan browser. Website tidak membutuhkan instalasi package atau server backend.

## Mengubah nomor WhatsApp
Buka `index.html`, cari bagian JavaScript:

```js
const WHATSAPP_NUMBER = '6285822498909';
```

Ubah dengan nomor tujuan format internasional tanpa tanda `+`, spasi, atau strip. Perbarui juga tautan WhatsApp yang berada pada tombol kontak/footer bila nomor berubah.

## Mengubah produk
Data produk berada pada array `products` di bagian akhir `index.html`. Setiap produk memiliki:
- `id`, `name`, `category`, `categoryLabel`
- `image`, `badge`, `caption`, `tags`
- `description`, `specs`

Untuk menambah produk, duplikasi salah satu objek dan ganti data serta nama file gambar. Simpan foto baru ke folder `assets/`.

Harga sengaja ditampilkan sebagai **Hubungi untuk harga** karena dokumen yang diberikan belum mencantumkan harga jual katalog per model.

## Deploy melalui GitHub Pages
1. Buat repository baru di GitHub.
2. Unggah `index.html`, `README.md`, dan folder `assets/` ke root repository.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**, pilih branch `main` dan folder `/ (root)`, lalu simpan.
5. Setelah proses deploy selesai, GitHub Pages akan menampilkan alamat website.

## Catatan konten
- Informasi profil, proses serat nanas, dan spesifikasi Shoulder Bag serta Hand Bag dirangkum dari proposal dan dokumen produk Ray Kreasi yang diberikan.
- Foto produk dan dokumentasi proses berasal dari materi Ray Kreasi yang diberikan.
- Website ini adalah katalog promosi/front-end. Belum ada pembayaran online, manajemen stok, checkout, atau dashboard admin.
- Nomor WhatsApp yang dipakai saat ini mengikuti nomor kontak pada proposal terbaru yang dilampirkan. Pastikan nomor tersebut memang nomor publik yang ingin ditampilkan sebelum website dipublikasikan.
