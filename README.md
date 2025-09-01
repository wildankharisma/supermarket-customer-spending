# supermarket-customer-spending
Capstone Project - Customer Spending Analysis

## Gambaran Umum
Project ini merupakan **capstone project analisis data** yang berfokus pada perilaku belanja (spending) pelanggan di sebuah supermarket.  
Tujuannya adalah untuk memahami faktor-faktor utama yang memengaruhi pengeluaran pelanggan dan memberikan insight yang dapat digunakan untuk **strategi marketing** dan **segmentasi pelanggan**.

Analisis difokuskan pada tiga faktor utama:  
- **Family Type** – aspek demografi terkait kebutuhan & pola konsumsi rumah tangga  
- **Income** – kapasitas finansial sebagai indikator daya beli  
- **Purchase Channel** – preferensi pelanggan dalam memilih saluran belanja  

## Dataset Overview
Dataset berisi informasi tentang demografi pelanggan, perilaku belanja, serta saluran pembelian.
- **People**:
ID, Year_Birth, Education, Marital_Status, Income, Kidhome, Teenhome, Dt_Customer, Recency, Complain
- **Products**:
MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds
- **Promotion**:
NumDealsPurchases, AcceptedCmp1-5, Response
- **Place**:
NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth

## Alur Analisis
- **Business Understanding**:
Menentukan konteks & perumusan masalah
- **Data Preprocessing**:
Pembersihan data, penanganan missing values, konversi tipe data
- **Exploratory Data Analysis (EDA)**:
Analisis distribusi, outlier, korelasi, pola spending
- **In Depth Analysis**:
Uji T-test, ANOVA, Kruskal untuk validasi hipotesis
- **Insights & Kesimpulan**:
Temuan utama untuk segmentasi & strategi

## Insight Utama
- Pendapatan (Income) memiliki korelasi positif kuat dengan total spending.
- Family Type berpengaruh terhadap preferensi kategori produk (keluarga dengan anak vs single).
- Purchase Channel menunjukkan intensitas spending yang berbeda; belanja di toko vs online memberikan pola yang bervariasi.
- Segmentasi pelanggan dapat membantu supermarket untuk menargetkan pelanggan bernilai tinggi dan mengoptimalkan kampanye promosi.
