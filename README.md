# UTS PBM - Kasus 6: Pencatatan Penjualan Ikan TPI

Aplikasi Android Kotlin + Jetpack Compose untuk mencatat penjualan ikan di TPI.

## Fitur
- Jenis ikan: Tongkol, Tuna, Kerapu, dan Cumi.
- Validasi berat (> 0 dan maksimal 500 kg) dan harga.
- Ikan kurang segar mendapat pengurangan harga 25%.
- Ringkasan pendapatan kotor, retribusi TPI 5%, bagian pengepul 10%, dan pendapatan bersih.
- Ringkasan berat dan nilai penjualan per jenis ikan.
- Hapus transaksi.
- **SQLite lokal** untuk menyimpan data transaksi secara permanen saat aplikasi ditutup dan dibuka kembali.

## Cara membuka
1. Ekstrak ZIP.
2. Android Studio > Open, pilih folder utama `UTS_PBM_Kasus6_TPI` (folder ini berisi `settings.gradle.kts`).
3. Tunggu Gradle Sync selesai.
4. Sambungkan perangkat Android dengan USB debugging aktif.
5. Pilih perangkat di toolbar lalu tekan Run (▶).

## Penyimpanan data
Database dibuat otomatis di penyimpanan internal aplikasi dengan nama `tpi_penjualan.db`, tabel `penjualan_ikan`. Data tidak memerlukan internet. Data dapat hilang jika aplikasi di-uninstall atau data aplikasi dihapus melalui pengaturan Android. Belum ada fitur ekspor/cadangan.

## Catatan
Proyek ini adalah kode sumber awal. Jalankan Gradle Sync dan build di Android Studio; bila muncul error, perbaiki sesuai pesan yang tampil.
