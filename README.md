# Analysis Pengaruh Histori Akademik, Background Keluarga, Sosial Experience, dan Aktivitas Penggunaan Elektronik terhadap Kemampuan Programming Skill Mahasiswa untuk Ruang Lingkup Student Computer Science

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis pengaruh beberapa faktor terhadap kemampuan programming skill mahasiswa, khususnya:
- Histori Akademik
- Background Keluarga
- Sosial Experience
- Aktivitas Penggunaan Elektronik

Hasil dari analisis ini digunakan untuk memprediksi programming skill mahasiswa berdasarkan nilai rata-rata dari mata kuliah yang relevan, menggunakan dua algoritma:
1. **Multiple Linear Regression (MLR)**
2. **Naive Bayes**

## Tujuan
- **Analisis Faktor:** Menentukan faktor-faktor yang paling berpengaruh terhadap programming skill.
- **Prediksi Skill:** Mengembangkan model prediktif berbasis Machine Learning.
- **Perbandingan Algoritma:** Membandingkan performa MLR dan Naive Bayes dengan berbagai metrik evaluasi.

## Dataset
Dataset meliputi data mahasiswa dengan variabel-variabel berikut:
- **Histori Akademik:** Nilai rata-rata dari mata kuliah terkait programming.
- **Background Keluarga:** Tingkat pendidikan dan pekerjaan orang tua.
- **Sosial Experience:** Partisipasi dalam kegiatan sosial.
- **Aktivitas Penggunaan Elektronik:** Lama waktu penggunaan perangkat elektronik untuk belajar dan hiburan.

## Tools yang Digunakan
- **Jupyter Notebook**
- **Visual Studio Code**

## Teknologi yang Digunakan
- **Python 3.8+** Bahasa pemrograman utama.
- **Library:** 
  - Pandas dan NumPy (manipulasi data)
  - Scikit-learn (machine learning)
  - Matplotlib dan Seaborn (visualisasi data)


## Struktur Proyek
    
    ├── data/
    │   ├── raw_data.csv         # Dataset mentah sebelum preprocessing
    │   ├── processed_data.csv   # Dataset setelah preprocessing
    ├── src/
    │   ├── preprocess.py        # Script untuk preprocessing data
    │   ├── train_mlr.py         # Script untuk melatih model Multiple Linear Regression
    │   ├── train_naive_bayes.py # Script untuk melatih model Naive Bayes
    │   ├── evaluate.py          # Script untuk evaluasi model
    ├── results/
    │   ├── model_performance.csv # Hasil evaluasi model
    │   ├── insights.pdf          # Laporan insight dari analisis
    ├── requirements.txt          # Daftar dependensi proyek
    └── README.md                 # Dokumentasi proyek

## Cara Menjalankan Proyek

1. **Clone repositori**  
   Salin repositori proyek ini ke komputer Anda menggunakan perintah berikut:
   ```bash
   git clone https://github.com/your-repo.git
2. **Masuk ke direktori proyek**
   ```bash
   cd your-repo
3. **Install dependensi**
   ```bash
   pip install -r requirements.txt
4. **Preprocessing data**
   ```bash
   python src/preprocess.py
5. **Melatih model**
   - Multiple Linear Regression (MLR)
       ```bash
       python src/train_mlr.py
    - Naive Bayes
       ```bash
       python src/train_naive_bayes.py
7. **Evaluasi model**
   ```bash
   python src/evaluate.py
8. **Hasil evaluasi** akan disimpan dalam direktori results/ dengan nama file model_performance.csv

## Kontributor
- Mutiara Enjelina (Ketua)
- Calvin Josep Silaen
- Emalia Putri Lestari Telaumbanua
- Indah Silitonga
- Samuel Saut Royzeki Aritonang
