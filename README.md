# LariKita Coach — prototipe input manual

## Fitur prototipe
- Dashboard dan agenda latihan mingguan contoh
- Template program 5K, 10K, half marathon, dan marathon (4 minggu)
- Input manual jarak, durasi, dan RPE; hitung pace dari jarak/waktu
- Input usia, HR istirahat, dan HR maksimum untuk estimasi zona HR Karvonen
- Kalender latihan sederhana
- Perpustakaan drill, strength/core, mobility/isometrik, dan plyometrik
- Checklist recovery dan kesiapan latihan
- Profil pelari, input PB, dan prediksi kasar dari PB 5K
- Daftar murid lokal
- AI Coach demo berbasis aturan lokal (belum terhubung ke AI online)
- PWA manifest dan service worker

## Keputusan produk
Aplikasi ini tidak memakai GPS untuk merekam lari. Semua data latihan dimasukkan secara manual oleh pelari atau pelatih. Integrasi smartwatch tidak termasuk dalam versi ini.

## Cara mencoba
Buka `index.html` di browser modern. Untuk pemasangan seperti aplikasi (PWA), host folder ini di HTTPS lalu buka melalui Chrome Android dan pilih menu "Install app" / "Add to Home screen". Service worker biasanya tidak berjalan dari `file://`.

## Cara menjadi APK Android
Paket ini belum merupakan APK native yang sudah ditandatangani. Untuk APK yang bisa langsung dipasang, folder ini perlu dibungkus dengan Android Studio (mis. WebView/Capacitor), diberi package ID dan ikon, lalu build APK dan uji di perangkat. Fitur akun, sinkronisasi cloud, database murid multi-perangkat, dan AI online belum diimplementasikan. Jangan menyimpan API key rahasia langsung di APK.

## Keselamatan
Program merupakan contoh awal, bukan resep individual. Volume dan intensitas perlu disesuaikan dari riwayat 3–4 minggu, pengalaman, kesehatan, dan gejala. Hentikan latihan dan cari pertolongan untuk nyeri dada, pingsan, sesak yang tidak wajar, atau cedera akut. Rumus HR dan prediksi performa hanyalah perkiraan.
