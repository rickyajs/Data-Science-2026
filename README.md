# Selamat Datang & Hallo Perkenalkan Nama Saya Ricky Armanda Jaya Sirait, NIM : 240401020219 Kelas : IF401 Dari Prodi PJJ S1 Informatika Universitas Siber Asia.
# Tujuan Saya Belajar Data Science Ini Adalah Saya Sudah Mulai Tertarik Mempelajarinya Karena Data Science Sedang Populer Belakangan Ini.
# Tools / Library yang saya gunakan adalah kesuluruhan dari modul pertemuan matakuliah Data Science yang diberikan.
# Berikut adalah kesimpulan yang saya simpulkan dari modul pertemuan 1 sampai 13 yang telah saya pelajari :

# (*) Pertemuan 1: Pengenalan Data Science & CRISP-DM
Inti: Data Science menggabungkan Ilmu Komputer, Matematika/Statistika, dan Bisnis untuk mengubah data menjadi wawasan (insight).
Kerangka Kerja (CRISP-DM): Proses iteratif yang terdiri dari 6 tahap: Pemahaman Bisnis → Pemahaman Data → Persiapan Data → Pemodelan → Evaluasi → Penerapan (Deployment).
Ekosistem: Python, Google Colab/Jupyter Notebook, dan GitHub sebagai platform kolaborasi.

# (*) Pertemuan 2: Struktur Data Python, NumPy & Pandas
Struktur Data Python: List (bisa diubah), Tuple (tidak bisa diubah), Dictionary (kunci-nilai), dan Set (unik/tanpa duplikat).
NumPy: Digunakan untuk komputasi numerik cepat menggunakan operasi vektorisasi (ndarray).
Pandas: Digunakan untuk manipulasi data tabular melalui objek Series (1D) dan DataFrame (2D).

# (*) Pertemuan 3: Pembersihan Data (Data Cleaning)
Tujuan: Memastikan kualitas data agar tidak menghasilkan prediksi yang salah (Garbage In, Garbage Out).
Penanganan Masalah:
Missing values: Dihapus (dropping) atau diisi (imputasi mean/median).
Duplikat: Dihapus agar tidak mendistorsi statistik.
Outlier: Dideteksi dengan metode IQR (box plot) kemudian dihapus atau dibatasi (capping).

# (*) Pertemuan 4: Statistika Dasar & Analisis Data
Statistika Deskriptif: Mengukur pusat data (Mean, Median, Modus) dan penyebaran data (Standar Deviasi, Varians, Kuartil/IQR).
Bentuk Data: Dilihat dari kemiringan kurva (Skewness) dan keruncingannya (Kurtosis).
Analisis Hubungan: Menggunakan Analisis Univariat (satu variabel) dan Analisis Bivariat (dua variabel untuk melihat korelasi/hubungan, meski korelasi belum tentu berarti sebab-akibat).

# (*) Pertemuan 5: Visualisasi Data
Prinsip Utama: Harus jelas, akurat, efisien, estetis, dan memiliki konteks.
Tools: Matplotlib dan Seaborn.
Kerangka Insight: Menggunakan rumus What? (Apa datanya?), So What? (Apa dampaknya bagi bisnis?), dan Now What? (Apa rekomendasi tindakannya?).

# (*) Pertemuan 6: Persiapan Data (Preprocessing)
Data Splitting: Membagi data menjadi Data Train dan Data Test untuk mencegah kebocoran informasi (data leakage).
Encoding: Mengubah teks kategorikal menjadi angka lewat Label Encoding (untuk data berjenjang/ordinal) atau One-Hot Encoding (untuk data tanpa jenjang/nominal).
Scaling: Menyetarakan rentang nilai numerik menggunakan Standardization (Z-score) atau Normalization (MinMaxScaler 0-1) agar memproses semua variabel.

# (*) Pertemuan 7: Machine Learning — Regresi Linear
Konsep: Algoritma supervised learning untuk memprediksi angka kontinu berdasarkan hubungan garis lurus dengan variabel input.
Evaluasi Model: Dinilai menggunakan metrik eror seperti MAE, MSE, RMSE .
Evaluasi Visual (Residual Plot): Model dianggap baik jika penyebaran nilai erornya (residual) acak dan tidak membentuk pola tertentu.

# (*) Pertemuan 9: Algoritma Klasifikasi (Bagian 1)
Fokus Utama: Mengenal Supervised Learning untuk memprediksi kategori diskret (biner maupun banyak kelas).
Logistic Regression & Decision Tree: Logistic Regression memetakan probabilitas menggunakan fungsi Sigmoid. Sementara itu, Decision Tree menyusun aturan alur logis berdasarkan tingkat kemurnian data (Gini/Entropy), di mana batas kedalaman pohon perlu diatur agar model tidak overfitting.
Evaluasi Performa: Penilaian dilakukan lewat Confusion Matrix yang menghasilkan metrik Accuracy, Precision, Recall, dan F1-Score. Penentuannya disesuaikan dengan kebutuhan kasus (contoh: kasus medis mengutamakan Recall).

# (*) Pertemuan 10: Algoritma Klasifikasi (Bagian 2)
Ensemble Learning & Random Forest: Teknik ini menggabungkan performa beberapa model sekaligus. Random Forest memanfaatkan metode Bagging dan pemilihan fitur acak agar prediksi lebih stabil dan tahan terhadap overfitting. Solusi Imbalanced Dataset: Kelas data yang tidak seimbang bisa menipu metrik akurasi (Accuracy Paradox). Trik mengatasinya adalah dengan rekayasa data (oversampling via SMOTE atau undersampling), penyesuaian bobot kelas (class_weight), serta pengaturan ambang batas keputusan (threshold tuning).

# (*) Pertemuan 11: Unsupervised Learning: Clustering
Fokus Utama: Mengelompokkan data tanpa label berdasarkan tingkat kemiripannya.
K-Means vs. Hierarchical Clustering: K-Means membagi data ke dalam beberapa kelompok secara berulang mengelilingi titik centroid (sebaiknya diinisialisasi dengan K-Means++). Hierarchical Clustering membangun tingkatan struktur kelompok bertahap yang divisualisasikan melalui Dendrogram.
Penentuan Jumlah Klaster: Kombinasi Elbow Method (grafik penurunan WCSS) dan Silhouette Score digunakan untuk menentukan jumlah kelompok ($K$) yang paling pas.

# (*) Pertemuan 12: Asosiasi Data & Sistem Rekomendasi
Association Rule Mining: Menemukan tren keterikatan antar-item (contoh: Market Basket Analysis) menggunakan algoritma Apriori. Hubungan ini diukur lewat metrik Support (frekuensi), Confidence (kepastian), dan Lift (kekuatan korelasi).
Sistem Rekomendasi: Terdiri dari Collaborative Filtering (berbasis kemiripan kebiasaan pengguna) dan Content-Based Filtering (berbasis kesamaan atribut produk, seperti Cosine Similarity). Keduanya sering digabung (Hybrid) dan diuji menggunakan Precision/Recall.

# (*) Pertemuan 13: Pengantar Deep Learning & NLP Dasar
Machine Learning vs. Deep Learning: ML klasik membutuhkan ekstraksi fitur manual, sedangkan Deep Learning bisa mengekstrak fitur secara otomatis dari data tak terstruktur (teks, gambar, audio) menggunakan jaringan saraf (Neural Network).
Konsep ANN & NLP: Neural Network bekerja lewat Input, Hidden, dan Output Layer yang dilatih menggunakan Forward Pass dan Backpropagation. Pada NLP, data teks dikonversi ke angka via metode seperti TF-IDF untuk keperluan analisis (seperti analisis sentimen).
