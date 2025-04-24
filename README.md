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
  - - `sentiment_model.keras`              : Model Keras hasil training untuk analisis sentimen  
  - `tfidf_vectorizer.pkl`           : TF-IDF vectorizer hasil training untuk memproses teks  
- `raw_data_lgr.csv`               : Dataset hasil scraping review game Getrich dari Google Play  
- `scraping/`                      : Folder untuk proses scraping data
  - `scraping_review.ipynb`        : Notebook scraping review dari Google Play  
- `requirements.txt`               : File daftar pustaka yang dibutuhkan  
- `README.md`                      : Dokumentasi utama proyek  


## ▶️ File Proyek

1. **Latih model** dengan menjalankan file:
File ini berisi preprocessing data, pelabelan, ekstraksi fitur, dan pelatihan model.

2. **Jalankan demo model (deployment)**:
3. File ini menampilkan antarmuka input ulasan, lalu model akan memprediksi sentimennya.

---

## 🚀 Cara Menjalankan Proyek

Berikut adalah langkah-langkah yang dapat diikuti untuk menjalankan proyek ini:

### 1. Menyiapkan Lingkungan Virtual

Sebelum memulai, pastikan Anda menggunakan virtual environment agar dependensi proyek terisolasi dengan baik. Untuk membuat dan mengaktifkan lingkungan virtual, jalankan perintah berikut di terminal:

- **Untuk Windows:**
  ```bash
  python -m venv venv
  .\venv\Scripts\activate

- **Untuk Linux/mac:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  
### 2. Instalasi Dependensi
 pip install -r requirements.txt
 
### 3. Jalankan proyek
 - File Proces and Modelling.ipynb
 - File deploy.ipynb


