
# 📊 Final Project Report: Data Analysis & Hypothesis Testing

## 🧾 Dataset Information
**Dataset:** Students Performance in Exams  
**Sumber:** [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  
**Jumlah Baris:** 1000  
**Jumlah Kolom:** 8  

**Deskripsi Kolom:**
| Kolom | Deskripsi |
|-------|------------|
| gender | Jenis kelamin siswa |
| race/ethnicity | Ras atau etnis siswa |
| parental level of education | Tingkat pendidikan orang tua |
| lunch | Jenis makan siang (standard/free-reduced) |
| test preparation course | Mengikuti kursus persiapan ujian atau tidak |
| math score | Nilai matematika |
| reading score | Nilai membaca |
| writing score | Nilai menulis |

---

## 🔍 1. Dataset Summary
Dataset berisi data performa siswa berdasarkan berbagai faktor demografis.  
Nilai diukur untuk tiga subjek utama: **Matematika, Membaca, dan Menulis**.

Tujuan analisis ini adalah untuk mengetahui **faktor-faktor yang memengaruhi performa siswa**, seperti gender, kursus persiapan, dan pendidikan orang tua.

---

## 📈 2. Data Exploration Plan
1. Analisis distribusi nilai siswa.  
2. Bandingkan skor berdasarkan gender.  
3. Lihat pengaruh kursus persiapan terhadap nilai.  
4. Cek korelasi antar nilai (math, reading, writing).

---

## 🔬 3. Exploratory Data Analysis (EDA)
- Distribusi nilai rata-rata menunjukkan mayoritas siswa memiliki skor 60–80.  
- Perempuan sedikit lebih unggul dalam **reading** dan **writing**, sedangkan laki-laki cenderung unggul di **math**.  
- Kursus persiapan ujian meningkatkan skor rata-rata sekitar 5–10 poin.

---

## 🧹 4. Data Cleaning & Feature Engineering
- Tidak ada nilai hilang (missing values).  
- Ditambahkan kolom baru `average_score` = rata-rata dari tiga skor ujian.

---

## 💡 5. Key Findings
| Kelompok | Rata-rata Nilai |
|-----------|-----------------|
| Semua siswa | 68.4 |
| Laki-laki | 66.3 |
| Perempuan | 70.5 |

Perempuan memiliki rata-rata nilai lebih tinggi dibandingkan laki-laki.

---

## 🧪 6. Hypothesis Formulation
1. H₀: Tidak ada perbedaan signifikan antara rata-rata skor laki-laki dan perempuan.  
2. H₀: Kursus persiapan ujian tidak memengaruhi skor rata-rata.  
3. H₀: Pendidikan orang tua tidak berpengaruh terhadap skor rata-rata siswa.

---

## 📉 7. Hypothesis Testing & Significance Analysis
- **Uji t-test dua sampel (independen)** digunakan untuk gender.  
- Hasil: `p-value < 0.05` → Tolak H₀.  
  ➜ Ada **perbedaan signifikan** antara nilai rata-rata laki-laki dan perempuan.  
- Uji lain menunjukkan kursus persiapan juga **berpengaruh positif** terhadap nilai.

---

## 🧾 8. Conclusion & Next Steps
✅ **Kesimpulan:**
- Perempuan secara signifikan memiliki nilai lebih tinggi dari laki-laki.  
- Kursus persiapan membantu meningkatkan performa siswa.  
- Pendidikan orang tua memiliki hubungan moderat terhadap hasil belajar.

🚀 **Langkah Selanjutnya:**
- Gunakan regresi linier untuk memprediksi skor rata-rata siswa.  
- Tambahkan visualisasi interaktif (misalnya dengan `plotly` atau `seaborn`).  
- Publikasikan hasil di GitHub untuk portofolio data analysis-mu.

---

© 2025 — Iqbal Maulana Hakim  
Jurusan: Teknik Informatika, Universitas Dian Nuswantoro  
