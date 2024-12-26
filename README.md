# Analysis Pengaruh Histori Akademik, Background Keluarga, Sosial Experience, dan Aktivitas Penggunaan Elektronik terhadap Kemampuan Programming Skill Mahasiswa untuk Ruang Lingkup Student Computer Science

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis pengaruh beberapa faktor terhadap kemampuan programming skill mahasiswa, khususnya:
- Histori Akademik
- Background Keluarga
- Sosial Experience
- Aktivitas Penggunaan Elektronik

Hasil dari analisis ini digunakan untuk memprediksi programming skill mahasiswa berdasarkan nilai rata-rata dari mata kuliah yang relevan, menggunakan dua algoritma:
1. **Random Forest**
2. **SVM**

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
  - Joblib (menyimpan dan memuat model yang telah dilatih)


## Struktur Proyek
    
    ├── data/
    │   ├── raw_data.csv         # Dataset mentah sebelum preprocessing
    │   ├── preprocessing1.csv   # Dataset setelah preprocessing
    ├── src/
    │   ├── Pre-Processing.ipynb        # Script untuk preprocessing data
    │   ├── Random Forest.ipynb         # Script untuk melatih model Random Forest
    │   ├── SVM.ipynb # Script untuk melatih model SVM
    ├── results/
    │   ├── df_scaled.pkl 
    │   ├── RandomForest.pkl      # Model Random Forest
    │   ├── scaler.pkl            # Model Scaler
    │   ├── SVM.pkl               # Model SVM
    ├── requirements.txt          # Daftar dependensi proyek
    └── README.md                 # Dokumentasi proyek

## Cara Menjalankan Proyek

1. **Clone repositori**  
   Salin repositori proyek ini ke komputer Anda menggunakan perintah berikut:
   ```bash
   git clone https://github.com/Calvin76en/Analisis-faktor-programming-skill.git
2. **Masuk ke direktori proyek**
   ```bash
   cd your-repo
3. **Install dependensi**
   ```bash
   pip install -r requirements.txt
4. **Preprocessing data**
   ```bash
   python src/Pre-Processing.ipynb
5. **Melatih model**
   - Random Forest
       ```bash
       python src/Random Forest.ipynb
    - Naive Bayes
       ```bash
       python src/SVM.ipynb

## Kontributor
- Mutiara Enjelina (Ketua)
- Calvin Josep Silaen
- Emalia Putri Lestari Telaumbanua
- Indah Silitonga
- Samuel Saut Royzeki Aritonang
