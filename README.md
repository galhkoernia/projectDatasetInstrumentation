# Project Data Mata Kuliah Instrumentasi Cerdas

Project ini berisi pengolahan tiga jenis dataset untuk tugas pengolahan
data, yaitu **tabular, image, dan sequence**. Setiap dataset memiliki
keterkaitan dengan bidang Fisika dan diolah menggunakan Python melalui
Jupyter Notebook.

## Struktur Project

``` text
project-data/
├── citra/
│   ├── assets/
│   │   └── galaxy/
│   └── analysis_citra.ipynb
├── sequence/
│   ├── assets/
│   │   ├── AirQualityUCI.csv
│   │   └── AirQualityUCI.xlsx
│   └── analysis_sequence.ipynb
├── tabular/
│   ├── assets/
│   │   └── crop_recommendation.csv
│   └── analysis_tabular.ipynb
└── README.md
```

## Dataset Tabular

Folder: `tabular/`

Dataset: `crop_recommendation.csv`

Dataset berbentuk tabular dan memuat parameter lingkungan/tanah seperti
N, P, K, temperature, humidity, pH, rainfall, serta label.

Pengolahan mencakup pemeriksaan struktur dan kualitas data, statistik,
visualisasi, serta analisis parameter.

Notebook: `tabular/analysis_tabular.ipynb`

> **Sumber Data:** Dataset diperoleh dari [Kaggle](https://www.kaggle.com/) —
> *Crop Recommendation Dataset*. Dataset digunakan hanya untuk keperluan
> pembelajaran/tugas pengolahan data.

## Dataset Image

Folder: `citra/`

Dataset berupa **citra Galaxy**.

Pengolahan citra mencakup pembacaan gambar, pemeriksaan ukuran dan mode,
visualisasi, grayscale, representasi piksel sebagai data numerik,
statistik intensitas, histogram, dan normalisasi piksel.

Notebook: `citra/analysis_citra.ipynb`

> **Sumber Data:** Dataset citra Galaxy diperoleh dari [Kaggle](https://www.kaggle.com/) —
> *Galaxy Image Dataset*. Dataset digunakan hanya untuk keperluan
> pembelajaran/tugas pengolahan citra.

## Dataset Sequence

Folder: `sequence/`

Dataset: **Air Quality UCI**

Dataset memiliki urutan waktu sehingga digunakan sebagai
**sequence/time-series**. Parameter yang berkaitan dengan kondisi fisik
lingkungan antara lain temperatur dan kelembapan.

Pengolahan mencakup pembacaan data, pembersihan, pembentukan timestamp,
pengurutan berdasarkan waktu, pengambilan parameter fisik, visualisasi
terhadap waktu, statistik sequence, dan moving average.

Notebook: `sequence/analysis_sequence.ipynb`

> **Sumber Data:** Dataset *Air Quality UCI* diperoleh dari [Kaggle](https://www.kaggle.com/) —
> *Air Quality UCI Dataset*. Dataset digunakan hanya untuk keperluan
> pembelajaran/tugas pengolahan data sequence.

## Tujuan

Project ini menunjukkan pengolahan dasar pada tiga bentuk data:

**Tabular → Image → Sequence**

Fokus pengolahan adalah memahami, membersihkan, mengolah, dan
menganalisis data. Project ini tidak berfokus pada model Machine
Learning yang kompleks.

## Tools

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   PIL/Pillow
-   Jupyter Notebook / Google Colab

## Lisensi & Sumber Data

Seluruh dataset yang digunakan dalam project ini **diperoleh dari Kaggle**
(https://www.kaggle.com/). Hak cipta dan lisensi masing-masing dataset
sepenuhnya mengikuti ketentuan yang tercantum pada halaman dataset di
Kaggle.

Dataset digunakan **hanya untuk keperluan pembelajaran, tugas akademik,
dan penelitian non-komersial**. Jika kamu ingin menggunakan ulang dataset
ini, silakan merujuk langsung ke sumber aslinya di Kaggle dan mematuhi
lisensi yang berlaku.

## Catatan

Setiap tahapan pengolahan pada notebook dijelaskan menggunakan Markdown
atau komentar `#` agar fungsi dari setiap proses dapat dipahami dengan
jelas.

---
