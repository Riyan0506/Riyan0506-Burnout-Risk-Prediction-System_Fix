# 🔥 Burnout Risk Prediction System

AI-Powered Employee Wellness Monitoring Platform

## 📖 Overview

Burnout Risk Prediction System adalah platform berbasis Artificial Intelligence yang dirancang untuk membantu organisasi mendeteksi risiko burnout karyawan secara dini, memberikan rekomendasi tindakan preventif, serta mendukung pengambilan keputusan berbasis data.

Proyek ini menggabungkan pendekatan Data Science, Machine Learning, Deep Learning, REST API, dan Interactive Dashboard dalam satu solusi end-to-end yang siap digunakan untuk kebutuhan analisis dan monitoring kesejahteraan karyawan.

---

## 🎯 Problem Statement

Burnout merupakan salah satu tantangan terbesar dalam lingkungan kerja modern karena dapat menyebabkan:

* Penurunan produktivitas
* Tingginya turnover karyawan
* Menurunnya kepuasan kerja
* Peningkatan biaya operasional perusahaan

Melalui proyek ini, organisasi dapat mengidentifikasi individu yang berisiko mengalami burnout sebelum dampak yang lebih besar terjadi.

---

## 🚀 Key Features

### Employee Burnout Prediction

Melakukan prediksi tingkat risiko burnout menggunakan model Machine Learning dan Deep Learning yang telah dilatih menggunakan data karyawan.

### AI Recommendation Engine

Memberikan rekomendasi personal berdasarkan kondisi masing-masing karyawan, termasuk:

* Work-life balance suggestions
* Stress reduction strategies
* Productivity improvement recommendations

### Interactive Dashboard

Dashboard Streamlit menyediakan:

* KPI Monitoring
* Burnout Analytics
* Risk Distribution
* Individual Assessment
* Model Evaluation

### REST API Service

FastAPI digunakan untuk menyediakan endpoint prediksi yang dapat diintegrasikan ke aplikasi lain.

### Email Notification

Mengirimkan laporan hasil prediksi dan rekomendasi secara otomatis.

### Google Calendar Integration

Membantu pengguna menjadwalkan aktivitas wellness dan recovery secara otomatis.

---

## 🧠 Machine Learning & AI Pipeline

Data Collection
↓
Data Wrangling
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Machine Learning Modeling
↓
Deep Learning Modeling
↓
Model Evaluation
↓
Model Export (.keras)
↓
Inference Service
↓
FastAPI Deployment
↓
Streamlit Dashboard

---

## 📊 Dashboard Preview

Dashboard menyediakan beberapa modul utama:

### Executive Dashboard

Menampilkan ringkasan kondisi burnout organisasi secara keseluruhan.

### Employee Assessment

Prediksi burnout untuk individu berdasarkan input pengguna.

### Analytics Dashboard

Visualisasi data dan insight hasil analisis.

### AI Recommendation Panel

Rekomendasi personal yang dihasilkan secara otomatis.

---

## 🏗️ Project Structure

```text
burnout_ds_project/

├── burnout_analysis.py
├── dashboard_burnout.py
├── model_deep_learning.py
├── inference.py
├── api_server.py
├── generative_ai_recommendations.py
├── email_notification.py
├── google_calendar_integration.py
├── models/
├── exported_models/
├── logs/
├── synthetic_employee_burnout.csv
├── data_dictionary.csv
└── README.md
```

---

## 🛠️ Technologies Used

### Data Science

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn

### Deep Learning

* TensorFlow
* Keras

### Backend

* FastAPI

### Dashboard

* Streamlit

### AI Integration

* Generative AI API

---

## 📈 Results

Model berhasil mencapai performa yang memenuhi target proyek dengan metrik evaluasi yang baik pada data validasi dan data uji.

Evaluasi dilakukan menggunakan:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

Model produksi diekspor ke format TensorFlow `.keras` untuk kebutuhan deployment dan inference.

---

## 💻 Installation

### Clone Repository

```bash
git clone <repository-url>
cd burnout_ds_project
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running The Project

### Run Analysis Pipeline

```bash
python burnout_analysis.py
```

### Train Deep Learning Model

```bash
python model_deep_learning.py
```

### Run Dashboard

```bash
streamlit run dashboard_burnout.py
```

### Run API

```bash
python api_server.py
```

---

# ✅ Coding Camp Requirements Coverage

Bagian ini menunjukkan bagaimana proyek memenuhi kriteria yang ditetapkan pada program Coding Camp.

## Data Science Requirements

### Problem Discovery

Proyek dimulai dengan identifikasi permasalahan burnout pada lingkungan kerja modern dan perumusan pertanyaan bisnis yang dapat diukur.

### Data Wrangling

Tahapan yang dilakukan:

* Gathering Data
* Assessing Data
* Cleaning Data

### Exploratory Data Analysis

Dilakukan analisis statistik dan visualisasi untuk memahami pola burnout dan faktor-faktor yang memengaruhinya.

### Explanatory Analysis

Visualisasi dan insight digunakan untuk menjawab pertanyaan bisnis yang telah ditentukan.

### Interactive Dashboard

Insight dan hasil analisis ditampilkan melalui dashboard Streamlit yang interaktif.

### Data Dictionary

Dokumentasi atribut data disediakan untuk meningkatkan interpretabilitas dataset.

---

## Artificial Intelligence Requirements

### Deep Learning

Model dibangun menggunakan TensorFlow dan Keras sesuai kebutuhan permasalahan bisnis yang telah didefinisikan.

### Custom Component

Proyek mengimplementasikan komponen kustom TensorFlow untuk meningkatkan fleksibilitas pelatihan model.

### Model Export

Model hasil pelatihan diekspor ke format `.keras` yang siap digunakan untuk deployment.

### Inference Pipeline

Disediakan pipeline inferensi untuk melakukan prediksi pada data baru.

### REST API

Model dapat diakses melalui FastAPI menggunakan endpoint RESTful.

### AI Feature Integration

Prediksi burnout menjadi fitur utama aplikasi dan terintegrasi dengan dashboard serta API.

---

## ⭐ Additional Implementations

Selain memenuhi kebutuhan utama, proyek juga mengimplementasikan beberapa fitur tambahan:

* Feature Engineering
* A/B Testing
* TensorBoard Monitoring
* Generative AI Recommendations
* Email Notification System
* Google Calendar Integration
* FastAPI Deployment Architecture

---

## 🔮 Future Improvements

Beberapa pengembangan yang dapat dilakukan pada versi berikutnya:

* Database Integration
* Cloud Deployment
* Real-Time Monitoring
* Advanced Explainable AI (XAI)
* Multi-Tenant Organization Support

---

## 👨‍💻 Team

Coding Camp 2026 Capstone Project

Theme:
Healthy Lives & Well-being
