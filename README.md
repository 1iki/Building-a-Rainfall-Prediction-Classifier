# 🌧️ Building a Rainfall Prediction Classifier (and Machine Learning Labs)

> **IBM Machine Learning & Data Science Course Projects & Final Capstone**  
> *Proyek-Proyek Pembelajaran Mesin & Proyek Akhir Klasifikasi Prediksi Curah Hujan*

---

## 🇬🇧 Project Overview (English)

This repository contains a comprehensive collection of Machine Learning projects and laboratories built with Python, Scikit-Learn, Pandas, NumPy, and Matplotlib/Seaborn. The primary objective is to demonstrate various supervised learning techniques—ranging from regression to multi-class classification—culminating in an end-to-end **Rainfall Prediction Classifier** final project using Australian weather dataset (`weatherAUS.csv`).

### 📓 Repository Contents

1. **`FinalProject_AUSWeather.ipynb` (Main Capstone Project)**
   - **Goal**: Predict whether it will rain today in the Melbourne region using historical Australian weather data.
   - **Key Workflow**:
     - Data cleaning, location filtering (Melbourne, Melbourne Airport, Watsonia), and feature engineering (`Date` mapped to `Season`).
     - Automated preprocessing pipeline using `ColumnTransformer` (`StandardScaler` for numerical features and `OneHotEncoder` for categorical features).
     - Model building & Hyperparameter tuning using `GridSearchCV` with `Pipeline` (`RandomForestClassifier` vs `LogisticRegression`).
     - Model evaluation via Precision, Recall, F1-Score, Confusion Matrices, ROC-AUC, and Feature Importance analysis.

2. **`MODULE 4/Multi-class_Classification.ipynb`**
   - **Goal**: Multi-class classification strategies for Obesity Risk assessment.
   - **Techniques**: Comparison of One-vs-All (OvA) and One-vs-One (OvO) classification strategies using Logistic Regression, automated ML pipeline function `obesity_risk_pipeline`, and feature importance extraction.

3. **`Decision_trees.ipynb`**
   - **Goal**: Multi-class medical drug recommendation classifier based on patient health metrics (`drug200.csv`).
   - **Techniques**: Categorical feature label encoding, correlation analysis, Decision Tree Classifier (`entropy` criterion), tree depth visualization, and decision path extraction.

4. **`Logistic_Regression.ipynb`**
   - **Goal**: Binary classification for Telecommunications Customer Churn prediction (`ChurnData.csv`).
   - **Techniques**: Feature standardization (`StandardScaler`), Logistic Regression training, class probability prediction (`predict_proba`), feature coefficient weight visualization, and Log Loss evaluation across feature subsets.

5. **`Mulitple-Linear-Regression.ipynb`**
   - **Goal**: Multiple Linear Regression for vehicle CO2 Emissions prediction (`FuelConsumption.csv`).
   - **Techniques**: Multi-feature regression modeling, 3D surface plot fitting vs. actual observations, and feature-wise sub-modeling.

6. **`Simple-Linear-Regression.ipynb`**
   - **Goal**: Simple Linear Regression for vehicle CO2 emissions based on engine size and fuel consumption.
   - **Techniques**: Data splitting (`train_test_split`), model fitting, regression line plotting, and evaluation using Mean Squared Error (MSE), Mean Absolute Error (MAE), and $R^2$ score.

---

## 🇮🇩 Ringkasan Proyek (Bahasa Indonesia)

Repositori ini berisi koleksi lengkap dari proyek dan laboratorium Pembelajaran Mesin (*Machine Learning*) yang dibangun menggunakan Python, Scikit-Learn, Pandas, NumPy, dan Matplotlib/Seaborn. Tujuan utamanya adalah untuk mengimplementasikan berbagai teknik *supervised learning*—mulai dari regresi hingga klasifikasi multi-kelas—yang berpuncak pada **Proyek Akhir Klasifikasi Prediksi Curah Hujan** menggunakan data cuaca Australia (`weatherAUS.csv`).

### 📓 Isi Repositori

1. **`FinalProject_AUSWeather.ipynb` (Proyek Utama - Capstone)**
   - **Tujuan**: Memprediksi apakah akan turun hujan hari ini di wilayah Melbourne menggunakan data historis cuaca Australia.
   - **Alur Kerja Utama**:
     - Pembersihan data, pemfilteran lokasi (Melbourne, Melbourne Airport, Watsonia), dan rekayasa fitur (*Date* dipetakan menjadi *Season*).
     - Pra-pemrosesan otomatis menggunakan `ColumnTransformer` (`StandardScaler` untuk fitur numerik dan `OneHotEncoder` untuk fitur kategorikal).
     - Pembuatan model & tuning hiperparameter menggunakan `GridSearchCV` dengan `Pipeline` (`RandomForestClassifier` vs `LogisticRegression`).
     - Evaluasi model melalui Presisi, Recall, F1-Score, *Confusion Matrix*, dan analisis Tingkat Kepentingan Fitur (*Feature Importance*).

2. **`MODULE 4/Multi-class_Classification.ipynb`**
   - **Tujuan**: Strategi klasifikasi multi-kelas untuk penilaian Risiko Obesitas.
   - **Teknik**: Perbandingan strategi One-vs-All (OvA) dan One-vs-One (OvO) menggunakan Logistic Regression, fungsi pipeline ML otomatis `obesity_risk_pipeline`, dan ekstraksi *feature importance*.

3. **`Decision_trees.ipynb`**
   - **Tujuan**: Klasifikasi rekomendasi obat medis multi-kelas berdasarkan metrik kesehatan pasien (`drug200.csv`).
   - **Teknik**: *Label encoding* fitur kategorikal, analisis korelasi, *Decision Tree Classifier* (kriteria `entropy`), visualisasi kedalaman pohon, dan ekstraksi jalur keputusan.

4. **`Logistic_Regression.ipynb`**
   - **Tujuan**: Klasifikasi biner untuk prediksi *Customer Churn* telekomunikasi (`ChurnData.csv`).
   - **Teknik**: Standarisasi fitur (`StandardScaler`), pelatihan Logistic Regression, prediksi probabilitas kelas (`predict_proba`), visualisasi bobot koefisien fitur, dan evaluasi *Log Loss*.

5. **`Mulitple-Linear-Regression.ipynb`**
   - **Tujuan**: *Multiple Linear Regression* untuk prediksi Emisi CO2 kendaraan (`FuelConsumption.csv`).
   - **Teknik**: Pemodelan regresi banyak fitur, visualisasi permukaan 3D (*3D surface plot*), dan analisis regresi parsial.

6. **`Simple-Linear-Regression.ipynb`**
   - **Tujuan**: *Simple Linear Regression* untuk emisi CO2 kendaraan berdasarkan ukuran mesin dan konsumsi bahan bakar.
   - **Teknik**: Pembagian data (*train_test_split*), fitting model, visualisasi garis regresi, dan evaluasi menggunakan *Mean Squared Error* (MSE), *Mean Absolute Error* (MAE), serta skor $R^2$.

---

## 🛠️ Requirements & Installation

```bash
# Clone the repository
git clone https://github.com/1iki/Building-a-Rainfall-Prediction-Classifier.git

# Change directory
cd Building-a-Rainfall-Prediction-Classifier

# Install required Python packages
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 🚀 How to Run

Launch Jupyter Notebook or Jupyter Lab in the project directory:

```bash
jupyter notebook
```

Open any notebook of interest (e.g., `FinalProject_AUSWeather.ipynb`) and run all cells sequentially.

---
© IBM Machine Learning Course Project.
