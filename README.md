# Deteksi Ujaran Kebencian dan Emosi pada Komentar TikTok

## 🎯 Tujuan
Proyek ini bertujuan untuk mengklasifikasikan emosi sekaligus mendeteksi ujaran kebencian pada komentar TikTok, khususnya pada kasus viral perceraian Arhan dan Zize. Hasilnya digunakan untuk memahami pola emosi dan persepsi masyarakat terhadap isu viral di media sosial.

---

## 📄 Deskripsi Singkat
Dataset dikumpulkan melalui proses crawling pada komentar TikTok. Komentar kemudian diberi label emosi: **marah, senang, sedih, kecewa, dan benci**. Dataset ini digunakan untuk melatih model machine learning sehingga sistem dapat memberikan prediksi otomatis berdasarkan teks komentar.

---

## 📂 Struktur Dataset
Dataset berisi **1001 entri** dengan kolom:

| Kolom            | Keterangan |
| `komentar`       | Teks komentar asli |
| `cleaned_text`   | Teks yang sudah dibersihkan |
| `label`          | Label emosi (teks) |


---
## 🤖 Model Machine Learning yang Digunakan
Proyek ini menggunakan tiga model utama:

1. **Support Vector Machine (SVM)**  
   Model klasifikasi yang mencari hyperplane terbaik untuk memisahkan kelas emosi.

2. **Multinomial Naive Bayes**  
   Model probabilistik yang bekerja baik pada data teks seperti BoW atau TF-IDF.

3. **Random Forest Classifier**  
   Model ensemble yang menggunakan banyak decision tree untuk meningkatkan akurasi.

---

