<div align="center">

# ⛏️✨ Data Mining Practice ✨⛏️

### 📚 Kumpulan Kebutuhan Praktikum Penambangan Data 📚

*Dataset • Modul • Eksperimen • Tugas Praktikum*

[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-ff69b4?style=for-the-badge)](https://github.com/matthewpriantara/Data_Mining_Practice)
[![Data Mining](https://img.shields.io/badge/Field-Data%20Mining-7c3aed?style=for-the-badge&logo=database&logoColor=white)](https://github.com/matthewpriantara/Data_Mining_Practice)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

---

> 🌸 *"Dari data mentah menjadi wawasan bermakna"* 🌸

</div>

## 🌷 Halo, Selamat Datang! 🌷

Halo semuanya! 👋 Repository ini adalah **arsip pusat** untuk semua hal yang diperlukan selama **Praktikum Penambangan Data (Data Mining)**.

Mulai dari 📦 **dataset**, 📓 **notebook eksperimen**, 🧪 **tugas tiap pertemuan**, sampai 🛠️ **script preprocessing & modeling** — semuanya dikumpulkan rapi di satu tempat biar gampang diakses, dipelajari ulang, dan dikembangkan lagi! 💖

---

## 🎯 Tujuan Repository

| ✨ Poin | 📝 Penjelasan |
| :--- | :--- |
| 📦 **Sentralisasi Dataset** | Menyimpan semua dataset praktikum agar mudah diunduh & digunakan ulang |
| 🧪 **Dokumentasi Praktikum** | Mencatat setiap eksperimen & analisis tiap pertemuan |
| 🔄 **Reproducibility** | Memastikan setiap analisis bisa dijalankan ulang oleh siapa pun |
| 🌱 **Media Belajar** | Tempat belajar preprocessing, klasifikasi, clustering, & evaluasi model |

---

## 🗂️ Struktur Repository

```bash
📁 Data_Mining_Practice/
│
├── 📁 pert_2/                  # 💳 Pertemuan 2 — Analisis Churn Nasabah Bank
│   ├── 📊 BankChurners.csv     #    Dataset utama (±10.127 baris)
│   └── 🗜️ BankChurners.csv.zip #    Versi terkompresi
│
├── 📁 pert_3/                  # 🏦 Pertemuan 3 — Prediksi Persetujuan Pinjaman
│   ├── 📊 loan_data.csv        #    Dataset utama (381 baris)
│   └── 🗜️ archive.zip          #    Arsip pendukung
│
└── 📄 README.md                # 💖 Kamu sedang membacanya!
```

> 📌 *Struktur akan terus bertambah seiring berjalannya praktikum! Stay tuned~* ✨

---

## 📊 Katalog Dataset

### 💳 Pertemuan 2 — `BankChurners.csv`

> Analisis perilaku & churn nasabah kartu kredit bank 🏧

| 🏷️ Info | 📋 Detail |
| :--- | :--- |
| 📁 Lokasi | `pert_2/BankChurners.csv` |
| 📏 Ukuran | ~1.4 MB • 10.127 baris × 23 kolom |
| 🎯 Target | `Attrition_Flag` (Existing Customer / Attrited Customer) |
| ✨ Fitur Menarik | `Customer_Age`, `Gender`, `Credit_Limit`, `Total_Trans_Amt`, `Total_Trans_Ct`, `Avg_Utilization_Ratio`, `Card_Category` |
| 🧪 Cocok Untuk | Klasifikasi Churn, EDA, Feature Engineering, Naive Bayes |

### 🏦 Pertemuan 3 — `loan_data.csv`

> Prediksi status persetujuan pinjaman 💰

| 🏷️ Info | 📋 Detail |
| :--- | :--- |
| 📁 Lokasi | `pert_3/loan_data.csv` |
| 📏 Ukuran | ~26 KB • 381 baris × 13 kolom |
| 🎯 Target | `Loan_Status` (Y / N) |
| ✨ Fitur Menarik | `Gender`, `Married`, `Education`, `ApplicantIncome`, `LoanAmount`, `Credit_History`, `Property_Area` |
| 🧪 Cocok Untuk | Data Cleaning (missing value!), Klasifikasi Biner, Logistic Regression, Decision Tree |

---

## 🧭 Roadmap Praktikum

```mermaid
graph LR
    A[📥 Data Collection] --> B[🧹 Preprocessing]
    B --> C[🔍 EDA & Visualisasi]
    C --> D[🤖 Modeling]
    D --> E[📏 Evaluasi]
    E --> F[💡 Insight]
```

- [x] ✅ **Pert 2** — Eksplorasi dataset BankChurners
- [x] ✅ **Pert 3** — Preprocessing & klasifikasi data pinjaman
- [ ] 🔜 **Pert 4+** — Clustering, Association Rule, & Model Tuning
- [ ] 🌟 **Final** — Mini Project Data Mining

---

## 🚀 Cara Penggunaan

### 1️⃣ Clone repository ini 💻

```bash
git clone https://github.com/matthewpriantara/Data_Mining_Practice.git
cd Data_Mining_Practice
```

### 2️⃣ Siapkan environment Python 🐍

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3️⃣ Load dataset di notebook 📓

```python
import pandas as pd

# 💳 Dataset Pertemuan 2
df_churn = pd.read_csv("pert_2/BankChurners.csv")
print(df_churn.shape)
print(df_churn.head())

# 🏦 Dataset Pertemuan 3
df_loan = pd.read_csv("pert_3/loan_data.csv")
print(df_loan.shape)
print(df_loan.head())
```

### 4️⃣ Mulai eksplorasi! 🔍✨

```python
# Cek missing value 👀
df_loan.isnull().sum()

# Statistik deskriptif 📊
df_churn.describe(include="all")
```

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-76B900?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## 🤝 Kontribusi

Kontribusi selalu terbuka lebar! 🌈

1. 🍴 Fork repo ini
2. 🌱 Buat branch baru (`git checkout -b pert-4-clustering`)
3. 💾 Commit perubahanmu (`git commit -m "add: eksperimen clustering pert 4"`)
4. 🚀 Push & buat Pull Request

---

## 👨‍💻 Author

<div align="center">

**Made with 💖 by [matthewpriantara](https://github.com/matthewpriantara)**

*TRPL • Semester 5 • Praktikum Penambangan Data*

⭐ Jangan lupa kasih **star** kalau repo ini membantu kamu! ⭐

---

🌸 *Happy Mining! Semoga datanya bersih & akurasinya tinggi!* 📈✨

</div>
