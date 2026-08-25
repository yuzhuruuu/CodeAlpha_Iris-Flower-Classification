# CodeAlpha_Iris_Classification

Task 1 dari **CodeAlpha Data Science Internship** — membangun model machine learning untuk mengklasifikasikan spesies bunga Iris (*setosa*, *versicolor*, *virginica*) berdasarkan pengukuran sepal dan petal.

## Deskripsi Proyek

Proyek ini menggunakan dataset klasik Iris untuk:
- Melakukan Exploratory Data Analysis (EDA) terhadap fitur-fitur bunga
- Melatih dan membandingkan beberapa model klasifikasi
- Mengevaluasi performa model menggunakan metrik akurasi, classification report, dan confusion matrix
- Menganalisis fitur mana yang paling berpengaruh dalam klasifikasi

## Dataset

Dataset yang digunakan adalah **Iris Dataset**, diambil langsung dari `sklearn.datasets` (150 sampel, 4 fitur numerik, 3 kelas seimbang):

| Fitur | Keterangan |
|---|---|
| sepal length (cm) | Panjang kelopak luar |
| sepal width (cm) | Lebar kelopak luar |
| petal length (cm) | Panjang kelopak dalam |
| petal width (cm) | Lebar kelopak dalam |
| species | Target: setosa / versicolor / virginica |

## Tools & Libraries

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (model & evaluasi)

## Alur Pengerjaan

1. **Import Library & Load Dataset**
2. **Exploratory Data Analysis (EDA)** — distribusi fitur, pairplot, heatmap korelasi
3. **Preprocessing** — train-test split (80:20) & standardisasi fitur
4. **Training Model** — Logistic Regression, KNN, Decision Tree, Random Forest, SVM
5. **Evaluasi Model** — akurasi, cross-validation, classification report, confusion matrix
6. **Feature Importance** — menggunakan Random Forest
7. **Uji Prediksi Manual** — mencoba model pada data baru
8. **Kesimpulan**

## Hasil Utama

- Seluruh model menghasilkan akurasi tinggi (>90%) pada data uji.
- Fitur `petal length` dan `petal width` adalah fitur paling berpengaruh dalam membedakan spesies.
- Kesalahan klasifikasi (jika ada) umumnya terjadi antara kelas *versicolor* dan *virginica* karena sedikit overlap pada fitur petal.

## Cara Menjalankan

```bash
git clone https://github.com/<username>/CodeAlpha_Iris_Classification.git
cd CodeAlpha_Iris_Classification
pip install -r requirements.txt
jupyter notebook CodeAlpha_Iris_Classification.ipynb
```

## Struktur Repo

```
CodeAlpha_Iris_Classification/
├── Iris_Classification.ipynb             # Notebook utama
├── Iris.csv                              # Dataset
├── README.md                             # Dokumentasi proyek
└── requirements.txt                      # Daftar dependencies
```

## Author

**Annisa Yusri Nur Rochmah**
Data Science Intern — CodeAlpha
📧 annisayusri59@gmail.com

## Tentang CodeAlpha

Task ini dikerjakan sebagai bagian dari **CodeAlpha Data Science Internship**.
🔗 [www.codealpha.tech](https://www.codealpha.tech)
