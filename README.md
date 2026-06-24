# finalterm-machine-learning

**Deskripsi**

Repository ini berisi dua implementasi proyek Machine Learning menggunakan pendekatan Deep Learning, yaitu:
1.  **Proyek Regresi** – Prediksi tahun rilis lagu berdasarkan karakteristik audio.
   * Dataset: midterm-regresi-dataset.csv
   * Tujuan: Memprediksi tahun rilis lagu berdasarkan fitur audio.
2. * **Proyek Klasifikasi** – Deteksi transaksi fraud berdasarkan data transaksi.
   * Dataset: train_transaction.csv
   * Tujuan: Mengklasifikasikan transaksi fraud dan non-fraud.

Kedua proyek mencakup seluruh tahapan machine learning, mulai dari eksplorasi data, preprocessing, pelatihan model, hyperparameter tuning, evaluasi model, hingga pelacakan eksperimen menggunakan MLflow.

**Metode yang Digunakan**
* Data Preprocessing
* Feature Scaling
* Deep Learning (Artificial Neural Network)
* Hyperparameter Tuning menggunakan Optuna
* Experiment Tracking menggunakan MLflow
* Interpretasi Model menggunakan LIME

**Metrik Evaluasi**
1. Regresi
   * MSE
   * RMSE
   * MAE
   * R² Score
2. Klasifikasi
   * Accuracy
   * Precision
   * Recall
   * F1-Score
   * ROC AUC
   * Struktur Rep
  
**Cara Menjalankan**
1. Gunakan kernel Py 3.11.9
2. Download file dataset (CSV)
3. Buka notebook jupyter
4. Lakukan Run All di notebook
5. Lalu buka ketik diterminal:
   py -3.11 -m mlflow ui --backend-store-uri sqlite:///mlflow.db
6. Jika sudah buka http://127.0.0.1:5000/       


**Nama: Fidela Risyunira**
| **NIM: 101032300001**
| **CLASS: TK-46-GAB**
