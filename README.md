# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding
Jaya Jaya Institut merupakan salah satu institusi pendidikan perguruan yang telah berdiri sejak tahun 2000. Hingga saat ini ia telah mencetak banyak lulusan dengan reputasi yang sangat baik. Akan tetapi, terdapat banyak juga siswa yang tidak menyelesaikan pendidikannya alias dropout. Oleh karena itu, perlu dianalisis faktor-faktor yang mempengaruhi tingginya dropout sehingga Jaya Jaya Institut dapat dengan cepat memberi bimbingan khusus ke mahasiswa tersebut.

### Permasalahan Bisnis
Jaya Jaya Institut menghadapi tantangan serius dengan tingginya tingkat dropout mahasiswa. Dropout yang tinggi tidak hanya merugikan institusi dari segi reputasi dan keuangan, tetapi juga berdampak negatif pada mahasiswa yang tidak menyelesaikan pendidikan mereka. Tingginya angka dropout dapat mengurangi kepercayaan calon mahasiswa dan orang tua terhadap kualitas pendidikan yang ditawarkan oleh Jaya Jaya Institut. Berikut adalah beberapa permasalahan bisnis utama yang dihadapi oleh institusi:

1. Reputasi Jaya Jaya Institut
    Tingginya tingkat dropout dapat merusak citra institusi sebagai penyedia pendidikan berkualitas untuk Jaya Jaya Institut
2. Kehilangan Pendapatan
    Setiap mahasiswa yang dropout berarti potensi pendapatan dari biaya kuliah dan lainnya yang hilang sehingga akan berakibat ke operasional Jaya Jaya Institut.
3. Pengaruh pada Akreditasi:
    Tingkat kelulusan yang rendah dapat mempengaruhi akreditasi Jaya Jaya Institut.
4. Ketidakpuasan Stakeholder
    Mahasiswa, orang tua, dan masyarakat dapat kehilangan kepercayaan terhadap kemampuan institusi dalam mendidik dan mendukung mahasiswa sampai lulus.

### Cakupan Proyek
1. Mengumpulkan dan memproses data mahasiswa.
2. Menganalisis data untuk menemukan pola dan faktor-faktor yang mempengaruhi dropoutnya mahasiswa.
3. Membangun model prediktif menggunakan algoritma Random Forest Classifier.
4. Membuat dashboard bisnis untuk memvisualisasikan temuan dan prediksi.
5. Memberikan rekomendasi tindakan berdasarkan hasil analisis.

### Persiapan
Berikut adalah tahapan untuk menyiapkannya:

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/students_performance/data.csv

Setup environment:
Apabila menginstal Python melalui Anaconda ataupun miniconda, Anda dapat menggunakan conda sebagai package manager dan environment management system. Berikut merupakan tahapan dalam membuat virtual environment menggunakan conda untuk melakukan prediksi.

1. Buka terminal atau PowerShell.
2. Jalankan perintah berikut.
    ```
     conda create --name prediksi_dropout python=3.9
    ```
3. Aktifkan virtual environment dengan menjalankan perintah berikut.
    ```
    conda activate prediksi_dropout
    ```
4. Instal semua library yang dibutuhkan menggunakan perintah berikut.
    ```
    pip install numpy pandas matplotlib seaborn scikit-learn streamlit scipy setuptools
    ```
5. Buka jupyter-notebook dengan menjalankan perintah berikut.
    ```
    jupyter-notebook
    ```
6. Buka file python prediction.py
7. Masukkan data yang ingin diprediksi pada variabel X_new
8. Tekan tombol run code
9. Hasil prediksi akan keluar
10. Bisa juga dengan mengakses link streamlit ini: https://belajar-penerapan-data-science-2-koekoo.streamlit.app

## Business Dashboard

Dashboard bisnis ini dikembangkan untuk membantu memprediksi kemungkinan seorang mahasiswa akan berhenti studi di Jaya Jaya Institut. Prediksi ini dihasilkan dari pemodelan machine learning yang telah melalui proses pelatihan menggunakan data historis mahasiswa.

Antarmuka dashboard menyajikan sejumlah input variabel yang menggambarkan aspek-aspek yang bisa memengaruhi keputusan dropout, seperti jalur masuk, mata kuliah yang diprogram, riwayat pendidikan sebelumnya, pekerjaan orang tua, serta indikator akademik lainnya. Berdasarkan data yang dimasukkan, sistem akan mengolah informasi tersebut menggunakan model prediktif yang telah disimpan, sehingga pengguna dapat memperoleh wawasan mengenai potensi risiko mahasiswa untuk tidak melanjutkan studi.

Dengan memanfaatkan dashboard ini, pihak Jaya Jaya Institut diharapkan dapat mengambil langkah-langkah strategis secara lebih dini dalam rangka menekan angka putus kuliah dan mendorong peningkatan prestasi serta keberlanjutan pendidikan mahasiswa.

## Conclusion

Tingkat dropout mahasiswa di Jaya Jaya Institut dipengaruhi oleh beragam aspek yang mencakup karakteristik demografis, latar belakang pendidikan sebelumnya, kondisi ekonomi, situasi keluarga dan sosial, serta performa akademik. Mahasiswa yang berusia lebih tua saat pertama kali mendaftar, terutama mereka yang berusia di atas 23 tahun atau masuk melalui jalur transfer, memiliki risiko lebih tinggi untuk tidak menyelesaikan studi. Risiko ini juga meningkat pada mahasiswa yang mengambil program studi manajemen malam hari atau teknik informatika, memiliki nilai masuk (admission grade) yang rendah, dan tidak menerima bantuan beasiswa.

Di samping itu, kondisi keluarga turut berperan, khususnya ketika orang tua mahasiswa, baik ibu maupun ayah—memiliki tingkat pendidikan yang tidak tercatat atau tidak diketahui, yang seringkali mencerminkan kurangnya dukungan akademik di lingkungan rumah. Mahasiswa yang mengalami dropout umumnya juga menunjukkan capaian akademik yang lebih rendah dibandingkan rekan-rekan mereka yang tetap melanjutkan pendidikan.

### Rekomendasi Action Items
Berikut adalah rekomendasi yang dapat dilakukan Jaya Jaya Institut untuk mengurangi tingkat dropout:

1. Kembangkan layanan konseling dan dukungan psikologis bagi mahasiswa yang berasal dari latar belakang keluarga dengan tingkat pendidikan orang tua yang tidak diketahui atau rendah, guna membantu mereka mengatasi tekanan emosional dan sosial yang mungkin memengaruhi keberlangsungan studi.

2. Tingkatkan akses terhadap program beasiswa bagi mahasiswa dengan risiko tinggi dropout, disertai penyuluhan yang jelas mengenai prosedur pengajuan dan jenis bantuan keuangan yang tersedia.

3. Bangun sistem pemantauan akademik yang berkelanjutan, agar institusi dapat mendeteksi secara dini mahasiswa dengan performa menurun dan memberikan intervensi tepat waktu untuk mencegah dropout.

4. Fasilitasi program remedial yang terstruktur untuk mahasiswa dengan nilai awal masuk yang rendah, guna mendukung mereka mengejar ketertinggalan akademik dan meningkatkan daya saing di lingkungan kampus.

5. Sediakan program dukungan khusus bagi mahasiswa yang berasal dari keluarga dengan kondisi ekonomi dan sosial yang kurang mendukung, seperti akses ke program pengembangan diri atau pelatihan soft skill.

6. Perbaiki sarana dan prasarana penunjang belajar, termasuk perpustakaan, ruang belajar, dan fasilitas layanan mahasiswa lainnya, agar tercipta suasana belajar yang lebih mendukung dan nyaman.

7. Dorong keterlibatan orang tua dalam pendidikan anak, melalui inisiatif komunikasi berkala dan program sosialisasi yang menumbuhkan kesadaran pentingnya dukungan keluarga terhadap keberhasilan studi mahasiswa.

8. Sediakan bimbingan akademik tambahan secara khusus untuk mahasiswa program manajemen malam hari dan teknik informatika, mengingat kelompok ini menunjukkan tingkat kerentanan dropout yang lebih tinggi.

9. Promosikan program keseimbangan hidup mahasiswa, seperti kegiatan ekstrakurikuler, komunitas positif, dan layanan kesehatan mental, agar mahasiswa dapat mengelola tekanan akademik dengan lebih baik.

## URL Dashborad
https://lookerstudio.google.com/reporting/1bc4346c-6452-4baf-8cbf-619575993b3e

## URL Streamlit
https://belajar-penerapan-data-science-2-koekoo.streamlit.app