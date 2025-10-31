# 🎓 Final Project: Data Analysis & Hypothesis Testing

 **Iqbal Maulana Hakim** (NIM: A11.2023.15100).
## 📘 Deskripsi Proyek
Proyek ini merupakan bagian dari tugas akhir **Analisis Data**   
Tujuan proyek ini adalah untuk melakukan **analisis data eksploratif (EDA)** dan **uji hipotesis statistik** menggunakan dataset *Students Performance in Exams*.

---

## 🧾 Dataset
**Nama Dataset:** Students Performance in Exams  
**Sumber:** [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)  

Dataset berisi informasi performa 1000 siswa pada tiga mata pelajaran utama: **Matematika, Membaca, dan Menulis**, serta faktor-faktor seperti:
- Gender
- Ras/Etnis
- Tingkat pendidikan orang tua
- Jenis makan siang
- Kursus persiapan ujian

---

## 🧠 Tujuan Analisis
1. Mengetahui faktor-faktor yang memengaruhi performa siswa.  
2. Menganalisis perbedaan skor berdasarkan gender dan kursus persiapan.  
3. Melakukan uji hipotesis untuk menentukan signifikansi perbedaan tersebut.

---

## 📊 Struktur Proyek
final_project_data_analysis/
│
├── data/
│ └── StudentsPerformance.csv
│
├── notebook/
│ └── analysis.ipynb
│
├── report.md

---

## 🚀 Cara Menjalankan Proyek

### 1️⃣ Clone Repository
```bash
git clone https://github.com/<username>/final_project_data_analysis.git
cd final_project_data_analysis
2️⃣ Buat Virtual Environment (Opsional)
bash
python -m venv venv
venv\\Scripts\\activate  # di Windows
# atau
source venv/bin/activate  # di macOS/Linux

3️⃣ Install Dependencies
bash
pip install pandas matplotlib seaborn scipy jupyter
4️⃣ Jalankan Notebook
Buka file analysis.ipynb di VS Code atau Jupyter Notebook, lalu jalankan setiap cell dari atas ke bawah:

python
Shift + Enter
🧪 Hasil Utama
Terdapat perbedaan signifikan antara skor rata-rata laki-laki dan perempuan.

Kursus persiapan ujian memiliki pengaruh positif terhadap skor siswa.

Pendidikan orang tua menunjukkan hubungan moderate terhadap hasil belajar.

✍️ Penulis
Nama: Iqbal Maulana Hakim
NIM: A11.2023.15100
Jurusan: Teknik Informatika, Universitas Dian Nuswantoro (UDINUS)
📍 Lokasi: Semarang, Indonesia
