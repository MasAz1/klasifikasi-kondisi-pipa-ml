# Klasifikasi Kondisi Pipa Berdasarkan Debit dan Tekanan

Project ini merupakan implementasi machine learning untuk mengklasifikasikan kondisi pipa air berdasarkan parameter Pressure dan Flow_Rate menggunakan metode Logistic Regression dengan Polynomial Features.

## Metode

Model machine learning dibangun menggunakan beberapa tahapan, yaitu:

- Preprocessing data
- Polynomial Features
- StandardScaler
- SMOTE
- Logistic Regression
- GridSearchCV

## Dataset

Fitur yang digunakan dalam penelitian ini adalah:

- Pressure
- Flow_Rate

Target klasifikasi:

- Leakage_Flag

## Output Klasifikasi

- 0 = Normal
- 1 = Bocor

## Cara Menjalankan Project

Install library yang dibutuhkan:

```bash
pip install -r requirements.txt
