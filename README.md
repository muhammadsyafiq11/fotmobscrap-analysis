<p align="center" width="80%">
    <img width="60%" src="images/top 5 league logo.jpg">
</p>

<div align="center">
# 📊 Scraping & Visualisasi Data Top 5 Liga Eropa dari Fotmob
<p align="center">

Proyek ini merupakan proyek yang bertujuan untuk mengambil data statistik tim sepak bola dari situs [Fotmob.com](https://www.fotmob.com/), menyimpannya ke dalam basis data MongoDB, serta menyajikannya dalam bentuk visualisasi yang informatif untuk menggali insight dari 5 liga top Eropa.

## 🎯 Tujuan Proyek

- Mengambil data statistik tim (seperti jumlah gol, kebobolan, jumlah kartu kuning) dari **Premier League**, **La Liga**, **Bundesliga**, **Serie A**, dan **Ligue 1**
- Menyimpan data hasil scraping ke dalam basis data **MongoDB**
- Melakukan agregasi data untuk menghasilkan insight seperti:
  - Tim dengan serangan terbaik dengan metrik tertentu
  - Tim dengan bertahan terbaik dengan metrik tertentu
- Menyajikan hasil analisis melalui visualisasi menggunakan **matplotlib**, **seaborn**, dan **plotly**

## 🧰 Teknologi yang Digunakan

- **Bahasa Pemrograman**: Python
- **Scraping**: `requests`, `Selenium`, `pandas`
- **Database**: MongoDB Atlas
- **Visualisasi**: `matplotlib`, `seaborn`, `plotly`
- **Antarmuka Notebook**: Jupyter

## 📁 Struktur Proyek
```
fotmobscrap-analysis/
├── data/
    Top.5.Liga.csv
├── images/
    big chance conversion rate.png
    performa defensif top 5 klub.png
    radar top 5 rating.png
├── notebooks/
    Scrapping & Visualization Fotmob.ipynb
└── README.md
```

## 🔍 Fitur

- Scraping data statistik tim dari 5 liga besar Eropa
- Penyimpanan data ke MongoDB
- Agregasi performa tim untuk analisis mendalam
- Visualisasi seperti:
  - Bar chart: Tim dengan jumlah gol tertinggi
  - Radar chart: Efektivitas bertahan tim
  - Bar chart: Tim dengan konversi peluang tertinggi
  - dll
 
## 📊 Contoh Visualisasi
![Radar Chart: Top 5 Klub dengan Rating Tertinggi](images/radar%20top%205%20rating.png)
![Radar Chart: Top 5 Klub dengan Konversi Peluang Besar Tertinggi](images/big%20chance%20conversion%20rate.png)
![Radar Chart: Top 5 Klub dengan Performa Defensif Terbaik](images/performa%20defensif%20top%205%20klub.png)

## 📚 PPT
Berikut adalah link powerpoint berkaitan dengan project yang telah dibuat :
+ [PPT Fotmob Data Scraping, Aggregation, and Visualization](https://drive.google.com/file/d/1F-8oZ7S3CG4BsB8t8NB5V9Xx3SxCHkor/view?usp=sharing)
  
## 🤝 Tim Pengembang
+ [Muhammad Syafiq](https://github.com/muhammadsyafiq11/) (M0501241005)
+ [Nabillah Rahmatiah Tangke](https://github.com/nabillahtangke/) (M0501241070)
+ [Naufalia Alfiryal](https://github.com/Naufaliaa/) (M0501241074)
+ [Nabila Fida Millati](https://github.com/nabilafida/) (M0501241087)
