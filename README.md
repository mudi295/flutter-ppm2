# PPM Sesi 2 — Product & Profile

Project Flutter Web untuk tugas PPM Sesi 2.

## Identitas
- Nama: Muhamad Hamudi
- NIM: 20240040028
- Prodi/Kelas: Teknik Informatika / TI24G

## Fitur
- AppBar sesuai format tugas
- Kartu profil menggunakan `StatelessWidget`
- 5 ikon bintang
- Kartu produk menggunakan `StatefulWidget`
- Favorite dengan perubahan ikon dan jumlah Like
- Tombol `-` / `+`, minimum quantity 1
- Total harga otomatis
- Tombol Tambah ke Keranjang + SnackBar
- Banner promo menggunakan `Stack` dan `Positioned`
- Responsive layout untuk web
- Tanpa package tambahan

## Menjalankan
```bash
flutter pub get
flutter run -d chrome
```

Untuk web-server:
```bash
flutter run -d web-server --web-hostname 0.0.0.0 --web-port 8080
```
