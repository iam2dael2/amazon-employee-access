# Amazon Employee Access
## Deskripsi Project
Proyek ini bertujuan untuk melakukan analisis data terkait akses karyawan terhadap sistem Amazon Employee Access. Dalam proyek ini, data yang relevan akan dikumpulkan dan dieksplorasi untuk memahami pola akses karyawan ke berbagai sumber daya dan layanan internal perusahaan.

## Deskripsi Dataset
Data berasal dari Amazon Inc. yang dikumpulkan dari tahun 2010-2011 (dipublikasikan di platform Kaggle). Set pelatihan terdiri dari 32769 sampel dan set pengujian terdiri dari 58922 sampel. Set pelatihan memiliki satu atribut label bernama "ACTION", yang nilainya "1" mengindikasikan bahwa aplikasi disetujui, sedangkan "0" mengindikasikan penolakan. Sebagai prediktor dari status ini, ada delapan fitur, yang menunjukkan karakteristik sumber daya yang dibutuhkan dan peran serta kelompok kerja karyawan di Amazon yang meminta akses.

**train.csv** - Set pelatihan. Setiap baris memiliki TINDAKAN (kebenaran dasar), SUMBER DAYA, dan informasi tentang peran karyawan pada saat persetujuan

**test.csv** - Set pengujian yang harus dilakukan prediksi. Setiap baris menanyakan apakah karyawan yang memiliki karakteristik yang terdaftar harus memiliki akses ke sumber daya yang terdaftar.

## Langkah Pengerjaan
**1. Pengumpulan Data**<br>
   Data terkait akses karyawan ke sistem Employee Access akan dikumpulkan dari berbagai sumber, seperti log akses, data keamanan, dan catatan kegiatan karyawan. Data ini akan mencakup informasi seperti waktu akses, jenis akses, level akses, dan identitas karyawan.<br>
<br>**2. Pembersihan dan Pengolahan Data**<br>
   Data yang dikumpulkan akan diperiksa, diperbaiki kesalahan atau ketidaksesuaian, dan dibersihkan agar siap untuk analisis lebih lanjut. Hal ini mungkin melibatkan penghapusan duplikasi, penanganan data yang hilang, dan standarisasi format data.<br>
<br>**3. Analisis Eksplorasi**<br>
Data yang telah diproses akan digunakan untuk melakukan analisis eksplorasi. Tujuan dari analisis ini adalah untuk mengidentifikasi pola akses karyawan, tren penggunaan sistem, dan poin-poin penting terkait akses karyawan terhadap berbagai sumber daya dan layanan internal.<br>
<br>**4. Visualisasi Data**<br>
Hasil analisis akan divisualisasikan dalam bentuk grafik, diagram, dan visualisasi data lainnya. Ini akan membantu dalam presentasi temuan yang relevan secara visual dan dapat dimengerti.<br>
<br>**5. Analisis Keamanan**<br>
Selama proyek ini, juga akan dilakukan analisis keamanan untuk memastikan akses karyawan terhadap sistem Employee Access sesuai dengan kebijakan keamanan perusahaan. Hal ini akan melibatkan identifikasi akses yang tidak sah, upaya keamanan yang mencurigakan, dan evaluasi kebijakan keamanan yang ada.<br>
<br>**6. Temuan dan Rekomendasi**<br>
Berdasarkan hasil analisis, temuan yang signifikan akan diidentifikasi dan direpresentasikan dalam bentuk laporan. Rekomendasi juga akan diajukan untuk meningkatkan kebijakan akses, keamanan, atau efisiensi sistem Employee Access.
