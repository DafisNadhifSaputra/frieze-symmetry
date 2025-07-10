# Frieze Symmetry Web App

![Frieze Symmetry](screenshots/preview.png)

## Deskripsi Proyek

Frieze Symmetry Web App adalah aplikasi web interaktif yang memungkinkan pengguna untuk menggambar dan membuat pola frieze berdasarkan 7 grup simetri yang berbeda. Dengan aplikasi ini, pengguna dapat menggambar motif dasar yang kemudian secara otomatis diulang dan ditransformasikan sesuai dengan pola simetri frieze yang dipilih.

Aplikasi ini ideal untuk:
- Pembelajaran tentang simetri dan transformasi geometri
- Membuat pola dan motif berulang yang menarik
- Eksplorasi konsep matematika dalam seni dan desain

## Fitur Utama

- **7 Grup Simetri**: p111, pm11, p1m1, p112, pmm2, p1a1, dan pma2
- **Alat Gambar Beragam**: Garis, kotak, kotak terisi, oval, oval terisi, dan pensil (freehand)
- **Penyesuaian Lebar Garis**: Pilihan lebar garis yang beragam
- **Pemilihan Warna**: Menggunakan color picker yang interaktif
- **Pengaturan Translasi**: Mengatur jarak pengulangan motif
- **Grid Panduan**: Tampilan grid visual untuk membantu penempatan elemen
- **Mode Gelap/Terang**: Antarmuka yang nyaman untuk kondisi pencahayaan yang berbeda
- **Fitur Undo/Redo**: Membatalkan dan mengulangi perubahan
- **Ekspor & Impor**: Menyimpan karya dalam format JSON dan PNG

## Cara Penggunaan

1. **Pilih Grup Simetri**: Pilih salah satu dari 7 grup untuk transformasi.
2. **Pilih Alat & Opsi**: Pilih alat gambar, lebar garis, dan gaya kursor.
3. **Pilih Warna**: Gunakan color picker untuk memilih warna gambar.
4. **Menggambar**: Klik-tahan-geser pada kanvas putih.
5. **Translasi**: Sesuaikan jarak pengulangan dan klik "Terapkan".
6. **Grid**: Aktifkan/nonaktifkan garis bantu.
7. **Kontrol Lain**: Urungkan, Ulangi, Bersihkan, Simpan/Muat JSON, Unduh PNG.
8. **Mode Tampilan**: Gunakan sakelar untuk mode terang/gelap.

## Teknologi yang Digunakan

- HTML5 Canvas untuk menggambar
- JavaScript murni (vanilla JS)
- Pustaka iro.js untuk color picker
- CSS Variables untuk tema dinamis
- Responsive design untuk kompatibilitas perangkat

## Instalasi dan Penggunaan Lokal

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/Walpaper-Symmetry.git
   ```

2. Buka file `frieze-symmetry/index.html` di browser web Anda.

3. Tidak diperlukan instalasi atau dependensi tambahan, aplikasi akan langsung berjalan di browser.

## Demo

Lihat demo langsung dari aplikasi [di sini]([https://dafisnadhifsaputra.github.io/frieze-symmetry/]).

## Grup Simetri Frieze yang Didukung

| Grup | Deskripsi |
|------|-----------|
| p111 | Hanya translasi |
| pm11 | Refleksi vertikal |
| p1m1 | Refleksi horizontal |
| p112 | Rotasi 180° |
| pmm2 | Refleksi horizontal dan vertikal |
| p1a1 | Refleksi horizontal dengan glide |
| pma2 | Kombinasi refleksi vertikal dan glide |

## Perkembangan

Versi terkini: v1.9 - Modifikasi Dimensi & pm11

### Riwayat Versi

- v1.9: Modifikasi Dimensi & pm11
- v1.8: Spectrum Color Picker

## Kontribusi

Kontribusi sangat diterima! Jika Anda memiliki ide atau perbaikan:

1. Fork repositori ini
2. Buat branch baru (`git checkout -b fitur-baru`)
3. Commit perubahan Anda (`git commit -am 'Menambahkan fitur baru'`)
4. Push ke branch tersebut (`git push origin fitur-baru`)
5. Buat Pull Request

## Lisensi

Hak Cipta © 2025 Dafis Nadhif Saputra. Hak Cipta Dilindungi.

## Tentang Pengembang

Aplikasi ini dibuat dan dikembangkan oleh Dafis Nadhif Saputra.

---

**Catatan**: Tambahkan screenshot aplikasi di folder `screenshots/` sebelum men-deploy ke GitHub untuk memperbaiki tampilan README.
