# Database for Machine Learning 🧠

> **Dataset untuk pembelajaran mesin — Klasifikasi dan analisis sereal**

Repositori ini berisi dataset yang dirancang untuk keperluan **pembelajaran mesin (machine learning)**. Dataset ini berisi data sereal dengan atribut yang dapat digunakan untuk tugas klasifikasi, clustering, atau analisis data eksploratif.

---

## 📁 Dataset

| File | Deskripsi |
|------|-----------|
| `cereal_imp.csv` | Dataset sereal dengan atribut nutrisi dan kategori |

### Potensi Penggunaan
- **Klasifikasi** — Memprediksi jenis/kategori sereal
- **Clustering** — Segmentasi produk berdasarkan karakteristik nutrisi
- **Regresi** — Memprediksi nilai nutrisi berdasarkan komposisi
- **Visualisasi Data** — EDA (Exploratory Data Analysis)

---

## 🛠️ Tech Stack (Recommended)

- **Python:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Google Colab / Jupyter Notebook**

### Contoh Load
```python
import pandas as pd
df = pd.read_csv('cereal_imp.csv')
print(df.info())
print(df.describe())
```

---

## 📄 Lisensi

**MIT License**

---

> Dataset oleh [Pandu Pangestu](https://github.com/pandupan) — Untuk keperluan pembelajaran machine learning.
