# Klasifikasi Kategori Obesitas Menggunakan Algoritma Decision Tree dan Random Forest

## Deskripsi Proyek

Proyek ini bertujuan membangun model *Machine Learning* untuk mengklasifikasikan kategori obesitas berdasarkan karakteristik individu menggunakan algoritma *Decision Tree* dan *Random Forest*. Selain membangun model, proyek ini juga membandingkan performa kedua algoritma berdasarkan metrik evaluasi yang digunakan.

---

## Dataset

Dataset yang digunakan berasal dari Kaggle:

https://www.kaggle.com/datasets/mrsimple07/obesity-prediction

Jumlah data:
- 1000 data
- 7 atribut
- Format CSV

Target klasifikasi:
- Normal Weight
- Overweight
- Obese
- Underweight

---

## Tools dan Library

Proyek ini dikembangkan menggunakan:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Langkah Pengerjaan

Tahapan yang dilakukan pada proyek ini meliputi:

1. Business Understanding
2. Data Understanding
3. Exploratory Data Analysis (EDA)
4. Data Preparation
5. Modeling
6. Evaluation
7. Kesimpulan dan Rekomendasi

---

## Algoritma

Algoritma yang digunakan:

- Decision Tree
- Random Forest

---

## Hasil Evaluasi

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|---------:|----------:|--------:|---------:|
| Decision Tree | 0.9150 | 0.9161 | 0.9150 | 0.9147 |
| Random Forest | 0.9350 | 0.9378 | 0.9350 | 0.9351 |

Berdasarkan hasil evaluasi, algoritma **Random Forest** memperoleh performa terbaik pada seluruh metrik evaluasi.

---

## Struktur Repository

```
.
├── Data/
│   ├── Dataset/
│   │   └── obesity_data.csv
│   └── Jurnal/
│       └── Referensi jurnal yang digunakan
├── media/
│   └── Seluruh gambar laporan
├── Prediksi Kategori Obesitas.ipynb
├── Laporan_UAS.md
└── README.md
```

---

## Cara Menjalankan

1. Clone repository.

```bash
git clone https://github.com/USERNAME/NAMA_REPOSITORY.git
```

2. Buka file:

```
Prediksi Kategori Obesitas.ipynb
```

3. Jalankan notebook dari awal hingga akhir.

---

## Penulis

- Nama : Sani Aulia Nurafifah
- NIM : 2406086
- Kelas : C
