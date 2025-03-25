# CO2 Emission Prediction

## 📌 Overview

Proyek ini bertujuan untuk memprediksi emisi CO2 menggunakan model machine learning. Dataset yang digunakan berisi informasi terkait faktor-faktor yang memengaruhi emisi CO2, seperti jenis bahan bakar, konsumsi energi, dan karakteristik kendaraan.

## 📂 Repository Structure

- `notebooks/` : Berisi notebook Jupyter yang digunakan untuk eksplorasi data, pelatihan model, dan evaluasi.
- `data/` : Dataset yang digunakan dalam proyek ini.
- `models/` : Model yang telah dilatih dan disimpan.
- `requirements.txt` : Daftar dependensi yang dibutuhkan untuk menjalankan proyek.

## 🛠 Installation

1. Clone repository ini:
   ```bash
   git clone https://github.com/username/co2-emission-prediction.git
   cd co2-emission-prediction
   ```

2. Install dependensi:
   ```bash
   pip install -r requirements.txt
   ```

3. Jalankan Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 🔍 Data Preprocessing

- Menghapus nilai yang hilang (missing values)
- Normalisasi fitur untuk meningkatkan performa model
- Split data menjadi train dan test

## 🏗 Model Training

Model yang digunakan dalam prediksi emisi CO2 antara lain:
- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost**

Evaluasi model dilakukan menggunakan metrik **Mean Absolute Error (MAE)** dan **R-squared (R²)**.

## 📊 Results

- Model terbaik dalam eksperimen ini adalah **[nama model terbaik]** dengan MAE sebesar **[nilai MAE]** dan R² sebesar **[nilai R²]**.
- Visualisasi hasil prediksi dibandingkan dengan data aktual dapat ditemukan dalam notebook.

## 📌 Future Improvements

- Mencoba fitur engineering yang lebih kompleks
- Menggunakan lebih banyak data untuk meningkatkan akurasi
- Eksplorasi model deep learning untuk prediksi lebih akurat

## 📜 License

Proyek ini menggunakan lisensi [MIT License](LICENSE).

## 🤝 Contributing

Jika Anda ingin berkontribusi, silakan buat pull request atau buka issue untuk diskusi lebih lanjut!

---

✨ **Author:** [Arif Athaya Harahap]  
📧 **Contact:** [arifathayaharahap@gmail.com]

