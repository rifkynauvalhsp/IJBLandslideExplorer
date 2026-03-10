# IJBLandslideExplorer

IndrajaBuana Landslide Explorer adalah aplikasi Google Earth Engine (GEE) mutakhir untuk mendeteksi area tanah longsor dan menganalisis dampak kerusakannya secara real-time.

Sistem ini dirancang untuk memecahkan masalah tutupan awan pasca-bencana dengan memanfaatkan penetrasi sinyal radar, serta menggabungkannya dengan kecerdasan buatan yang dilatih menggunakan citra satelit beresolusi ultra-tinggi.

✨ Fitur Unggulan

🚀 Deteksi Tembus Awan (SAR): Menggunakan satelit Sentinel-1 (Normalized Radar Burn Ratio) untuk memetakan keruntuhan lereng tanpa terhalang cuaca buruk.

🧠 Ensemble Machine Learning: Model AI (Random Forest + GBM) dilatih secara spesifik menggunakan Ground Truth dari citra komersial PlanetScope (3m) untuk akurasi prediksi level regional.

💰 Valuasi Dampak Sosial-Ekonomi: Secara otomatis menghitung kerugian finansial (dalam Rupiah) untuk kerusakan bangunan, pertanian, infrastruktur, serta mengestimasi populasi jiwa yang terdampak.

⚠️ Pemodelan Risiko Dinamis (AHP): Menghasilkan indeks bahaya spasial berdasarkan topografi (NASADEM), anomali hujan (CHIRPS), kelembapan tanah (FLDAS), dan tata guna lahan.

🧹 Filter Noise Pintar: Pemrosesan raster cepat (Fast Raster Analytics) yang mengabaikan deteksi palsu di bawah 3 piksel terhubung.

🛠️ Cara Penggunaan

Buka Aplikasi: Akses tautan live Google Earth Engine.

Gambar Area (AOI): Gunakan drawing tools (kotak/poligon) di peta untuk menentukan zona analisis.

Atur Parameter: Masukkan tanggal Pre-Event dan Post-Event kejadian bencana.

Pilih Metode: Sangat disarankan menggunakan mode ML Fusion (Trained on Planet).

Jalankan: Klik "Jalankan Analisis". Panel kiri akan memuat statistik kerusakan, grafik curah hujan, dan proporsi lahan terdampak secara interaktif.

🔬 Studi Kasus: Longsor Pasir Langu

Aplikasi ini telah divalidasi pada kejadian bencana ekstrem di Pasir Langu, Bandung Barat (Januari 2026), mampu mengidentifikasi 3.42 Ha area runtuhan dan memproyeksikan kerugian ekonomi hingga miliaran rupiah hanya dalam hitungan detik.

Pengembang Proyek: Rifky Nauval Hendrawan & Dr. Irwan Ary Dharmawan

Laboratorium Digital Rock Physics & Remote Sensing (DRPRS) - Universitas Padjadjaran
