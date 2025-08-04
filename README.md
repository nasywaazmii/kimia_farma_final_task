# kimia_farma_final_task
Final task project: Big Data Analyst Kimia Farma

Sebagai perusahaan farmasi nasional, Kimia Farma perlu memahami performa bisnisnya secara menyeluruh, terutama selama periode 2020–2023 yang dipengaruhi pandemi dan perubahan perilaku konsumen. Melalui proyek ini, tujuannya  menganalisis data transaksi, produk, dan cabang Kimia Farma menggunakan BigQuery dan Looker Studio. Tujuannya adalah menghasilkan dashboard interaktif yang menyajikan insight tentang penjualan, profitabilitas, dan kepuasan pelanggan sebagai dasar pengambilan keputusan strategis.

📊 Dataset yang Digunakan
Empat dataset utama disediakan dan di-import ke Google BigQuery:
kf_final_transaction – berisi transaksi pelanggan (tanggal, harga, diskon, rating)
kf_product – informasi produk (id, nama, kategori, harga)
kf_kantor_cabang – data cabang (id, nama, kota, provinsi, rating)
kf_inventory – data stok barang di tiap cabang


Problem Statement :
Bagaimana kinerja penjualan Kimia Farma dari tahun ke tahun?
Cabang mana yang memiliki performa terbaik dan sebaliknya?
Produk dan wilayah mana yang memberikan kontribusi terbesar terhadap nett profit?
Apakah cabang yang memiliki rating tinggi juga memiliki rating transaksi tinggi?

Langkah-langkah Analisis:
Mengimpor data ke BigQuery dan membuat dataset kimia_farma
Melakukan transformasi data dan membuat tabel agregat melalui SQL
Menghitung metrik bisnis penting
Membuat dashboard di Google Looker Studio
Analisis tahunan, provinsi, cabang, produk, serta visualisasi GeoMap dan filter dinamis




