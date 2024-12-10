# Analisis-Sentiment-Komentar-Film
Analisis Sentimen dan Analisis Film Berdasarkan Bahasa dengan Dataset IMDb

Pendahuluan
Penelitian ini bertujuan untuk memahami pola ulasan film berdasarkan sentimen dan menganalisis produksi film berdasarkan bahasa, genre, dan rating. Data yang digunakan adalah dataset IMDb, yang mencakup ulasan film dan informasi terkait produksi. Analisis ini memberikan wawasan tentang preferensi audiens, distribusi bahasa dalam film, dan faktor-faktor yang memengaruhi rating.

Dataset
Penelitian ini menggunakan dua dataset utama:

Dataset Sentimen IMDb:

50.000 ulasan film dalam bahasa Inggris.
Kolom utama:
review: teks ulasan.
sentiment: label sentimen ("positive" atau "negative").
Dataset Film IMDb:

1.000 entri tentang film.
Kolom utama:
Title, Director, Stars, IMDb-Rating, Category, Duration, Censor-board-rating, dan ReleaseYear.
Proses Analisis
1. Analisis Sentimen
Langkah-langkah:

Preprocessing Data:
Membersihkan teks ulasan dengan menghapus simbol, stopwords, dan melakukan tokenisasi.
Representasi teks menggunakan TF-IDF untuk mengekstraksi fitur numerik.
Model Training:
Menggunakan Logistic Regression untuk memprediksi sentimen.
Dataset dibagi menjadi 80% data latih dan 20% data uji.
Evaluasi Model:
Mengukur akurasi, precision, recall, dan F1-score.
Model menghasilkan akurasi sebesar 88.99%, menunjukkan kemampuan prediksi yang kuat untuk ulasan positif dan negatif.
Hasil Distribusi Sentimen:

Positive: 25.000 ulasan.
Negative: 25.000 ulasan.
2. Analisis Berdasarkan Bahasa
Langkah-langkah:

Eksplorasi Bahasa:
Bahasa diekstraksi dari kategori film.
Menghitung jumlah film untuk setiap bahasa.
Distribusi Film Berdasarkan Tahun:
Memvisualisasikan tren produksi film berdasarkan bahasa dan tahun rilis.
Rata-Rata Rating IMDb:
Mengelompokkan film berdasarkan bahasa untuk menghitung rata-rata rating IMDb.
Identifikasi Genre Populer:
Genre utama diidentifikasi untuk setiap bahasa berdasarkan jumlah film.
Hasil
1. Analisis Sentimen
Model Logistic Regression memiliki akurasi tinggi dengan distribusi yang seimbang antara sentimen positif dan negatif.
Sentimen Positif lebih dominan dalam ulasan.
2. Analisis Berdasarkan Bahasa
Top 3 Bahasa Produksi Film:
Bahasa Inggris.
Bahasa Spanyol.
Bahasa Hindi.
Rata-rata IMDb Rating Berdasarkan Bahasa:
Film berbahasa Inggris cenderung memiliki rating lebih tinggi dibandingkan bahasa lainnya.
Genre Populer Berdasarkan Bahasa:
Inggris: Action, Drama, dan Sci-Fi.
Spanyol: Drama, Romance, dan Thriller.
Hindi: Drama, Romance, dan Action.
3. Visualisasi
Visualisasi hasil dibuat menggunakan Tableau, meliputi:

Distribusi sentimen.
Grafik jumlah film berdasarkan bahasa dan tahun.
Rata-rata rating IMDb berdasarkan bahasa.
Genre populer untuk setiap bahasa.
Kesimpulan
Model analisis sentimen menunjukkan performa yang baik dalam memprediksi ulasan positif dan negatif.
Produksi film didominasi oleh bahasa Inggris, dengan genre Action dan Drama sebagai yang paling populer.
Bahasa memiliki pengaruh signifikan terhadap distribusi rating IMDb, dengan film berbahasa Inggris cenderung memiliki rating lebih tinggi.
Rekomendasi
Pengembangan Model: Menggunakan model deep learning untuk analisis sentimen untuk hasil yang lebih baik.
Ekspansi Dataset: Menganalisis ulasan dalam berbagai bahasa untuk memahami preferensi global.
Visualisasi Lebih Lanjut: Mengintegrasikan data ke dalam Tableau Public untuk distribusi interaktif.
