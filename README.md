# Australia-Used-Car-Price-Prediction
Machine learning project to predict used car prices in the Australian market using multiple regression models (KNN, SVR, Decision Tree, Random Forest, Gradient Boosting). Evaluated with MAE and Cross Validation, optimized via hyperparameter tuning, and deployed with Streamlit on Hugging Face Spaces.

# Repository Outline

README.md – Penjelasan gambaran umum project

P1M2_Kevin_Hibatul.ipynb – Notebook berisi proses data cleaning, EDA, feature engineering, pembuatan model, cross validation, hyperparameter tuning, dan evaluasi model

australia_car_data.csv – Dataset mentah (raw) hasil download dari Kaggle

deployment/ – Berisi file aplikasi Streamlit untuk deployment di Hugging Face

# Latar Belakang Masalah

Industri otomotif merupakan salah satu pasar terbesar dengan dinamika harga yang kompleks. Harga mobil bekas tidak hanya ditentukan oleh satu faktor, tetapi dipengaruhi oleh berbagai aspek seperti merek, tahun produksi, kapasitas mesin, jarak tempuh, jenis bahan bakar, tipe transmisi, dan jumlah kursi.

Baik bagi konsumen maupun dealer, menentukan harga mobil bekas yang wajar merupakan tantangan besar. Kesalahan dalam menentukan harga dapat menyebabkan kerugian finansial. Oleh karena itu, pendekatan berbasis data menggunakan machine learning diperlukan untuk menghasilkan prediksi harga yang lebih akurat dan objektif.

# Tujuan Project

Membangun model machine learning regresi yang mampu memprediksi harga mobil bekas di pasar Australia secara akurat dan berbasis data.

# Output Project

Output dari project ini meliputi:

Model machine learning regresi yang telah dilatih

Evaluasi model menggunakan Cross Validation dan MAE

Aplikasi web interaktif berbasis Streamlit yang dideploy di Hugging Face Spaces untuk melakukan EDA dan prediksi harga mobil

# Data

Dataset diperoleh dari platform Kaggle dan berisi data listing mobil bekas di pasar Australia.

Dataset mencakup fitur-fitur seperti:

Brand

Year

Kilometers

Engine Capacity (CC)

Seating Capacity

Fuel Type

Gearbox

Price

Dataset kemudian disimpan dengan nama:

australia_car_data.csv
# Metodologi

Dalam project ini digunakan beberapa algoritma regresi:

K-Nearest Neighbors (KNN)

Support Vector Regressor (SVR)

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Tahapan yang dilakukan:

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Training model baseline

Cross Validation

Perbandingan model menggunakan MAE

Hyperparameter Tuning (GridSearchCV)

Pemilihan model terbaik

Deployment menggunakan Streamlit

Metric evaluasi yang digunakan adalah Mean Absolute Error (MAE) karena mudah diinterpretasikan dan relevan dengan konteks bisnis.

# Tech Stack

Bahasa Pemrograman:

Python

Library yang digunakan:

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

SciPy

Joblib

Deployment:

Streamlit

Hugging Face Spaces

# Referensi

Dataset Kaggle:
https://www.kaggle.com/datasets/lainguyn123/australia-car-market-data)

Deployment Hugging Face:
(https://huggingface.co/spaces/kiel145/Kevin-Hibatul-Deployment)

# Kesimpulan

Project ini berhasil membangun dan mengevaluasi beberapa model regresi untuk memprediksi harga mobil bekas. Random Forest menjadi model terbaik setelah dilakukan hyperparameter tuning. Model kemudian dideploy dalam bentuk aplikasi web interaktif untuk mendukung pengambilan keputusan berbasis data.
