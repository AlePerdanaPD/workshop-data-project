# Workshop Data Project

Proyek latihan untuk memahami kolaborasi data menggunakan Git, GitHub, dan Kaggle Notebook.

## Tujuan
- Memahami struktur proyek data yang baik
- Belajar kolaborasi menggunakan Git dan GitHub
- Melakukan eksplorasi data dengan Kaggle Notebook
- Mendokumentasikan analisis dengan Markdown

## Dataset
- **Nama**: Iris Species  
- **Sumber**: [UCI ML Repository via Kaggle](https://www.kaggle.com/datasets/uciml/iris)  
- **Lisensi**: Public Domain  
- **Deskripsi**: Dataset klasifikasi 3 spesies bunga Iris berdasarkan 4 fitur morfologis (sepal length, sepal width, petal length, petal width).
- **Jumlah Data**: 150 sampel dengan 3 spesies (Iris-setosa, Iris-versicolor, Iris-virginica)

## Struktur Proyek
workshop-data-project/</br>
├── data/</br>
│ ├── raw/</br>
│ └── processed/</br>
├── notebooks/</br>
├── README.md</br>
└── requirements.txt


## Analisis & Insight
Notebook eksplorasi data lengkap tersedia di Kaggle:</br>
- [EDA: Iris Species – Visualisasi & Storytelling](https://www.kaggle.com/username/nama-notebook)

### Ringkasan Insight
- Fitur petal sangat diskriminatif untuk membedakan spesies.
- Iris setosa terpisah sempurna dari versicolor & virginica.
- Tidak ada missing value → dataset siap untuk modeling.

## Cara Menggunakan Repository Ini
1. Clone repository: `git clone <url-repository>`
2. Navigasi ke folder: `cd workshop-data-project`
3. Buka Kaggle Notebook dari link di atas untuk melihat analisis
4. Untuk berkontribusi: buat branch baru, commit perubahan, dan buat pull request

## Best Practices
- ✅ Jangan ubah file di `data/raw/` — gunakan `data/processed/` untuk data hasil olahan
- ✅ Dokumentasikan setiap notebook dengan markdown cells
- ✅ Gunakan nama file yang deskriptif
- ✅ Commit dengan pesan yang jelas dan singkat
- ✅ Update README seiring perkembangan proyek

## Tim Kontributor
- [Ale Perdana Putra Darmawan] - Owner
- [Achmad Risel Araby] - Maintainer
