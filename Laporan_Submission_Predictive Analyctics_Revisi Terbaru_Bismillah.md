# Laporan Proyek Machine Learning - Reykhan Detak Chary Kartika

Link github : https://github.com/symphonicragnir/Submisi_Dicoding_ProjectAkhirr_MLterapan.git

## Domain Proyek

Proyek ini bertujuan untuk membangun model prediksi yang dapat memprediksi nilai matematika siswa berdasarkan berbagai fitur seperti jenis kelamin, etnisitas, tingkat pendidikan orang tua, jenis makan siang, dan apakah siswa mengikuti kursus persiapan ujian. Dataset yang digunakan dalam proyek ini berasal dari "Student Performance" yang dapat ditemukan di Kaggle. Dengan menganalisis data ini, proyek ini berfokus pada pembuatan model regresi yang dapat memprediksi skor matematika siswa berdasarkan faktor-faktor yang ada.

Dalam proyek ini, machine learning akan diterapkan untuk menganalisis hubungan antara fitur-fitur yang ada dan skor matematika siswa. Dengan menggunakan algoritma regresi seperti Linear Regression, model akan dilatih untuk memprediksi nilai siswa secara akurat. Tujuan utama dari proyek ini adalah untuk memberikan wawasan yang lebih baik tentang faktor-faktor yang mempengaruhi prestasi akademik siswa, sehingga dapat membantu lembaga pendidikan dalam merancang kebijakan yang lebih efektif dan memberikan dukungan yang lebih tepat sasaran.

## Project Overview

Pendidikan merupakan salah satu faktor penting dalam pembangunan sumber daya manusia. Nilai ujian, khususnya dalam mata pelajaran matematika, sering dijadikan indikator keberhasilan akademik siswa. Namun, prestasi siswa tidak hanya dipengaruhi oleh faktor internal seperti kemampuan intelektual, tetapi juga oleh faktor eksternal seperti latar belakang keluarga, jenis kelamin, status sosial ekonomi, dan ketersediaan program pendukung seperti kursus persiapan ujian.
Kemajuan teknologi dan ketersediaan data pendidikan memungkinkan penggunaan pendekatan machine learning dalam memprediksi hasil akademik siswa. Dengan membangun model prediktif berbasis data, institusi pendidikan dapat mengidentifikasi siswa yang berpotensi mengalami kesulitan akademik sejak dini dan memberikan intervensi yang sesuai.
Melalui penelitian ini, penulis akan menganalisis data performa ujian siswa dan membangun model prediktif yang dapat memperkirakan nilai matematika berdasarkan faktor-faktor non-akademik menggunakan algoritma pembelajaran mesin.
Predictive Analysis : Student Performance
Link dataset source (kaggle) : https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

**Rubrik/Kriteria Tambahan (Opsional)**:

- Jelaskan mengapa dan bagaimana masalah tersebut harus diselesaikan
- Menyertakan hasil riset terkait atau referensi. Referensi yang diberikan harus berasal dari sumber yang kredibel dan author yang jelas.

Mengapa Masalah Ini Harus Diselesaikan

1. Kesenjangan Pendidikan
   Siswa dari latar belakang ekonomi lemah atau dengan orang tua berpendidikan rendah sering kali menunjukkan performa yang lebih rendah. Hal ini menunjukkan adanya ketimpangan kesempatan belajar.
   📚 Reardon, S. F. (2011). The widening academic achievement gap between the rich and the poor: New evidence and possible explanations. Whither Opportunity? Rising Inequality, Schools, and Children's Life Chances. https://cepa.stanford.edu
2. Pengaruh Intervensi Pendidikan
   Kursus persiapan terbukti memiliki pengaruh positif terhadap skor ujian, yang menunjukkan bahwa intervensi tambahan seperti pembelajaran terstruktur dan dukungan belajar bisa meningkatkan performa siswa.
   📚 Fryer, R. G. (2014). Injecting charter school best practices into traditional public schools: Evidence from field experiments. Quarterly Journal of Economics, 129(3), 1355–1407.
3. Keadilan Gender dan Akses Pendidikan
   Penelitian menunjukkan bahwa terdapat perbedaan gender dalam performa matematika dan membaca, yang dapat mengarah pada stereotip atau perbedaan motivasi belajar.
   📚 Hyde, J. S., & Mertz, J. E. (2009). Gender, culture, and mathematics performance. Proceedings of the National Academy of Sciences, 106(22), 8801–8807. https://doi.org/10.1073/pnas.0901265106

Bagaimana Masalah Ini Harus Diselesaikan

1. Pengumpulan dan Analisis Data
   Gunakan data seperti dalam dataset Kaggle ini untuk menganalisis secara statistik faktor-faktor yang memengaruhi performa siswa.
2. Perancangan Intervensi Berbasis Data
   Program seperti kursus persiapan atau tutoring tambahan dapat ditargetkan kepada kelompok siswa yang rentan.
3. Pengembangan Kebijakan Inklusif
   Pemerintah dan lembaga pendidikan dapat menggunakan temuan ini untuk mengalokasikan sumber daya ke sekolah dengan tingkat performa rendah, atau yang melayani populasi berisiko.
4. Pelatihan Guru
   Guru dapat dilatih untuk mengenali faktor eksternal yang memengaruhi performa siswa dan memberikan dukungan personalisasi.
5. Pemberdayaan Orang Tua
   Meningkatkan keterlibatan orang tua, terutama yang memiliki tingkat pendidikan rendah, melalui pelatihan atau forum pendidikan.

## Business Understanding

Bagaimana kita dapat memprediksi nilai matematika siswa berdasarkan faktor-faktor demografis dan akademik seperti jenis kelamin, latar belakang etnis, tingkat pendidikan orang tua, jenis makan siang, dan partisipasi dalam kursus persiapan ujian?

### Problem Statements

1. Faktor apa saja dari data demografis dan akademik yang paling memengaruhi nilai matematika siswa?
2. Dapatkah model prediktif dibangun untuk memprediksi nilai matematika siswa secara akurat berdasarkan fitur demografis dan akademik mereka?
3. Bagaimana pengaruh program persiapan ujian terhadap nilai matematika siswa?
4. Apakah terdapat hubungan signifikan dalam nilai matematika berdasarkan jenis kelamin atau tingkat pendidikan orang tua?
5. Model prediksi mana yang memberikan kinerja terbaik dalam memprediksi nilai matematika siswa: regresi linier, pohon keputusan, atau random forest?

### Goals

1. Mengidentifikasi faktor-faktor demografis dan akademik yang berpengaruh terhadap nilai matematika siswa.
2. Membangun model prediksi untuk memperkirakan nilai matematika siswa berdasarkan data non-akademik seperti jenis kelamin, tingkat pendidikan orang tua, dan keikutsertaan dalam kursus persiapan ujian.
3. Mengevaluasi pengaruh program persiapan ujian terhadap prestasi matematika siswa.
4. Menilai efektivitas beberapa algoritma machine learning (seperti regresi linier, decision tree, dan random forest) dalam memprediksi nilai matematika.
5. Memberikan rekomendasi berdasarkan hasil analisis untuk mendukung kebijakan pendidikan yang lebih tepat sasaran.

### Manfaat Penelitian:

1. Bagi institusi pendidikan: Sebagai dasar untuk memahami faktor-faktor yang memengaruhi prestasi matematika siswa dan mengembangkan intervensi yang tepat.
2. Bagi guru dan orang tua: Memberikan wawasan mengenai pentingnya dukungan akademik dan persiapan ujian terhadap hasil belajar siswa.
3. Bagi peneliti dan praktisi data science: Menjadi studi kasus dalam penerapan machine learning untuk prediksi kuantitatif dalam bidang pendidikan.
4. Bagi pembuat kebijakan: Memberikan data dan analisis yang dapat dijadikan acuan dalam menyusun program pendidikan yang lebih efektif dan inklusif.

### Solution statements

- Model yang digunakan adalah Linear Regression, karena kita berfokus pada masalah regresi yang memprediksi skor berkelanjutan.
- Melakukan scaling fitur dan encoding fitur kategorikal untuk meningkatkan akurasi model.
- Memanfaatkan evaluasi metrik regresi seperti Mean Squared Error (MSE), Mean Absolute Error (MAE), dan R-squared (R²) untuk mengukur performa model.

## Data Understanding

Dataset ini berisi data tentang kinerja akademik siswa di berbagai mata pelajaran, dengan fokus utama pada matematika. Dataset terdiri dari 1000 baris dan 8 fitur, termasuk 3 fitur numerik (skor matematika, membaca, dan menulis) serta 5 fitur kategorikal yang menggambarkan informasi demografis dan akademik.

📄 Jumlah Data
Baris (Rows): 1000
Kolom (Columns): 8

🔗 Tautan Sumber Data
Dataset dapat diakses melalui tautan resmi Kaggle berikut:
👉 https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

![Data Understanding](https://github.com/user-attachments/assets/811a9973-d665-43dd-b420-6513693827af)

### Variabel-variabel pada study performance dataset adalah sebagai berikut:

- `math_score`: Skor matematika siswa (target variabel).
- `reading_score`: Skor membaca siswa.
- `writing_score`: Skor menulis siswa.
- `gender`: Jenis kelamin siswa (kategori: male, female).
- `race_ethnicity`: Ras atau etnis siswa.
- `parental_level_of_education`: Tingkat pendidikan orang tua siswa (kategori: high school, some college, bachelor’s degree, etc.).
- `lunch`: Jenis makan siang yang diterima siswa (kategori: standard, free/reduced).
- `test_preparation_course`: Status kursus persiapan ujian (kategori: none, completed).

### Exploratory Data Analysis (EDA)

- Cek missing values dengan `print(data.isnull().sum())` dan didapatkan hasil **tidak ada missing values**
- Cek duplikasi data dengan `data.duplicated().sum()` dan didapatkan hasil **tidak ada data yang duplikat**
- Visualisasi outlier dengan Boxplot
  ![Boxplot](https://github.com/user-attachments/assets/524f03ff-b96b-408c-a777-a81baf7551a4)

- Visualisasi Distribusi Skor Matematika
  ![Math Distribution](https://github.com/user-attachments/assets/25d3637e-80bb-460a-a336-35cc7f695d39)

- Visualisasi Distribusi Skor Membaca dan Menulis
  ![Reading Distribution](https://github.com/user-attachments/assets/dd8f8f13-20b6-41f9-a445-4d58a8a05227)
  ![Write Distribution](https://github.com/user-attachments/assets/7aaab005-fec8-4bd3-96b5-373e00316260)
  

**Rubrik/Kriteria Tambahan (Opsional)**:
Berdasarkan variabel yang ada, beberapa pendekatan analisis bisa dilakukan, antara lain:

- Analisis Perbandingan Berdasarkan Gender:
  Mengelompokkan data berdasarkan jenis kelamin dan menghitung rata-rata skor untuk masing-masing mata pelajaran. Apakah terdapat perbedaan signifikan antara siswa laki-laki dan perempuan? Studi literatur sering menyebutkan bahwa perbedaan dalam gaya belajar atau efek stereotip mungkin memengaruhi beberapa aspek, misalnya, perbedaan performa di reading dan writing.
- Pengaruh Test Preparation Course:
  Saring data berdasarkan status kursus persiapan ujian. Bandingkan rata-rata nilai antara siswa yang mengikuti kursus dengan yang tidak. Analisis ini dapat dilakukan dengan menggunakan uji hipotesis (misalnya, t-test) untuk melihat apakah perbedaan nilai signifikan secara statistik.
- Peran Tingkat Pendidikan Orang Tua:
  Variabel tingkat pendidikan orang tua sering diasumsikan berkorelasi positif dengan performa akademik anak. Analisis korelasi atau regresi dapat dilakukan untuk mengukur seberapa besar pengaruh variabel ini terhadap skor ujian.
- Analisis Demografis Lain (Race & Lunch):
  Pengelompokkan berdasarkan kelompok etnis dan tipe makan siang dapat mengungkap disparitas atau ketidaksetaraan yang mungkin terjadi. Misalnya, tipe makan siang (standar vs free/reduced) bisa menjadi proxy dari latar belakang

Berikut penjelasan hasil visualisasi distribusi skor:

1. Distribusi Math Score:
   Pada grafik ini, distribusi nilai matematika memiliki pola yang mendekati distribusi normal. Mayoritas nilai matematika berkisar antara 50 hingga 80, dengan puncak distribusi berada di sekitar nilai 60-70. Terdapat beberapa outlier di bagian kiri yang menunjukkan siswa dengan skor rendah (< 30), namun jumlahnya relatif sedikit.
2. Distribusi Reading Score:
   Distribusi nilai membaca juga menunjukkan pola mendekati normal, tetapi lebih condong ke kanan (skewed to the right). Puncak distribusi berada di sekitar nilai 70-80. Terdapat lebih banyak siswa yang mendapatkan skor tinggi (> 80) dibandingkan dengan siswa yang mendapatkan skor rendah (< 30).
3. Distribusi Writing Score:
   Distribusi skor menulis memiliki pola yang sangat mirip dengan skor membaca. Sebagian besar skor berkisar antara 60 hingga 80, dengan puncak distribusi di sekitar nilai 70-80. Grafik ini juga menunjukkan bahwa terdapat beberapa outlier di bagian bawah (skor rendah).

Secara keseluruhan, ketiga skor tersebut menunjukkan pola distribusi yang hampir simetris dan mendekati distribusi normal, meskipun terdapat sedikit skewness pada skor membaca dan menulis. Hal ini menunjukkan bahwa sebagian besar siswa mendapatkan skor yang cukup baik di ketiga kategori tersebut.

## Data Preparation

Pada tahap ini, dilakukan beberapa tahapan untuk mempersiapkan data:

1. Scaling Fitur Numerik: Fitur numerik `reading_score` dan `writing_score` di-scaling menggunakan `StandardScaler`. Sementara `math_score` di-scaling namun tidak digunakan sebagai fitur prediktor, melainkan sebagai target (y).
2. Encoding Fitur Kategorikal: Fitur seperti `gender`, `race_ethnicity`, `parental_level_of_education`, `lunch`, dan `test_preparation_course` diubah menjadi variabel numerik menggunakan One-Hot Encoding dengan penghapusan kategori pertama (`drop='first'`).
3. Data dibagi menjadi fitur (X) yang terdiri dari `reading_score`, `writing_score`, dan hasil encoding fitur kategorikal, serta target (y) yang berupa `math_score`. Pembagian dilakukan menggunakan `train_test_split` dengan rasio 80:20.

## Potensi Pengembangan Model Prediktif

Pada tahap ini, dilakukan beberapa proses untuk mempersiapkan data sebelum dilakukan pemodelan:

1. Identifikasi Fitur Numerik dan Kategori:
   - Fitur numerik (`numeric_features`): `reading_score` dan `writing_score`.
   - Fitur kategori (`categorical_features`): `gender`, `race_ethnicity`, `parental_level_of_education`, `lunch`, dan `test_preparation_course`.
2. OneHot Encoding:
   - Fitur kategori dikonversi menjadi bentuk numerik menggunakan `OneHotEncoder` dari sklearn.
   - Parameter `drop='first'` digunakan untuk menghindari dummy variable trap dengan menghapus kategori pertama.
   - Parameter `sparse_output=False` digunakan agar hasil encoding berupa DataFrame, bukan Sparse Matrix.
3. Menggabungkan Data Numerik dan Hasil Encoding:
   - Data numerik dan hasil encoding digabungkan menggunakan `pd.concat()`.
4. Pembagian Data: - Fitur (X): Gabungan data numerik (`reading_score`, `writing_score`) dan hasil OneHot Encoding. - Target (y): `math_score`, yaitu skor matematika siswa yang akan diprediksi. - Data dibagi menjadi data latih (`X_train`, `y_train`) dan data uji (`X_test`, `y_test`) dengan proporsi 80:20 menggunakan `train_test_split()`.
   Parameter `random_state=42` digunakan agar proses pembagian data tetap konsisten setiap kali kode dijalankan

## Modeling

Pada proyek ini, model yang digunakan adalah **Linear Regression**, yang merupakan algoritma regresi paling sederhana dan umum digunakan untuk memprediksi nilai kontinu. Linear Regression bertujuan untuk menemukan hubungan linear antara variabel dependen (skor matematika) dengan satu atau lebih variabel independen (fitur lainnya).
Langkah-langkah pemodelan:

1. Pelatihan Model: Model dilatih menggunakan data latih (`X_train` untuk fitur dan `y_train` untuk target) untuk mempelajari hubungan antara variabel independen dan dependen.
2. Pembangunan Model: Linear Regression digunakan untuk membangun model yang memprediksi skor matematika siswa berdasarkan fitur-fitur seperti jenis kelamin, etnisitas, tingkat pendidikan orang tua, dan faktor lainnya.

Parameter Model:
Model Linear Regression di sini menggunakan **parameter default**, yaitu:

- `fit_intercept`=True: Parameter ini mengatur apakah model akan menghitung intersep (konstanta). Dengan nilai default True, model akan menghitung intersep.
- `normalize=False`: Pada parameter ini, data tidak dinormalisasi secara otomatis sebelum pelatihan, yang merupakan default.
- `copy_X=True`: Data fitur akan disalin sebelum pelatihan, sesuai dengan parameter default.

Kelebihan Linear Regression:

- Sederhana dan mudah diinterpretasi.
- Cocok untuk prediksi nilai numerik yang berkelanjutan.

Kekurangan:

- Rentan terhadap overfitting jika tidak ditangani dengan baik, terutama dengan fitur yang sangat berhubungan satu sama lain.

Pada tahap ini, model Simple Linear Regression diterapkan sebagai baseline model untuk prediksi skor matematika (`math_score`).

- Library yang digunakan: `LinearRegression()` dari `sklearn.linear_model`.
- Proses fitting (`fit()`) dilakukan menggunakan data latih (`X_train`, `y_train`).
- Model akan belajar mencari hubungan linear antara fitur-fitur prediktor (`X_train`) dan target (`y_train`).

Model ini dipilih sebagai baseline karena kesederhanaannya dan untuk memberikan gambaran awal mengenai hubungan linear antara fitur prediktor dan skor matematika.

## Evaluation

Evaluasi dan Visualisasi
Pada tahap ini, dilakukan proses evaluasi model Simple Linear Regression menggunakan tiga metrik utama:

1. Mean Squared Error (MSE):

   - MSE mengukur rata-rata dari kuadrat perbedaan antara nilai aktual (`y_test`) dan nilai prediksi (`y_pred`).
   - Nilai MSE yang lebih rendah menunjukkan bahwa model mampu menghasilkan prediksi yang mendekati nilai aktual.
   - Pada model ini, MSE adalah 0.1266.

2. Mean Absolute Error (MAE):

   - MAE mengukur rata-rata dari nilai absolut perbedaan antara nilai aktual dan prediksi.
   - Semakin kecil nilai MAE, semakin baik performa model.
   - Pada model ini, MAE adalah 0.2781.

3. R-squared (R²):
   - R² mengukur seberapa baik model dapat menjelaskan variasi data target (`y_test`).
   - Nilainya berkisar antara 0 hingga 1, di mana nilai mendekati 1 menunjukkan bahwa model memiliki kemampuan prediktif yang baik.
   - Pada model ini, R² adalah 0.8804, yang berarti model dapat menjelaskan sekitar 88% variabilitas data skor matematika.

- Mean Squared Error (MSE): Mengukur rata-rata dari kuadrat perbedaan antara nilai prediksi dan nilai aktual.
- Mean Absolute Error (MAE): Mengukur rata-rata perbedaan absolut antara nilai prediksi dan nilai aktual.
- R-squared (R²): Menunjukkan seberapa baik model dapat menjelaskan variansi dalam data.

Hasil evaluasi:

- MSE: 0.1266719775854712
- MAE: 0.2781012880760494
- R²: 0.8804332983749563

## Visualisasi Hasil Prediksi vs Aktual

![Predictied Visual](https://github.com/user-attachments/assets/717b330a-18c0-4a41-b9b1-39b5222dfdb8)

Visualisasi ini menunjukkan hubungan antara nilai aktual (`y_test`) dan nilai prediksi (`y_pred`) untuk skor matematika (`math_score`).

- Sumbu X: Nilai aktual skor matematika.
- Sumbu Y: Nilai prediksi skor matematika.
- Scatter plot digunakan untuk melihat bagaimana model menangkap pola data. Jika titik-titik tersebut berada di sekitar garis diagonal (y = x), maka model berhasil melakukan prediksi yang akurat.
- Pada visualisasi ini, sebagian besar titik tersebar di sekitar garis diagonal, menunjukkan bahwa model dapat melakukan prediksi yang cukup baik meskipun terdapat beberapa outlier.

## Kesimpulan

![Conclusion](https://github.com/user-attachments/assets/acf82cc0-95d0-413c-a508-6644ba2c5590)

Hasil evaluasi menunjukkan bahwa model memiliki performa yang cukup baik dalam memprediksi skor matematika siswa. Dengan nilai R² sebesar 0.8804, model ini dapat menjelaskan sekitar 88% variansi dalam data, yang menunjukkan bahwa model mampu memprediksi skor matematika dengan akurasi tinggi. Nilai MSE dan MAE yang rendah menunjukkan bahwa perbedaan antara nilai prediksi dan nilai aktual relatif kecil, yang menandakan performa model yang baik.

Model ini telah berhasil menjawab Problem Statement pertama, yaitu memprediksi skor matematika siswa berdasarkan fitur demografis dan akademik mereka. Dengan hasil yang cukup memuaskan, model ini menunjukkan bahwa faktor-faktor seperti tingkat pendidikan orang tua, jenis kelamin, dan makan siang siswa memiliki pengaruh terhadap skor matematika mereka, meskipun tidak dijelaskan secara eksplisit dalam metrik.

Dalam hal Goal Statement, model ini telah memenuhi tujuan utama untuk membangun model yang akurat dan meneliti fitur-fitur yang lebih signifikan, seperti tingkat pendidikan orang tua yang mungkin berpengaruh terhadap prediksi skor matematika siswa. Metrik evaluasi juga menunjukkan bahwa model ini dapat digunakan untuk mengidentifikasi pola atau tren pada data yang dapat membantu dalam mengambil keputusan pendidikan yang lebih terarah.

Penerapan model Linear Regression untuk prediksi nilai matematika siswa dengan evaluasi menggunakan MSE, MAE, dan R² telah membuktikan dampaknya dalam meningkatkan pemahaman mengenai faktor-faktor yang mempengaruhi kinerja siswa. Solusi yang direncanakan, termasuk scaling fitur dan encoding fitur kategorikal, memberikan hasil yang signifikan, menjawab problem statement, dan memenuhi ekspektasi dalam mencapai tujuan proyek.
