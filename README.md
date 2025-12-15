# 📘 Judul Proyek
*Analisis Tingkat Risiko Kesehatan Maternal Menggunakan Pendekatan Machine Learning dan Deep Learning*

## 👤 Informasi
- **Nama:** Arya Yudha Prasetya
- **Repo:** [https://github.com/AryaYudhaP/UAS_DataScience ]
- **Video:** [Link Video Kamu Disini]

---

# 1. 🎯 Ringkasan Proyek
- Menyelesaikan permasalahan deteksi dini risiko kehamilan.
- Melakukan data preparation (cleaning, scaling).
- Membangun 3 model: **Baseline** (Logistic Regression), **Advanced** (Random Forest), **Deep Learning** (MLP).
- Melakukan evaluasi dan menentukan model terbaik.

---

# 2. 📄 Problem & Goals
**Problem Statements:**
- Tingginya risiko komplikasi kehamilan yang terlambat terdeteksi.
- Kesulitan menganalisis pola non-linear pada tanda vital secara manual.

**Goals:**
- Membangun model klasifikasi risiko (Low, Mid, High) dengan akurasi tinggi.
- Mengidentifikasi fitur kesehatan dominan (Gula Darah & Tensi).

---
## 📁 Struktur Folder

# 3. 📊 Dataset
- **Sumber:** UCI Machine Learning Repository
- **Jumlah Data:** 1014 baris
- **Tipe:** Tabular (Klasifikasi Multi-kelas)

### Fitur Utama
| Fitur | Deskripsi |
|------|-----------|
| Age | Usia ibu hamil |
| SystolicBP | Tekanan darah atas |
| DiastolicBP | Tekanan darah bawah |
| BS | Kadar gula darah |
| BodyTemp | Suhu tubuh |
| HeartRate | Detak jantung |

---

# 4. 🔧 Data Preparation
- Cleaning (hapus duplikat).
- Transformasi (StandardScaler).
- Splitting (80% Train, 20% Test).

---

# 5. 🤖 Modeling
- **Model 1 – Baseline:** Logistic Regression.
- **Model 2 – Advanced ML:** Random Forest.
- **Model 3 – Deep Learning:** Multilayer Perceptron (MLP) - *Best Model*.

---

# 6. 🧪 Evaluation
**Metrik:** Accuracy & Weighted F1-Score

### Hasil Singkat
| Model | Score (Acc) | Catatan |
|-------|--------|---------|
| Baseline | 0.60 | Underfitting |
| Advanced | 0.65 | Good feature importance |
| Deep Learning | 0.69 | Akurasi tertinggi |

---

# 7. 🏁 Kesimpulan
- **Model terbaik:** Deep Learning (MLP).
- **Alasan:** Mampu menangkap pola data yang kompleks dan non-linear.
- **Insight penting:** Risiko "Mid Risk" sulit dideteksi karena datanya sangat beririsan dengan risiko lain.

---

# 8. 🔮 Future Work
- [x] Tambah data (Khususnya Mid Risk)
- [x] Tuning model
- [ ] Coba arsitektur DL lain
- [x] Deployment

---

# 9. 🔁 Reproducibility
Gunakan environment:
```bash
pip install -r requirements.txt
