### Laporan Proyek Machine Learning = Farchan Suryadio Rizki
## Domain Proyek 
# ✨ Latar Belakang
Pendidikan merupakan salah satu faktor penting dalam pembangunan sumber daya manusia. Nilai ujian, khususnya dalam mata pelajaran matematika, sering dijadikan indikator keberhasilan akademik siswa. Namun, prestasi siswa tidak hanya dipengaruhi oleh faktor internal seperti kemampuan intelektual, tetapi juga oleh faktor eksternal seperti latar belakang keluarga, jenis kelamin, status sosial ekonomi, dan ketersediaan program pendukung seperti kursus persiapan ujian.
Kemajuan teknologi dan ketersediaan data pendidikan memungkinkan penggunaan pendekatan machine learning dalam memprediksi hasil akademik siswa. Dengan membangun model prediktif berbasis data, institusi pendidikan dapat mengidentifikasi siswa yang berpotensi mengalami kesulitan akademik sejak dini dan memberikan intervensi yang sesuai.
Melalui penelitian ini, penulis akan menganalisis data performa ujian siswa dan membangun model prediktif yang dapat memperkirakan nilai matematika berdasarkan faktor-faktor non-akademik menggunakan algoritma pembelajaran mesin.
Predictive Analysis : Student Performance
Link dataset source (kaggle) : https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

# ✅ Deskripsi Dataset:
Dataset ini memuat catatan nilai siswa pada tiga mata pelajaran utama, yaitu matematika, membaca, dan menulis. Di samping itu, tersedia pula beberapa variabel kategorikal yang dapat menjadi faktor penentu, seperti:
- Gender (Jenis Kelamin)
- Race/Ethnicity (Kelompok Etnis)
- Parental Level of Education (Tingkat Pendidikan Orang Tua)
- Lunch (Tipe Makan Siang: standar vs free/reduced)
- Test Preparation Course (Kursus Persiapan Ujian: completed atau none)

1. Target: nilai matematika (math score) – bisa diprediksi sebagai nilai numerik (regresi) atau dikelompokkan ke dalam kategori prestasi (klasifikasi).
2. Fitur:
- gender (male/female)
- race/ethnicity
- parental level of education
- lunch (standard/free)
- test preparation course (completed/none)
- reading score, writing score

# ✨  Proyek Prediksi:
🔸 1. Regresi
Tujuan: Memprediksi nilai matematika sebagai target numerik.
Model: Linear Regression, Random Forest Regressor, XGBoost Regressor, dll.
🔸 2. Klasifikasi
Tujuan: Mengelompokkan siswa ke dalam kategori prestasi, contoh:
low (0–60), medium (61–80), high (81–100)
Model: Logistic Regression, Decision Tree, Random Forest, SVM, dll.

# 📊 Visualisasi & Analisis yang Bisa Dibuat:
1. Korelasi antar nilai (math, reading, writing)
2. Boxplot nilai berdasarkan gender atau test preparation
3. Heatmap korelasi numerik
4. Analisis feature importance

# 🧩 Pernyataan Masalah:
Bagaimana kita dapat memprediksi nilai matematika siswa berdasarkan faktor-faktor demografis dan akademik seperti jenis kelamin, latar belakang etnis, tingkat pendidikan orang tua, jenis makan siang, dan partisipasi dalam kursus persiapan ujian?

# 🎯 Tujuan Proyek:
Tujuan dari proyek ini adalah untuk membangun model prediktif yang mampu:

(a) memprediksi nilai matematika siswa secara kuantitatif (regresi)
(b) mengelompokkan siswa ke dalam kategori prestasi (klasifikasi) berdasarkan karakteristik non-akademik mereka.

# ❓ Pertanyaan Masalah:

1. Faktor apa saja dari data demografis dan akademik yang paling memengaruhi nilai matematika siswa?
2. Dapatkah model prediktif dibangun untuk memprediksi nilai matematika siswa secara akurat berdasarkan faktor-faktor tersebut?
3. Bagaimana pengaruh program persiapan ujian terhadap nilai matematika siswa?
4. Apakah terdapat perbedaan signifikan dalam nilai matematika berdasarkan jenis kelamin atau tingkat pendidikan orang tua?

Model prediksi mana yang memberikan kinerja terbaik dalam memprediksi nilai matematika siswa: regresi linier, pohon keputusan, atau random forest? 

# 🎯 Tujuan Penelitian:
1. Mengidentifikasi faktor-faktor demografis dan akademik yang berpengaruh terhadap nilai matematika siswa.
2. Membangun model prediksi untuk memperkirakan nilai matematika siswa berdasarkan data non-akademik seperti jenis kelamin, tingkat pendidikan orang tua, dan keikutsertaan dalam kursus persiapan ujian.
3. Mengevaluasi pengaruh program persiapan ujian terhadap prestasi matematika siswa.
4. Menilai efektivitas beberapa algoritma machine learning (seperti regresi linier, decision tree, dan random forest) dalam memprediksi nilai matematika.
5. Memberikan rekomendasi berdasarkan hasil analisis untuk mendukung kebijakan pendidikan yang lebih tepat sasaran.

# 💡 Manfaat Penelitian:
1. Bagi institusi pendidikan: Sebagai dasar untuk memahami faktor-faktor yang memengaruhi prestasi matematika siswa dan mengembangkan intervensi yang tepat.
2. Bagi guru dan orang tua: Memberikan wawasan mengenai pentingnya dukungan akademik dan persiapan ujian terhadap hasil belajar siswa.
3. Bagi peneliti dan praktisi data science: Menjadi studi kasus dalam penerapan machine learning untuk prediksi kuantitatif dalam bidang pendidikan.
4. Bagi pembuat kebijakan: Memberikan data dan analisis yang dapat dijadikan acuan dalam menyusun program pendidikan yang lebih efektif dan inklusif.

# Variabel Dataset
Dataset Students Performance in Exams pada Kaggle memiliki total 8 variabel utama. Berikut adalah daftar variabel beserta penjelasan singkatnya:
- gender
Menunjukkan jenis kelamin siswa, dengan nilai seperti "male" atau "female".
- race/ethnicity
Mengidentifikasi kelompok etnis atau identitas kelompok siswa, biasanya dikategorikan sebagai group A, B, C, D, dan E.
- parental level of education
Menunjukkan tingkat pendidikan orang tua siswa, misalnya "high school", "some college", "bachelor's degree", atau "master's degree".
- lunch
Menyatakan tipe makan siang yang diterima siswa, yang dapat berupa "standard" atau "free/reduced". Variabel ini kadang digunakan sebagai indikator status ekonomi atau latar belakang sosial.
- test preparation course
Mengindikasikan apakah siswa telah mengikuti kursus persiapan ujian, dengan nilai "completed" apabila mengikuti, atau "none" jika tidak mengikuti.
- math score
Mewakili nilai ujian siswa pada mata pelajaran matematika.
- reading score
Mewakili nilai ujian siswa pada mata pelajaran membaca.
- writing score
Mewakili nilai ujian siswa pada mata pelajaran menulis.

![image](https://github.com/user-attachments/assets/99908c9b-f2fd-4e15-8566-cde7d51d06c8)


## Pendekatan Analisis
Berdasarkan variabel yang ada, beberapa pendekatan analisis bisa dilakukan, antara lain:
- Analisis Perbandingan Berdasarkan Gender:
Mengelompokkan data berdasarkan jenis kelamin dan menghitung rata-rata skor untuk masing-masing mata pelajaran. Apakah terdapat perbedaan signifikan antara siswa laki-laki dan perempuan? Studi literatur sering menyebutkan bahwa perbedaan dalam gaya belajar atau efek stereotip mungkin memengaruhi beberapa aspek, misalnya, perbedaan performa di reading dan writing.
- Pengaruh Test Preparation Course:
Saring data berdasarkan status kursus persiapan ujian. Bandingkan rata-rata nilai antara siswa yang mengikuti kursus dengan yang tidak. Analisis ini dapat dilakukan dengan menggunakan uji hipotesis (misalnya, t-test) untuk melihat apakah perbedaan nilai signifikan secara statistik.
- Peran Tingkat Pendidikan Orang Tua:
Variabel tingkat pendidikan orang tua sering diasumsikan berkorelasi positif dengan performa akademik anak. Analisis korelasi atau regresi dapat dilakukan untuk mengukur seberapa besar pengaruh variabel ini terhadap skor ujian.
- Analisis Demografis Lain (Race & Lunch):
Pengelompokkan berdasarkan kelompok etnis dan tipe makan siang dapat mengungkap disparitas atau ketidaksetaraan yang mungkin terjadi. Misalnya, tipe makan siang (standar vs free/reduced) bisa menjadi proxy dari latar belakang ekonomi yang berpengaruh terhadap ketersediaan dukungan belajar di rumah.

## Visualisasi Data
Untuk mendapatkan insight yang lebih mudah dipahami, beberapa teknik visualisasi yang dapat diterapkan antara lain:
- Boxplot:
![image](https://github.com/user-attachments/assets/4861d0ec-d564-430c-ab1e-e655fde8a9e5)
Menampilkan distribusi skor untuk setiap kategori (misalnya, gender atau test preparation status) guna mengidentifikasi median, kuartil, serta outlier.
- Bar Chart dan Violin Plot:
![image](https://github.com/user-attachments/assets/5948cf62-2cba-4ee4-992d-a26ae5a38125)
![image](https://github.com/user-attachments/assets/f18967a1-f05d-43a7-88ec-c3a10dcde127)
![image](https://github.com/user-attachments/assets/eb5a7183-523b-4e0a-b640-7533a5c9bd0c)
Untuk membandingkan rata-rata skor antar kelompok, chart jenis ini dapat membantu menyederhanakan perbandingan antar variabel kategorikal.
- Heatmap Korelasi:
Jika ingin mengeksplorasi hubungan antar tiga tipe skor (matematika, membaca, menulis), peta korelasi dapat mengidentifikasi apakah siswa yang memiliki nilai tinggi di satu mata pelajaran juga cenderung tinggi di mata pelajaran lainnya.
Visualisasi-visualisasi ini tidak hanya membuat hasil analisis lebih menarik secara visual, tetapi juga dapat membantu dalam penentuan fitur mana saja yang relevan untuk model prediktif.
1. Missing Values (Nilai Hilang):
    Dari hasil pengecekan menggunakan `data.isnull().sum()`, terlihat bahwa seluruh kolom memiliki nilai 0 untuk jumlah nilai hilang (missing values). Kesimpulannya, Dataset tidak memiliki missing values.
2. Duplikasi Data
    Dari hasil pengecekan menggunakan `data.duplicated().sum()`, terlihat bahwa tidak ada data yang duplikat.
3. Outlier Analysis:
    - Pada boxplot, terlihat beberapa titik yang berada di luar batas bawah (lower whisker) pada ketiga fitur numerik (`math_score`, `reading_score`, `writing_score`).
    - Titik-titik tersebut merupakan outlier karena berada di bawah batas Q1 - 1.5 * IQR.
    - Tidak ada outlier yang signifikan di bagian atas (upper whisker), hanya di bagian bawah.

berikut penjelasan hasil visualisasi distribusi skor:

1. Distribusi Math Score:
    Pada grafik ini, distribusi nilai matematika memiliki pola yang mendekati distribusi normal. Mayoritas nilai matematika berkisar antara 50 hingga 80, dengan puncak distribusi berada di sekitar nilai 60-70. Terdapat beberapa outlier di bagian kiri yang menunjukkan siswa dengan skor rendah (< 30), namun jumlahnya relatif sedikit.
2. Distribusi Reading Score:
    Distribusi nilai membaca juga menunjukkan pola mendekati normal, tetapi lebih condong ke kanan (skewed to the right). Puncak distribusi berada di sekitar nilai 70-80. Terdapat lebih banyak siswa yang mendapatkan skor tinggi (> 80) dibandingkan dengan siswa yang mendapatkan skor rendah (< 30).
3. Distribusi Writing Score:
    Distribusi skor menulis memiliki pola yang sangat mirip dengan skor membaca. Sebagian besar skor berkisar antara 60 hingga 80, dengan puncak distribusi di sekitar nilai 70-80. Grafik ini juga menunjukkan bahwa terdapat beberapa outlier di bagian bawah (skor rendah).

Secara keseluruhan, ketiga skor tersebut menunjukkan pola distribusi yang hampir simetris dan mendekati distribusi normal, meskipun terdapat sedikit skewness pada skor membaca dan menulis. Hal ini menunjukkan bahwa sebagian besar siswa mendapatkan skor yang cukup baik di ketiga kategori tersebut.

##  Potensi Pengembangan Model Prediktif
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

4. Pembagian Data:
    - Fitur (X): Gabungan data numerik (`reading_score`, `writing_score`) dan hasil OneHot Encoding.
    - Target (y): `math_score`, yaitu skor matematika siswa yang akan diprediksi.
    - Data dibagi menjadi data latih (`X_train`, `y_train`) dan data uji (`X_test`, `y_test`) dengan proporsi 80:20 menggunakan `train_test_split()`.

Parameter `random_state=42` digunakan agar proses pembagian data tetap konsisten setiap kali kode dijalankan
Dataset ini juga memberikan peluang untuk membangun model prediktif dalam ranah pendidikan, misalnya:
- Feature Engineering:
Lakukan encoding pada variabel kategorikal (seperti gender, parental level of education, lunch, dan test preparation) agar cocok untuk dimasukkan ke dalam model machine learning (misal, menggunakan One-Hot Encoding).
- Modeling:
Membangun model regresi (seperti Linear Regression atau Random Forest Regressor) untuk memprediksi salah satu skor ujian atau bahkan membangun model klasifikasi untuk mengelompokkan siswa berdasarkan kriteria performa.
- Evaluasi dan Interpretasi:
Menggunakan teknik seperti cross-validation untuk mengevaluasi performa model, serta feature importance untuk memahami variabel mana yang paling berpengaruh dalam menentukan nilai ujian.
Analisis seperti ini dapat membantu pihak sekolah atau pembuat kebijakan untuk mengidentifikasi bidang intervensi, misalnya peningkatan akses ke kursus persiapan ujian atau dukungan tambahan bagi siswa dari latar belakang dengan tingkat pendidikan orang tua yang rendah.

## Rekomendasi Implementasi Berdasarkan Analisis
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
    - 
Berdasarkan potensi insight yang didapat dari dataset ini, langkah-langkah berikut bisa dipertimbangkan:
- Intervensi Berdasarkan Kepolositas Gender dan Grup Etnis:
Jika analisis menunjukkan kesenjangan performa yang signifikan antara gender atau antar kelompok etnis, dapat dilakukan program pendukung khusus untuk mengatasi potensi bias ini.
- Peningkatan Kursus Persiapan Ujian:
Jika data menunjukkan bahwa siswa yang mengikuti kursus persiapan ujian memiliki skor lebih tinggi, meningkatkan akses dan kualitas program ini bisa menjadi strategi efektif untuk meningkatkan performa seluruh siswa.
- Program Dukungan untuk Orang Tua:
Melihat signifikansi tingkat pendidikan orang tua terhadap nilai, sekolah dapat mengadakan workshop atau program edukasi untuk orang tua sehingga mereka bisa mendukung proses belajar siswa di rumah.

## Visualisasi Evaluasi Hasil Prediksi
![image](https://github.com/user-attachments/assets/c724a839-e568-487e-b955-61fc4fddc0d2)
Visualisasi ini menunjukkan hubungan antara nilai aktual (`y_test`) dan nilai prediksi (`y_pred`) untuk skor matematika (`math_score`).
- Sumbu X: Nilai aktual skor matematika.
- Sumbu Y: Nilai prediksi skor matematika.
- Scatter plot digunakan untuk melihat bagaimana model menangkap pola data. Jika titik-titik tersebut berada di sekitar garis diagonal (y = x), maka model berhasil melakukan prediksi yang akurat.
- Pada visualisasi ini, sebagian besar titik tersebar di sekitar garis diagonal, menunjukkan bahwa model dapat melakukan prediksi yang cukup baik meskipun terdapat beberapa outlier.



## Kesimpulan
![image](https://github.com/user-attachments/assets/31542234-3f0a-4339-81e8-9dae06406453)

Dataset Students Performance in Exams menyediakan lahan analisis yang kaya untuk memahami faktor-faktor yang mempengaruhi kinerja akademik siswa. Dengan menggabungkan analisis statistik dan visualisasi, kita tidak hanya dapat mengenali pola-pola penting (seperti dampak jenis kelamin, kursus persiapan, pendidikan orang tua, hingga peran demografi lainnya), tetapi juga mengubah insight tersebut menjadi strategi intervensi yang konkrit untuk mendukung peningkatan mutu pendidikan.
Pendekatan ini menggabungkan eksplorasi data mendalam dan aplikasi model machine learning, memberikan dasar kuat bagi pengambil kebijakan untuk menciptakan solusi yang terukur dengan metrik evaluasi yang jelas.





