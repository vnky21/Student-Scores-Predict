# Contoh Kasus: Membandingkan Model Regresi Linear dan Random Forest

Repository ini berisi contoh kasus sederhana tentang bagaimana membandingkan performa dua model berbeda, yaitu Regresi Linear dan Random Forest, dalam memprediksi nilai berdasarkan fitur yang diberikan.

### Deskripsi

Dalam contoh kasus ini, kami menggunakan dataset yang terdiri dari dua kolom: "Hours" (jumlah jam belajar) dan "Scores" (nilai). Tujuan kami adalah untuk memprediksi nilai berdasarkan jumlah jam belajar. Kami membagi dataset menjadi data latih dan data uji, dan kemudian melatih dua model: Regresi Linear dan Random Forest.

### Langkah-langkah

1. **Pra-pemrosesan Data**: Memastikan tidak ada nilai yang hilang (missing values) dan mengonversi tipe data yang diperlukan.
2. **Pemisahan Data**: Memisahkan data menjadi data latih dan data uji.
3. **Pemodelan**:
    - Melatih model Regresi Linear.
    - Melatih model Random Forest.
4. **Evaluasi Model**: Menghitung Mean Squared Error (MSE) dan R-Squared untuk kedua model.
5. **Visualisasi**: Membandingkan nilai aktual dengan nilai yang diprediksi pada kedua model.

### Hasil

Hasil dari percobaan ini adalah sebagai berikut:

- R-Squared untuk Regresi Linear: 0.9605
- R-Squared untuk Random Forest: 0.9361

Berdasarkan hasil ini, kami dapat menyimpulkan bahwa model Regresi Linear memiliki sedikit keunggulan dalam menjelaskan variabilitas dalam data dibandingkan dengan model Random Forest.

### File

- `data.csv`: File dataset yang digunakan dalam contoh kasus.
- `model_comparison.ipynb`: Notebook Jupyter yang berisi kode untuk pemrosesan data, pelatihan model, dan evaluasi model.
- `README.md`: File yang berisi deskripsi dan ringkasan dari contoh kasus ini.

### Requirement

- Library: scikit-learn, pandas, matplotlib

### Kontribusi

Kontribusi dalam bentuk masukan, perbaikan bug, atau peningkatan fungsionalitas sangat dipersilakan. Silakan buat _pull request_ untuk menyumbang.
