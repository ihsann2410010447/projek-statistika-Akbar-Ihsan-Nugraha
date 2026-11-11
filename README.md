# Projek Statistika dan Probabilitas

**Milestone 1: EDA Dataset <StudentPerformance.csv>**

- **Nama:** Akbar Ihsan Nugraha
- **NIM:** 2410010447
- **Mata kuliah:** Statistika dan Probabilitas

## Deskripsi Dataset

- **Sumber:** Kaggle — [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Jumlah baris & kolom:** 1.000 baris, 8 kolom
- **Deskripsi singkat:** Dataset berisi nilai ujian siswa pada tiga mata pelajaran (matematika, membaca, menulis) beserta latar belakang siswa: gender, kelompok etnis, tingkat pendidikan orang tua, jenis makan siang, dan status kursus persiapan tes.

## Isi Repository

| File | Keterangan |
|------|------------|
| `Milestone1_EDA.ipynb` | Notebook analisis (EDA) |
| `<dataset>.csv` | Dataset yang digunakan |
| `screenshots/` | Screenshot hasil visualisasi / dashboard |
| `README.md` | Dokumentasi proyek |

## Ringkasan Analisis

1. **Data quality:** Dataset memiliki [N] baris dan [N] kolom. Terdapat [N] missing value
   (dari output Step 2) dan [N] data duplikat, sehingga [data tidak perlu dibersihkan /
   perlu penanganan berupa ...].
2. **Central tendency & dispersion:** Rata-rata nilai matematika [..], membaca [..], dan
   menulis [..]. Selisih mean dan median pada [kolom] sebesar [..], yang menunjukkan
   distribusi [simetris / miring ke kiri / miring ke kanan]. Nilai [kolom] paling bervariasi
   (std [..], CV [..]%), sedangkan [kolom] paling stabil (std [..], CV [..]%).
3. **Visualisasi univariate:** Histogram ketiga skor berbentuk [mendekati normal / miring ...].
   Boxplot menunjukkan outlier di sisi [bawah/atas] pada [kolom], umumnya pada nilai [..].
4. **Visualisasi bivariate:** Scatter plot [math score vs reading score] menunjukkan pola
   [linear positif / lemah / ...]. Heatmap menunjukkan korelasi tertinggi antara [kolom A]
   dan [kolom B] (r = [..]) dan terendah antara [kolom C] dan [kolom D] (r = [..]).

## Insight Utama

1. **[Judul insight 1, mis. hubungan antar skor]:** [kolom A] dan [kolom B] berkorelasi
   [kuat/sedang/lemah] (r = [..]), artinya siswa yang nilainya tinggi di satu mata pelajaran
   cenderung [tinggi/rendah] di mata pelajaran lainnya.
2. **[Judul insight 2, mis. dampak kursus persiapan]:** Siswa yang [menyelesaikan /
   tidak mengikuti] test preparation course memiliki rata-rata [kolom] sebesar [..] vs [..]
   (selisih [..] poin).
3. **[Judul insight 3, mis. outlier atau variasi]:** [kolom] memiliki outlier di sisi [..]
   dan variasi terbesar (CV [..]%), yang menunjukkan [...].

## Cara Menjalankan

1. Buka `Milestone1_EDA.ipynb` di Google Colab atau Jupyter Notebook.
2. Pastikan variabel `URL` mengarah ke file CSV raw di repo ini.
3. Jalankan semua cell dari atas ke bawah (*Restart & Run All*).
