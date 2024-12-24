# 🌐 Cakrawala Logistic Shipping Dataset

## 📄 Deskripsi
Dataset ini memuat informasi mengenai pengiriman barang di Cakrawala Logistik. Data ini mencakup detail pesanan, kondisi cuaca saat pengiriman, jenis kendaraan yang digunakan, kategori produk, dan status kedatangan. Tujuan dari dataset ini adalah untuk mengevaluasi efektivitas dan kecepatan pengiriman berdasarkan kondisi tertentu, serta untuk monitoring operasional.

### 📅 Tanggal Pembuatan
5 Desember 2024

## 🗂 Metadata Dataset

### 📊 Struktur Data

| Kolom              | Tipe Data      | Deskripsi                                                                 |
|--------------------|---------------|---------------------------------------------------------------------------|
| Order_ID           | VARCHAR(255)  | ID unik untuk setiap pesanan, berisi kombinasi huruf dan angka.          |
| Branch_Start       | VARCHAR(255)  | Cabang pengiriman awal (lokasi pengambilan barang).                      |
| Branch_Drop        | VARCHAR(255)  | Cabang pengiriman tujuan (lokasi penerimaan barang).                     |
| Pengirim           | VARCHAR(255)  | Nama pengirim barang.                                                    |
| Penerima           | VARCHAR(255)  | Nama penerima barang.                                                    |
| Alamat_Penerima    | TEXT          | Alamat lengkap tempat pengiriman barang, biasanya lebih panjang.         |
| Weather_Condition  | VARCHAR(255)  | Kondisi cuaca saat pengiriman barang.                                    |
| Vehicle_Type       | VARCHAR(255)  | Jenis kendaraan yang digunakan untuk pengiriman.                         |
| Category           | VARCHAR(255)  | Kategori produk yang dikirim.                                            |
| Arrival_Status     | VARCHAR(255)  | Status kedatangan barang.                                                |

### 📋 Atribut Penting untuk Analisis

1. *Order_ID*: Digunakan untuk mengidentifikasi pesanan secara unik dalam proses analisis.
2. *Weather_Condition*: Membantu memahami pengaruh kondisi cuaca terhadap keterlambatan pengiriman.
3. *Arrival_Status*: Informasi utama untuk mengetahui status kedatangan barang (tepat waktu atau terlambat).
4. *Branch_Start & Branch_Drop*: Membantu melacak rute pengiriman barang yang mungkin memiliki korelasi dengan keterlambatan.
5. *Vehicle_Type*: Memungkinkan analisis jenis kendaraan yang paling sering mengalami keterlambatan atau efisiensi pengiriman.

### 📋 Contoh Data
| Order_ID       | Branch_Start  | Branch_Drop      | Pengirim        | Penerima         | Alamat Penerima                    | Weather_Condition | Vehicle_Type    | Category      | Arrival_Status         |
|----------------|---------------|------------------|-----------------|------------------|------------------------------------|-------------------|-----------------|---------------|------------------------|
| ialx566343618  | Kebon Kawung  | Depok            | Michael Hubbard| Alexis Torres    | Buah Batu No.149, RT 9/RW 6       | Sunny             | pick up truck   | Clothing      | Terlambat             |
| akqg208421122  | Jalan Braga   | Jambi            | Tammy Gonzalez  | Lisa Clark       | Cihampelas No.367, RT 6/RW 7      | Stormy            | cargo truck     | Electronics   | Lebih Cepat Sampai    |
| njpu434582536  | Pasir Kaliki  | Tebing Tinggi    | Brian King      | Christy Reynolds | Dago No.564, RT 7/RW 5            | Sandstorms        | pick up truck   | Sports        | Tepat Waktu           |

## 📜 Lisensi
Dataset ini dirilis di bawah lisensi *MIT License*. Detail lisensi dapat ditemukan di [MIT License](https://www.mit.edu/~amini/LICENSE.md).

## 📚 Referensi
- [Kaggle - Amazon Delivery Dataset](https://www.kaggle.com/datasets/sujalsuthar/amazon-delivery-dataset)

## 👥 Kelompok 4
1. Agisni Zahra Latifa 
   - Kontak: [agisnizaral@student.telkomuniveristy.ic.id](mailto:agisnizaral@student.telkomuniveristy.ic.id)
2. Felicia Talitha Fathin 
   - Kontak: [feliciatalithah@student.telkomuniversity.ac.id](mailto:feliciatalithah@student.telkomuniversity.ac.id)
3. Salsabila Naurah Putri 
   - Kontak: [salsabilanaurah@student.telkomuniversity.ac.id](mailto:salsabilanaurah@student.telkomuniversity.ac.id)
