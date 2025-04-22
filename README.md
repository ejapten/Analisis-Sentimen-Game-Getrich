# 🕹️ Analisis Sentimen Game Getrich

Proyek ini dibuat untuk menganalisis ulasan pemain terhadap game **GetRich** dan mengklasifikasikan sentimen dari ulasan tersebut ke dalam tiga kategori: **positif**, **negatif**, atau **netral**. Model ini diharapkan bisa membantu pengembang untuk melihat respon pemain secara otomatis.

---

## 📦 Library yang Digunakan

- Python  
- TensorFlow  
- Scikit-learn  
- Pandas  
- Matplotlib  
- Gensim  
- NLTK  
- Langid  
- Gradio *(untuk deployment)*

---

## 🗂️ Struktur Folder Proyek

- `Proses and Modelling.ipynb`   : Notebook untuk training dan evaluasi model  
- `deploy/`                        : Folder berisi file untuk deployment
  - `deploy.ipynb`                 : Notebook untuk menjalankan model secara interaktif
  - - `model_sentimen.h5`              : Model Keras hasil training untuk analisis sentimen  
  - `tfidf_vectorizer.pkl`           : TF-IDF vectorizer hasil training untuk memproses teks  
- `raw_data_lgr.csv`               : Dataset hasil scraping review game Getrich dari Google Play  
- `scraping/`                      : Folder untuk proses scraping data
  - `scraping_review.ipynb`        : Notebook scraping review dari Google Play  
- `requirements.txt`               : File daftar pustaka yang dibutuhkan  
- `README.md`                      : Dokumentasi utama proyek  


## ▶️ Cara Menjalankan Proyek

1. **Latih model** dengan menjalankan file:
File ini berisi preprocessing data, pelabelan, ekstraksi fitur, dan pelatihan model.

2. **Jalankan demo model (deployment)**:
3. File ini menampilkan antarmuka input ulasan, lalu model akan memprediksi sentimennya.

---
