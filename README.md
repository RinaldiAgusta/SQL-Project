# 🧹 SQL Project: Data Cleaning - Layoffs Dataset (Kaggle)

*Dataset*: [Layoffs 2022 - Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022)

## 📝 Deskripsi
Proyek ini berfokus pada proses pembersihan data menggunakan SQL terhadap data layoffs perusahaan teknologi tahun 2022. Data mentah dibersihkan dan distandarisasi agar siap untuk dianalisis lebih lanjut seperti EDA dan visualisasi.

## ⚙ Langkah Pembersihan Data
- 🔁 *Menghapus Duplikat* menggunakan ROW_NUMBER() dan CTE.
- 📊 *Standarisasi Data*:
  - Mengisi NULL pada kolom industry berdasarkan nama perusahaan.
  - Menyatukan penulisan variasi seperti CryptoCurrency → Crypto.
  - Menghapus trailing karakter seperti titik (.) pada nama negara.
  - Mengubah format kolom date dari string ke format DATE.
- ❓ *Penanganan Nilai Null*:
  - Menghapus baris yang tidak memiliki informasi penting (total_laid_off & percentage_laid_off).
- 🧱 *Optimalisasi Struktur*:
  - Menghapus kolom sementara yang tidak dibutuhkan seperti row_num.

## 🧠 Tools & Skillset
- SQL (CTE, Subquery, ROW_NUMBER, JOIN, UPDATE, DELETE)
- Data profiling
- Data cleaning best practices
- Missing value handling
- String normalization & data type conversion

## ✅ Output
Dataset yang bersih dan terstruktur, siap untuk eksplorasi data lebih lanjut atau digunakan di tools BI seperti Tableau / Power BI.
