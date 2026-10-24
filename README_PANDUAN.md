# UTS PBM — Aplikasi Pencatatan Penjualan Ikan TPI

Folder ini adalah **satu project Android Studio** yang dirapikan dari tahap SQLite pada ZIP asal. Folder tahapan yang bertumpuk sudah dihilangkan.

## Fitur yang tersedia
- Input jenis ikan: Tongkol, Tuna, Kerapu, Cumi.
- Validasi berat dan harga.
- Mutu kurang segar mendapat pengurangan harga 25%.
- Perhitungan pendapatan kotor, retribusi TPI 5%, bagian pengepul 10%, dan pendapatan bersih.
- Daftar dan penghapusan transaksi.
- Penyimpanan lokal SQLite sehingga transaksi tetap ada saat aplikasi ditutup.
- Ikon launcher ikan merah.

## Cara membuka dan menjalankan
1. Ekstrak ZIP ini ke folder yang mudah ditemukan, misalnya `C:\Users\Nama\AndroidStudioProjects\`.
2. Buka Android Studio, pilih **File > Open**.
3. Pilih folder `UTS_PBM_TPI_Siap_Buka` yang berisi `settings.gradle.kts` dan `app`.
4. Tunggu **Gradle Sync** selesai. Izinkan unduhan dependency jika diminta dan pastikan internet aktif.
5. Sambungkan HP dengan USB debugging aktif, atau pilih emulator yang sudah berhasil dijalankan.
6. Pilih konfigurasi **app** di toolbar lalu tekan **Run (▶)**.
7. Untuk membuat APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**. Setelah berhasil, klik tautan lokasi APK yang muncul.

## Catatan penting
- Ini ZIP **source project**, bukan APK yang sudah dikompilasi. Kompilasi harus dilakukan di Android Studio karena memerlukan Android SDK dan dependensi Gradle.
- Jika emulator gagal karena disk penuh, jalankan di HP fisik atau kosongkan ruang penyimpanan terlebih dahulu.
- Isi identitas kelompok dan kebutuhan tugas pada dokumentasi sebelum dikumpulkan.
