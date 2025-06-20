# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Institut, sebuah institusi pendidikan yang mapan, menghadapi tantangan serius berupa tingginya tingkat mahasiswa yang tidak menyelesaikan studinya (dropout), meskipun memiliki reputasi baik. Fenomena ini menjadi masalah besar karena berdampak pada kredibilitas institusi dan efisiensi sumber daya. Oleh karena itu, tujuan utama Jaya Jaya Institut adalah mendeteksi mahasiswa berisiko dropout sedini mungkin agar dapat diberikan bimbingan khusus, dengan harapan dapat menurunkan angka putus kuliah secara signifikan.

Untuk mengatasi permasalahan ini, proyek ini akan menganalisis data performa mahasiswa yang disediakan guna mengidentifikasi faktor-faktor pemicu dropout. Kontribusi utama seorang data scientist adalah membangun model prediktif untuk deteksi dini dan mengembangkan dashboard visualisasi interaktif. Solusi ini diharapkan dapat meningkatkan retensi mahasiswa, memungkinkan pengambilan keputusan berbasis data yang lebih proaktif, dan pada akhirnya memperkuat reputasi Jaya Jaya Institut.

### Permasalahan Bisnis

Permasalahan bisnis utama yang akan diselesaikan adalah:
- Perlunya Penurunan Tingkat Dropout Mahasiswa: Angka putus kuliah sebesar 32,1% saat ini membutuhkan upaya strategis untuk dikurangi demi keberlanjutan akademik.
- Mendesaknya Analisis Faktor Pemicu Dropout: Diperlukan investigasi mendalam untuk mengidentifikasi variabel-variabel kunci yang mendorong tingginya tingkat putus kuliah.
- Pentingnya Pengembangan Sistem Monitoring Komprehensif: Untuk mendukung keputusan strategis yang lebih baik, institusi membutuhkan implementasi sistem monitoring yang mampu melacak tren dan faktor-faktor terkait dropout secara real-time.
  
### Cakupan Proyek

Cakupan proyek ini meliputi:
- Eksplorasi Data Mahasiswa: Melakukan analisis mendalam terhadap dataset Jaya Jaya Institut guna mengidentifikasi pola, korelasi, dan faktor-faktor signifikan yang berkorelasi dengan status putus kuliah mahasiswa.
- Pengembangan Model Prediktif: Membangun model machine learning yang mampu memprediksi probabilitas putus kuliah mahasiswa berdasarkan data yang tersedia, dengan fokus pada akurasi identifikasi faktor pemicu.
- Desain Dashboard yang Informatif: Merancang dan mengimplementasikan dasbor visual informatif yang berfungsi sebagai alat monitoring berkelanjutan untuk tingkat putus kuliah, identifikasi faktor kunci, dan pelacakan tren historis nantinya.

### Persiapan

Sumber data: [Dataset Dicoding](https://github.com/dicodingacademy/dicoding_dataset/tree/main/students_performance)

#### **Setup Environment**

#### Menyiapkan Lingkungan untuk Menjalankan Jupyter Notebook (.ipynb) di Google Colab dan VS Code

#### 1. Menjalankan Jupyter Notebook di Google Colab

Google Colab adalah platform online yang memungkinkan Anda menjalankan Jupyter Notebooks di cloud tanpa perlu pengaturan pada mesin lokal.

##### Panduan Langkah demi Langkah:
1. **Buka Google Colab**:
   - Kunjungi [Google Colab](https://colab.research.google.com/).

2. **Unggah Notebook Anda**:
   - Klik **File** di menu kiri atas.
   - Pilih **Upload notebook**.
   - Pilih file `.ipynb` dari mesin lokal Anda dan klik **Open**.

3. **Jalankan Notebook Anda**:
   - Setelah diunggah, notebook Anda akan terbuka di antarmuka Colab.
   - Anda dapat menjalankan sel notebook dengan memilih kode di dalamnya dan menekan **Shift + Enter** atau mengklik tombol play di samping sel tersebut.

4. **Menggunakan Google Drive (Opsional)**:
   - Jika file notebook Anda disimpan di Google Drive, Anda juga bisa membuka notebook langsung dari Google Drive.
   - Klik **File > Open notebook**, kemudian pilih tab **Google Drive** untuk memilih notebook dari drive Anda.

---

#### 2. Menjalankan Jupyter Notebook di VS Code

Untuk menjalankan Jupyter Notebook di **mesin lokal** menggunakan **VS Code**, Anda perlu menginstal beberapa alat, seperti **Python**, **Jupyter**, dan **VS Code Jupyter extension**.

##### Panduan Langkah demi Langkah:
1. **Instal VS Code**:
   - Jika Anda belum menginstal **VS Code**, unduh dan pasang dari [sini](https://code.visualstudio.com/Download).

2. **Instal Python**:
   - Pastikan Anda sudah menginstal **Python** di sistem Anda. Anda bisa mengunduhnya dari [sini](https://www.python.org/downloads/).
   - Setelah instalasi, periksa apakah Python terinstal dengan benar dengan menjalankan `python --version` di terminal atau command prompt.

3. **Instal Jupyter**:
   - Buka terminal atau command prompt dan instal Jupyter Notebook dengan menjalankan:
     ```bash
     pip install notebook
     ```
   - Ini akan menginstal Jupyter dan membuatnya tersedia untuk digunakan.

4. **Instal Jupyter Extension di VS Code**:
   - Buka **VS Code**.
   - Pergi ke **Extensions** dengan mengklik ikon Extensions di sidebar (atau tekan `Ctrl + Shift + X`).
   - Cari **"Jupyter"** dan instal **Jupyter extension** dari Microsoft.

5. **Instal Python Extension di VS Code**:
   - Cari **Python** extension di Extensions view.
   - Instal **Python extension** dari Microsoft untuk mendukung Python di VS Code.

6. **Buka Jupyter Notebook**:
   - Buka file `.ipynb` langsung di VS Code dengan memilih **File > Open File** atau drag dan drop notebook ke VS Code.
   - VS Code akan secara otomatis mendeteksi format notebook dan menampilkannya dalam editor yang mendukung Jupyter.

7. **Pilih Python Interpreter**:
   - Jika diminta, pilih interpreter Python yang ingin Anda gunakan dengan mengklik nama kernel di pojok kanan atas dan memilih interpreter yang sesuai. Pastikan Anda telah menginstal **Jupyter** di lingkungan yang dipilih.

8. **Jalankan Notebook**:
   - Setelah lingkungan diatur, Anda dapat menjalankan sel-sel dengan memilih kode dan menekan **Shift + Enter**, atau menggunakan tombol play.

---

## Business Dashboard

Dashboard ini dirancang untuk menyajikan wawasan mendalam mengenai status dropout mahasiswa. Dengan menampilkan metrik utama, tren, dan perbandingan berdasarkan beragam faktor pemicu yang teridentifikasi dari analisis, dashboard ini bertujuan membantu pihak institut dalam mengidentifikasi area fokus strategis untuk meningkatkan motivasi dan keberhasilan studi mahasiswa.

🔗 URL Lookerstudio: [Jaya Jaya institue Student Performance dashboard](https://lookerstudio.google.com/reporting/0113074f-0ad4-4a57-900b-810672fbcd43)
![Jaya Jaya institue Student Performance dashboard](src/Dashboard.png)


## Menjalankan Prototype Sistem Machine Learning

![image](/src/SS_DS2_streamlit(2).png)
![image](/src/SS_DS2_streamlit(3).png)
![image](/src/SS_DS2_streamlit(4).png)
![image](/src/SS_DS2_streamlit(1).png)


Prototype ini digunakan dengan cara meninput manual. Adapun cara menjalankannya terbagi menjadi dua yaitu secara lokal dan online.

Cara secara lokal:
Berikut adalah langkah-langkah untuk menyiapkan lingkungan pengembangan (environment) dan menjalankan aplikasi **Streamlit** (`app.py`) yang diambil dari repository GitHub berikut:  
[https://github.com/ThirafiQaedi/dicoding_penerapan_datascience2](https://github.com/ThirafiQaedi/dicoding_penerapan_datascience2)

## 1. Persiapkan Lingkungan Virtual
Buat lingkungan virtual untuk mengisolasi dependensi aplikasi agar tidak bentrok dengan proyek lain.

```bash
# Membuat environment virtual
python -m venv myenv

# Mengaktifkan environment
# Untuk Windows
myenv\Scripts\activate

# Untuk macOS/Linux
source myenv/bin/activate
```
## 2. Instalasi Dependensi
Clone repository dan install semua dependensi yang diperlukan oleh aplikasi.

### Langkah-langkah:
1. **Clone repository**:
   Clone repository GitHub yang berisi aplikasi dengan menjalankan perintah berikut di terminal:
   ```bash
   git clone https://github.com/ThirafiQaedi/dicoding_penerapan_datascience2.git
   ```

2. **Masuk ke folder proyek**:
   Setelah repository berhasil di-clone, pindah ke direktori proyek dengan perintah berikut:
   ```bash
   cd dicoding_penerapan_datascience2
   ```

3. **Install dependensi**:
   Jika proyek menyediakan file `requirements.txt`, Anda bisa menginstal semua dependensi yang diperlukan dengan perintah:
   ```bash
   pip install -r requirements.txt
   ```
   Ini akan menginstal semua paket Python yang dibutuhkan untuk menjalankan aplikasi.

4. **Jika tidak ada `requirements.txt`**:
   Jika proyek tidak menyertakan `requirements.txt`, Anda bisa menginstal dependensi secara manual. Misalnya, untuk aplikasi Streamlit, Anda harus menginstal Streamlit, Pandas, dan dependensi lainnya:
   ```bash
   pip install streamlit pandas numpy matplotlib seaborn scikit-learn
   ```

---

## 3. Jalankan Aplikasi Streamlit
Setelah semua dependensi diinstal, Anda dapat menjalankan aplikasi **Streamlit** dengan perintah berikut.

### Langkah-langkah:
1. **Jalankan aplikasi**:
   Untuk memulai aplikasi Streamlit, gunakan perintah:
   ```bash
   streamlit run app.py
   ```
   
   Perintah ini akan memulai aplikasi Streamlit pada `localhost`, dan Anda bisa mengaksesnya melalui browser dengan URL seperti:
   ```
   http://localhost:8501
   ```

2. **Buka aplikasi di browser**:
   Setelah menjalankan perintah di atas, aplikasi akan otomatis terbuka di browser. Jika tidak terbuka secara otomatis, Anda bisa membuka browser dan mengetikkan `http://localhost:8501`.

---

## 4. Periksa Kode dalam `app.py`
Pastikan kode dalam file `app.py` tidak mengandung kesalahan dan sesuai dengan struktur yang diharapkan. Berikut langkah-langkah yang perlu diperhatikan:

### Langkah-langkah:
1. **Periksa file `app.py`**:
   Pastikan bahwa file `app.py` tidak mengandung kesalahan atau missing dependencies. Jika ada error yang muncul setelah menjalankan aplikasi, periksa apakah semua pustaka yang dibutuhkan sudah diimpor dengan benar.

2. **Cek dependensi**:
   Jika aplikasi menggunakan data atau file eksternal (seperti CSV, Excel, atau model terlatih), pastikan bahwa file tersebut ada di folder yang sesuai dengan kode.

3. **Menangani kesalahan**:
   Jika ada kesalahan dalam aplikasi, Anda bisa memeriksa pesan error yang muncul di terminal dan menyesuaikan kode di `app.py` untuk memperbaiki masalah tersebut.

---

Untuk versi onlinenya dapat di lihat dilink streamlit cloud berikut : 

https://dicodingpenerapandatascience2-3k2f3kc83pmllwjndgwtgg.streamlit.app/

## Conclusion

Proyek ini berhasil melakukan analisis komprehensif terhadap data performa mahasiswa Jaya Jaya Institut. Melalui eksplorasi data dan penerapan uji statistik (seperti Chi-square dan t-test), proyek berhasil mengidentifikasi dan mengungkap korelasi serta perbedaan signifikan antara berbagai karakteristik mahasiswa dengan status putus kuliah.

Adapun karakteristik umum mahasiswa yang berstatus dropout:
A. Profil Demografi & Latar Belakang:
- Usia & Nilai Awal: Mahasiswa yang dropout memiliki rata-rata usia saat pendaftaran 26.07 tahun. Nilai kualifikasi sebelumnya rata-rata 131.09, dan nilai masuk rata-rata 124.67. Ini menunjukkan dropout tidak hanya terjadi pada mahasiswa sangat muda atau dengan nilai akademik rendah di awal.
- Jenis Kelamin: Proporsi dropout antara perempuan (50.8%) dan laki-laki (49.2%) hampir seimbang, menunjukkan tidak ada bias gender yang signifikan dalam fenomena dropout.
- Status Perkawinan: Mayoritas besar mahasiswa yang dropout berstatus Lajang (1.184 siswa), jauh melebihi kategori lain. Hal ini bisa mengindikasikan fleksibilitas hidup atau prioritas yang berbeda dibandingkan mereka yang sudah berkeluarga.
- Kualifikasi Pendidikan & Pekerjaan Orang Tua:
    - Mayoritas mahasiswa dropout berasal dari latar belakang di mana orang tua (baik ayah maupun ibu) memiliki kualifikasi pendidikan Menengah (Secondary Education) atau Pendidikan Dasar (Basic Education 3rd Cycle ke bawah).
    - Mengenai pekerjaan, banyak mahasiswa dropout memiliki orang tua (ayah dan ibu) yang berprofesi sebagai Pekerja Tidak Terampil (Unskilled Workers) atau Pekerja Terampil di Industri/Konstruksi. Ini mungkin mengindikasikan adanya tekanan ekonomi atau latar belakang sosial-ekonomi tertentu.
- Kualifikasi Sebelumnya Mahasiswa: Sebagian besar mahasiswa yang dropout masuk dengan kualifikasi Pendidikan Menengah (Secondary Education), menunjukkan bahwa ini adalah jalur masuk paling umum bagi mereka yang kemudian dropout.
  
B. Faktor Keuangan & Dukungan Institusional:
- Biaya Kuliah (Tuition Fees): Jumlah mahasiswa dropout yang biaya kuliahnya belum lunas/tepat waktu jauh lebih tinggi (~1.000 siswa) dibandingkan yang sudah lunas (~500 siswa). Ini adalah indikator kuat masalah keuangan yang berkontribusi pada dropout.
- Beasiswa: Mayoritas besar mahasiswa yang dropout bukanlah penerima beasiswa (~1.250 siswa). Ini mendukung hipotesis bahwa dukungan finansial (beasiswa) berperan penting dalam retensi mahasiswa.
- Status Debitur: Meskipun mayoritas mahasiswa dropout tidak berstatus debitur, ada kelompok signifikan (~250 siswa) yang berstatus debitur saat dropout. Ini menunjukkan bahwa masalah utang juga menjadi faktor bagi sebagian kelompok.
- Displaced: Jumlah mahasiswa dropout yang "Displaced" (tidak tinggal di tempat asal/terpisah dari keluarga) lebih tinggi (~750 siswa) dibandingkan yang tidak (~400 siswa). Ini bisa mengindikasikan kesulitan adaptasi atau kurangnya dukungan sosial/keluarga.

C. Jalur Pendaftaran & Program Studi:
- Mode Aplikasi: Mahasiswa yang mendaftar melalui mode "Over 23 years old" (435 siswa) dan "1st phase - general contingent" (345 siswa) merupakan kelompok terbesar di antara para dropout. Ini perlu diinvestigasi lebih lanjut mengapa mode aplikasi ini berkorelasi dengan dropout.
- Program Studi: Kursus "Management (evening attendance)" dan "Management" menunjukkan jumlah dropout tertinggi. Ini mungkin menunjukkan tantangan spesifik dalam kurikulum, beban kerja, atau harapan karier di program studi tersebut.
- Waktu Perkuliahan: Mayoritas besar mahasiswa yang dropout berasal dari program perkuliahan siang hari (Daytime, 83.2%). Ini menunjukkan bahwa program siang hari mungkin memiliki tantangan retensi yang berbeda dibandingkan program malam hari (yang mungkin lebih banyak diisi oleh pekerja).
  
D. Keterlibatan Akademik & Kurikulum (Sebelum Dropout):
- Rata-rata Unit Kurikulum: Mahasiswa yang dropout umumnya memiliki rata-rata unit yang terdaftar (enrolled) sekitar 21 (semester 1) dan 18 (semester 2). Rata-rata unit yang disetujui (approved) juga cukup tinggi, yaitu 21 (semester 1) dan 16 (semester 2).
- Nilai & Evaluasi: Nilai maksimum yang dicapai di semester 1 dan 2 adalah 18 dan 17. Ada juga unit tanpa evaluasi yang signifikan (maksimal 8 di semester 1, 12 di semester 2).
- Implikasi: Ini mengindikasikan bahwa mahasiswa yang dropout bukan berarti sama sekali tidak terlibat atau berprestasi. Banyak dari mereka sempat mengambil dan bahkan menyelesaikan sejumlah unit dengan nilai yang lumayan, sebelum akhirnya memutuskan untuk putus kuliah. Unit tanpa evaluasi bisa menjadi sinyal dini masalah.

### Rekomendasi Action Items (Optional)

1. Intervensi Finansial & Dukungan Ekonomi:
- Sistem Peringatan Dini Tunggakan Biaya Kuliah: Implementasikan sistem otomatis yang memberikan peringatan dini kepada mahasiswa dan/atau pembimbing/wali jika ada keterlambatan pembayaran biaya kuliah, diikuti dengan penawaran solusi atau bantuan (misalnya, cicilan, penundaan, atau informasi beasiswa).
- Peningkatan Program Beasiswa & Bantuan Keuangan: Perluas cakupan dan jenis beasiswa (terutama beasiswa berbasis kebutuhan) atau program bantuan keuangan lainnya, mengingat mayoritas dropout bukan pemegang beasiswa dan banyak yang memiliki tunggakan biaya.
- Konseling Keuangan: Sediakan layanan konseling keuangan bagi mahasiswa untuk membantu mereka mengelola anggaran, memahami opsi pinjaman pendidikan, dan mencari sumber pendanaan tambahan, terutama bagi mereka yang teridentifikasi sebagai debitur.
  
2. Dukungan Adaptasi & Kesejahteraan Mahasiswa:
- Program Adaptasi untuk Mahasiswa Lajang & Displaced: Kembangkan program orientasi atau komunitas yang lebih terfokus untuk mahasiswa lajang dan mereka yang "displaced" (jauh dari rumah/keluarga). Ini bisa berupa grup dukungan, kegiatan sosial, atau fasilitas tempat tinggal yang terjangkau.
- Dukungan Psikososial Terpadu: Perkuat layanan konseling dan dukungan mental/emosional. Mahasiswa dengan usia rata-rata 26 tahun yang dropout mungkin menghadapi tekanan hidup yang lebih kompleks di luar akademik.
- Program Mentoring Khusus: Pertimbangkan program mentoring di mana mahasiswa senior atau staf pengajar dapat membimbing mahasiswa baru atau mereka dari latar belakang pendidikan/pekerjaan orang tua yang kurang menguntungkan, membantu mereka menavigasi tantangan akademik dan sosial.
  
3. Tinjauan Kurikulum & Dukungan Akademik Khusus Program Studi:
- Evaluasi Program Studi dengan Angka Dropout Tinggi: Lakukan evaluasi menyeluruh terhadap kurikulum, metode pengajaran, beban kerja, dan peluang karier di program studi Management (evening attendance) dan Management yang memiliki tingkat dropout tinggi. Identifikasi titik-titik kesulitan spesifik.
- Sistem Peringatan Dini Keterlibatan Akademik: Kembangkan sistem untuk memonitor keterlibatan mahasiswa pada unit mata kuliah, terutama jika terdapat "unit tanpa evaluasi". Ini bisa menjadi indikator awal masalah akademik atau motivasi, dan memungkinkan intervensi lebih awal (misalnya, konseling akademik atau tutorial).
- Dukungan Akademik Terpersonalisasi: Tawarkan dukungan akademik tambahan (tutorial, bimbingan belajar) untuk mata kuliah-mata kuliah yang seringkali menyebabkan unit tanpa evaluasi atau nilai rendah di kalangan mahasiswa dropout.

4. Optimalisasi Proses Pendaftaran & Orientasi:
- Evaluasi Jalur Aplikasi Berisiko Tinggi: Tinjau proses penerimaan dan orientasi untuk mahasiswa yang mendaftar melalui mode "Over 23 years old" dan "1st phase - general contingent". Pastikan ekspektasi mereka terkelola dengan baik dan mereka mendapatkan dukungan adaptasi yang memadai sejak awal.
- Program Retensi Awal: Pertimbangkan program retensi yang difokuskan pada bulan-bulan atau semester pertama bagi kelompok-kelompok berisiko tinggi yang teridentifikasi dari mode aplikasi.
  
5. Pemantauan Berkelanjutan & Pengambilan Keputusan Berbasis Data:
- Pembentukan Tim Retensi: Bentuk tim lintas departemen (HR, Kemahasiswaan, Akademik, Keuangan) yang secara rutin meninjau dashboard dan menginterpretasikan data untuk mengidentifikasi mahasiswa berisiko.
- Pengembangan Protokol Intervensi: Buat protokol yang jelas tentang jenis intervensi apa yang harus dilakukan ketika seorang mahasiswa teridentifikasi berisiko dropout (misalnya, panggilan dari pembimbing akademik, penawaran konseling, atau bantuan keuangan).
- Iterasi Model & Dashboard: Lakukan pembaruan data dan evaluasi model serta dashboard secara berkala (misalnya, setiap semester) untuk memastikan relevansi dan akurasinya seiring waktu, mengingat kemungkinan adanya perubahan tren atau faktor pemicu.
