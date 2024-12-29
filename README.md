# Clustering Data Acak Menggunakan K-Means  

Proyek ini bertujuan untuk mempelajari dan menerapkan algoritma **K-Means Clustering** pada dataset acak yang dihasilkan secara random. Selain itu, proyek ini menggunakan **Elbow Method** untuk menentukan jumlah cluster terbaik dan mengevaluasi hasil clustering dengan **Silhouette Score**.  

---

## 🧠 Deskripsi Singkat  
Dataset yang digunakan dalam proyek ini adalah data acak dengan dua dimensi, **x** dan **y**, yang berisi 500 baris. Proyek ini mencakup berbagai tahapan dari membaca data, analisis eksplorasi, hingga visualisasi hasil clustering.  

---

## 📊 Data  
- **Sumber Data**: File `cluster_s1.csv`  
- **Ukuran Dataset**: 500 baris data acak  
- **Kolom Data**:  
  - **`x`**: Nilai acak 1  
  - **`y`**: Nilai acak 2  

---

## ⚙️ Tahapan Proses  
1. **Import Library yang Dibutuhkan**  
   - Menggunakan library Python seperti `pandas`, `matplotlib`, `seaborn`, dan `scikit-learn`.  

2. **Membaca Dataset**  
   - Dataset di-load dari file CSV menggunakan `pandas`.  

3. **Visualisasi Data Awal**  
   - Scatter plot untuk melihat distribusi awal data acak.  

4. **Mencari Jumlah Cluster Terbaik**  
   - Menggunakan **Elbow Method** dengan memplot nilai inertia terhadap jumlah cluster.  

5. **Clustering dengan K-Means**  
   - Menerapkan algoritma K-Means dengan jumlah cluster yang optimal.  

6. **Evaluasi Hasil Clustering**  
   - Menghitung **Silhouette Score** untuk mengevaluasi seberapa baik data terkelompok.  

7. **Visualisasi Hasil Clustering**  
   - Scatter plot dengan warna berbeda untuk setiap cluster.  

---

## 📊 Hasil Analisis  
- **Jumlah Cluster Optimal**: 15 cluster (ditemukan menggunakan Elbow Method).  
- **Evaluasi Clustering**:  
  - **Silhouette Score** menunjukkan bahwa cluster yang dihasilkan cukup baik.  

### Visualisasi Elbow Curve  
![Elbow Curve](https://via.placeholder.com/800x400)  
*Elbow point menunjukkan jumlah cluster terbaik pada 15 cluster.*  

### Visualisasi Hasil Clustering  
![Cluster Visualization](https://via.placeholder.com/800x400)  
*Data acak yang telah dikelompokkan menjadi 15 cluster.*  

---

## 📦 Tools dan Teknologi  
- **Python**  
- **Jupyter Notebook**  
- **Libraries**:  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`
 
## 🎯 Kesimpulan
1. Elbow Method mengidentifikasi bahwa jumlah cluster terbaik adalah 15.
2. K-Means Clustering berhasil mengelompokkan data acak dengan baik.
3. Evaluasi menggunakan Silhouette Score menunjukkan hasil yang memadai.

## 🛠 Pengembangan Selanjutnya
1. Menggunakan dataset lain untuk membandingkan hasil clustering.
2. Menerapkan metode clustering lain seperti DBSCAN atau Hierarchical Clustering.
3. Mengintegrasikan hasil ke dalam dashboard interaktif untuk visualisasi lebih dinamis.
