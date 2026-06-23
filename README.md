# Introduction to Machine Learning with Python - Code Reproduction & Theory Deep-Dive

Tugas ini merupakan pemenuhan poin individu untuk kelas pengayaan (Enrichment Class) Machine Learning dan Deep Learning. Fokus utama tugas ini adalah melakukan reproduksi kode program secara menyeluruh serta melakukan kajian teori mendalam yang bersumber dari buku **"Introduction to Machine Learning with Python"** oleh Andreas C. Müller & Sarah Guido (O'Reilly).

---

## 📋 Ringkasan Materi Per Bab

### [Chapter 1: Introduction](Chapter_01.ipynb)

- **Konsep Utama:** Pengenalan dasar Machine Learning, perbedaan taksonomi antara Supervised dan Unsupervised Learning.
- **Praktik Eksperimen:** Alur _end-to-end_ pertama menggunakan algoritma K-Nearest Neighbors (k-NN) pada dataset klasik Iris untuk klasifikasi spesies bunga.

### [Chapter 2: Supervised Learning](Chapter_02.ipynb)

- **Konsep Utama:** Eksplorasi mendalam mengenai algoritma klasifikasi dan regresi, konsep _overfitting_ vs _underfitting_, serta pentingnya kompleksitas model.
- **Praktik Eksperimen:** Implementasi k-NN, Linear Models (Ridge, Lasso, Logistic Regression), Decision Trees, Ensemble Methods (Random Forests, Gradient Boosting), Support Vector Machines (SVM), dan dasar Neural Networks (MLP) menggunakan Wisconsin Breast Cancer dataset.

### [Chapter 3: Unsupervised Learning and Preprocessing](Chapter_03.ipynb)

- **Konsep Utama:** Pengolahan data tanpa label (_target_) untuk reduksi dimensi, transformasi skala fitur, dan pengelompokkan data.
- **Praktik Eksperimen:** Penerapan transformasi data lewat `StandardScaler`, reduksi dimensi menggunakan _Principal Component Analysis_ (PCA) untuk visualisasi, serta algoritma pengelompokan menggunakan _K-Means Clustering_.

### [Chapter 4: Representing Data and Feature Engineering](Chapter_04.ipynb)

- **Konsep Utama:** Metode representasi tipe data non-numerik serta rekayasa fitur (_feature engineering_) untuk mendongkrak performa model.
- **Praktik Eksperimen:** Transformasi data kategori menggunakan _One-Hot Encoding_ (`get_dummies`), teknik binning, serta seleksi fitur otomatis menggunakan `SelectPercentile`.

### [Chapter 5: Model Evaluation and Improvement](Chapter_05.ipynb)

- **Konsep Utama:** Teknik evaluasi ketat performa model agar tidak bias serta taktik pencarian parameter (_hyperparameter tuning_) optimal.
- **Praktik Eksperimen:** Implementasi _Cross-Validation_ (Validasi Silang), otomatisasi pencarian parameter via _GridSearchCV_, serta pemanfaatan metrik evaluasi lanjutan (Confusion Matrix, Precision, Recall, f1-score, ROC AUC).

### [Chapter 6: Algorithm Chains and Pipelines](Chapter_06.ipynb)

- **Konsep Utama:** Standardisasi alur kerja pengolahan data untuk mencegah terjadinya kebocoran informasi dari data uji ke data latih (_data leakage_).
- **Praktik Eksperimen:** Enkapsulasi proses _preprocessing_ (`StandardScaler`) dan estimasi (`SVC`) menjadi satu kesatuan objek menggunakan modul `Pipeline` dari scikit-learn.

### [Chapter 7: Working with Text Data](Chapter_07.ipynb)

- **Konsep Utama:** Pemrosesan dan ekstraksi data teks (_Natural Language Processing_ dasar) menjadi representasi vektor angka yang dapat dipahami algoritma ML.
- **Praktik Eksperimen:** Tokenisasi dokumen dan pembobotan berbasis frekuensi kata menggunakan teknik _Bag-of-Words_ melalui objek `CountVectorizer`.

### [Chapter 8: Wrapping Up](Chapter_08.ipynb)

- **Konsep Utama:** Kesimpulan umum mengenai siklus iterasi pengerjaan proyek Machine Learning dari hulu ke hilir.
- **Poin Penting:** Penekanan bahwa rekayasa fitur, kebersihan data, dan evaluasi metrik yang tepat memegang peranan jauh lebih vital daripada sekadar mencoba model yang kompleks.

---

## 🛠️ Lingkungan Pengembangan & Pustaka (Dependencies)

Seluruh kode dalam repositori ini ditulis menggunakan bahasa pemrograman **Python** di dalam lingkungan kerja notebook (`.ipynb`) dengan dependensi pustaka utama sebagai berikut:

- `numpy`
- `matplotlib`
- `pandas`
- `scikit-learn`

### Cara Menjalankan secara Lokal:

1. Pastikan seluruh dependensi sudah terinstal pada komputer Anda:
   ```bash
   pip install numpy matplotlib pandas scikit-learn
   ```
