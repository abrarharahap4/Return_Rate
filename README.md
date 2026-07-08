# Interactive Dashboard - Data Visualization
## Dibimbing.id (Assignment Day 30)
<br>

### 📊 Dashboard Analisis Return Rate Produk E-Commerce Otomotif - AdventureWorks
Dashboard interaktif berbasis PowerBI untuk menganalisis tingkat pengembalian (return rate) produk pada data penjualan e-commerce AdventureWorks. lengkap dengan estimasi kerugian pendapatan dan profit akibat return.

<img width="1263" height="707" alt="image" src="https://github.com/user-attachments/assets/fdff4a11-90e2-4ef3-b8ab-4912abe458aa" />


### 📁 Isi Repository
- [AdventureWorks_Sample_Dataset.xlsx](./AdventureWorks_Sample_Dataset.xlsx)

- [Ghairandi_Al_Abrar_Assignment_Day_27_Dashboard.pbix](./Ghairandi_Al_Abrar_Assignment_Day_27_Dashboard.pbix)


### 🎯 Tujuan Proyek
Membangun dashboard yang dapat membantu tim bisnis dan manajemen memahami:
- Seberapa besar tingkat return produk secara keseluruhan
- Kategori/sub-kategori produk mana yang paling sering dikembalikan oleh customer
- Tren jumlah return dari waktu ke waktu
- Estimasi kerugian pendapatan (revenue) akibat tingkat return 


### 🧩 Fitur & Visualisasi
  #### Key Metrics (Cards)
  - Total Order (Jumlah order yang terjadi)
  - Total Quantity (terjual)
  - Total Return Quantity (jumlah yang dikembalikan)
  - Return Rate (%)
  - Estimated Lost Profit

  #### Visual Utama
  - Pivot Table => Breakdown Return Rate & Estimaed Lost Revenue per Category => Sub-category => Product Name
  - Line Chart => Tren total Return per tahun & bulan
  - Bar Chart => Perbandingan Return Rate antar kategori produk
  - Slicer => Filter interaktif berdasarkan Sub-Category produk


### 📌 Key Insights
Selama periode yang dianalisis, AdventureWorks mencatat 200 order dengan total 1.163 unit produk terjual, dan dari jumlah itu sebanyak 67 unit dikembalikan pelanggan — setara Return Rate sebesar 5,76%, yang berujung pada estimasi kerugian pendapatan sekitar $45.849.

Yang menarik, kategori Clothing justru punya Return Rate paling tinggi (6,5%) dibanding Bikes (5,8%) dan Accessories (5,2%), padahal volume penjualannya paling kecil di antara ketiganya — artinya rasio returnnya nggak proporsional dengan seberapa banyak produk itu terjual. 

Tren return juga sempat melonjak tajam di April–Mei 2024, dengan jumlah return dua kali lipat lebih tinggi dibanding bulan-bulan lain, dan kontributor kerugian terbesar datang dari dua produk spesifik, WindCutter S dan Ridge Runner 350, yang bersama-sama menyumbang lebih dari $16.000 lost revenue. 

Temuan ini mengarah ke rekomendasi untuk mengaudit kualitas produk di kategori Clothing meski volumenya kecil, menelusuri lebih lanjut apa yang terjadi pada WindCutter S dan Ridge Runner 350, serta mengecek apakah ada masalah batch produksi atau kualitas yang muncul spesifik di periode April–Mei 2024.

### 🗂️ Sumber Data
Dataset menggunakan AdventureWorks Sample Dataset (data publik) yang berisi tabel Sales, Products, dan Returns yang saling berelasi.



