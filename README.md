<h1> AWS SaaS Sales Analytics - Optimisasi Penjualan dan Profitabilitas Berbasis Data </h1>

## 1. Project Overview
Pada project ini perusahaan ingin memahami kinerja bisnis AWS SaaS berdasarkan data AWS SaaS Sales dalam format CSV yang mencatat riwayat transaksi dari tahun 2020 hingga 2023. Analisis ini berfokus pada evaluasi performa penjualan dan profitabilitas dari berbagai `Product`, `Subregion`, `Segment`, serta `Industry`. Selain itu, perusahaan juga ingin memahami dampak `Discount` terhadap `Profit Margin` guna mendukung pengambilan keputusan strategis yang lebih efektif. Informasi ini akan membantu perusahaan dalam mengidentifikasi peluang peningkatan profit serta mengurangi potensi kerugian.

Key Objectives:
- Menganalisis tren penjualan dan profit AWS SaaS dari tahun ke tahun dan faktor-faktor yang dapat mempengaruhinya.
- Mencari tahu subregion mana yang menunjukkan performa sales dan profitabilitas yang kuat atau lemah.
- Menentukan customer segment dan industry mana yang memberikan kontribusi profit terbesar maupun terkecil.
- Mengidentifikasi produk apa saja yang menghasilkan loss atau profit rendah meskipun memiliki sales tinggi.
- Menganalisis pengaruh discount terhadap profit margin serta subregion, segment, industry dan product.

## 2. Data Sources
[SaaS-Sales](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales) - AWS SaaS Sales for 2020-2023

## 3. Technologies Used
- Programming Language: Python (e.g., Pandas, NumPy)
- Visualization: Matplotlib, Seaborn, Plotly
- Version Control: Git
- Others: Jupyter Notebook

## 4. Project Structure

```
├── README.md                           <- The top-level README for developers using this project.
|
├── AWS-SaaS-Sales-Presentation.pdf     <- Generated analysis as pdf for project presentation.
│             
├── SaaS-Sales-Data-Analytic.ipynb      <- Jupyter notebooks. Analytics.
│
├── Cleaned-SaaS-Sales.csv              <- Cleaned Data.
│                                                                      
└── SaaS-Sales.csv                      <- Raw Data.

```

## 5. Summary of Finding
### 5.1 Business Insight
**Tren Penjualan dan Profit**
- Tren pertumbuhan positif dengan rata-rata puncak penjualan di akhir tahun (Q4), sementara di awal tahun rata-rata volume penjualan cenderung menurun.
- Peningkatan signifikan penjualan tidak selalu diikuti kenaikan profit yang sebanding.

**Subregion**
- Subregion IND, UKIR, dan NAMER menunjukkan margin keuntungan yang kuat dan stabil.
- JAPN dan ANZ memperlihatkan fluktuasi margin yang tinggi serta sering mengalami margin negatif.

**Segment dan Industry**
- SMB merupakan kontributor terbesar terhadap revenue dan profit.
- Enterprise kontribusi terkecil untuk sales dan profit tetapi memiliki profit margin terbesar.

**Product**
- Produk ContactMatcher, Site Analytics, Marketing Suite – Gold, dan Big Ol Database termasuk dalam kategori “high sales but low margin”.
- Produk Alchemy, Data Smasher, Support, dan FinanceHub mampu mempertahankan margin yang kuat.

**Discount**
- Pemberian diskon menunjukkan korelasi negatif yang sangat kuat dengan margin keuntungan (–0,864).
- Tingkat diskon yang lebih tinggi secara konsisten menghasilkan margin yang lebih rendah atau bahkan negatif.

### 5.2 Actionable Recommendation
- Strategi Optimisasi Penjualan dan Profit Tahunan
- Kontrol Pemberian Discount
- Tinjau Kembali Harga untuk Produk High-Sales dengan Margin Rendah
- Fokus pada Produk Bermargin Tinggi untuk Upselling dan Promosi, Produk dengan margin tinggi
- Strategi Penetapan Harga Berdasarkan Segmen
- Tinjauan Strategi Harga Berdasarkan Subregion
- Pantau Pemberian Discount melalui Pelaporan Berkala
