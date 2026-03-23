# Proyek Pertama: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. Walaupun telah menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%. Untuk mencegah hal ini semakin parah, manajer departemen HR ingin meminta bantuan Anda mengidentifikasi berbagai faktor yang mempengaruhi tingginya attrition rate tersebut.

### Permasalahan Bisnis

* **Jumlahnya Karyawan yang Mengundurkan Diri (Attrition)**: Perushaan Jaya Jaya Maju memiliki banyak karyawan tetapi juga mengalami penurunan karyawan, sehingga mengganggu stabilitas perusahaan dan sumber daya manusia yang ada dalam perushaan
* **Faktor - Faktor yang menyebabkan karyawan Mangundurkan Diri (Analisis)**: Faktor yang mengakibatkan banyaknya karyawan perusahaan memutuskan mengundurkan diri.

### Cakupan Proyek

* Melakukan EDA (Exploratory Data Analysis) terhadap data untuk mengidentifikasi faktor - faktor yang memiliki korelasi **Attrition**
* Visualisasi dan pemodelan data untuk mengidentifikasi pola - pola data Attrition
* Pembuatan Dasboard dengan LookerStudio untuk visualisi data.

### Persiapan

Sumber data: [Jaya Jaya Maju](https://lookerstudio.google.com/reporting/0cfbe2da-1f8b-41cd-b79e-67ec3e9bbd85)

### Setup environment:

- install requirements:
```
pip install -r requirements.txt
```
Prediction Model dengan Google Colab:
  1. Buka ini [Google Colab](https://colab.research.google.com/drive/1fpRGoZwTSNRjOrAhBwoG8QN4g-_pP_e5?usp=sharing)
  2. Masukan model xgboost_model.pkl
  3. Jalankan file prediction.py
  4. Output akan Keluar

## Business Dashboard

Link: [LookerStudio](https://lookerstudio.google.com/reporting/0cfbe2da-1f8b-41cd-b79e-67ec3e9bbd85)

![Screenshot 2026-03-23 093759](https://github.com/user-attachments/assets/010b0873-7925-4cc0-b523-b35166bb5612)

Business Dashboard ini memberikan gambaran mengenai kondisi sumber daya manusia persuahaan Jaya Jaya Maju, yang saat ini memiliki total 1.470 karyawan dengan tingkat attrition 12,2%. Dapat dilihat bahwa rata - rata kepuasan kerja (job satisfaction) berada di angka 2.7 dari 4.0 sebuah skor menengah. sementara rata-rata upah per jam tercatat sebesar 88. Secara demografi, tenaga kerja didominasi oleh laki-laki sebesar 59,8% berbanding perempuan 40,2%, dengan mayoritas karyawan merupakan profesional muda yang berada di rentang usia 27 hingga 38 tahun. Tetapi ada 28% status karyawan yang "Tidak Diketahui" pada grafik attrition, yang menandakan sebagian data perlu diperbarui dan pembersihan agar lebih akurat.

Jika melihat pada distribusi peran pekerjaan, populasi terbesar terpusat pada posisi Sales Executive, Research Scientist, dan Laboratory Technician. Besarnya volume karyawan di ketiga posisi ini berarti perputaran atau turnover di sana akan sangat membebani biaya rekrutmen dan operasional perusahaan. Selain itu, pemetaan antara pendapatan bulanan dan kepuasan lingkungan kerja melalui grafik gelembung (scatter plot) dapat dimanfaatkan oleh manajemen untuk mengevaluasi apakah gaji yang diberikan sudah cukup selaras dengan kenyamanan yang dirasakan karyawan. Secara keseluruhan, informasi ini mengarahkan tim HR untuk berfokus pada investigasi akar masalah rendahnya kepuasan kerja di angka 2,7 tersebut, khususnya bagi karyawan usia 27-38 tahun di departemen padat karya, guna mencegah tingkat attrition semakin membengkak.

## Conclusion

Kesimpulan dari proyek ini ada faktor - faktor yang mempengaruhi terhadapat tingkat Attrition dalam perusahaan Jaya Jaya Maju, dapat di analisis pada data bahwa variabel seperti usia, kepuasan kerja, role pekerjaan, sampai tingkat pendidikan memiliki korelasi antara satu sama lain yang mempengaruhi tingkat Attrition. Dari sini perushaan Jaya Jaya Maju perlu memperhatikan variabel serta faktor - faktor yang mempengaruhi tingkat Attrition dan melakukan pencegahan agar Attrition tidak meningkat.

### Rekomendasi Action Items

Penyelesaian masalah dan Target yang harus dilakukan perusahaan:

- Meningkatkan Upah pekerja yang memiliki lebih bannyak pengalaman
- Pertinbangan untuk lowongan Internship dan program pengembangan Karir untuk pekerja entry level
- Memberikan waktu yang lebih fleksibel agar karyawan dapat menjalan hobi dan istirahat
