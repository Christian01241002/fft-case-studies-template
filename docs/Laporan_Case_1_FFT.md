# Case Study 1: Solar Cycle Analysis Using FFT

## Nama

Christian Mayone Permana (kerja sendiri) 01241002

## Tujuan

Menganalisis data jumlah sunspot (bintik matahari) menggunakan Fast
Fourier Transform (FFT) untuk menentukan periode dominan siklus
aktivitas matahari.

## Metode

1.  Memuat data sunspot dari file CSV.
2.  Memvisualisasikan data pada domain waktu.
3.  Menghilangkan komponen DC dengan mengurangi nilai rata-rata data.
4.  Menghitung Fast Fourier Transform (FFT) menggunakan NumPy.
5.  Membentuk spektrum frekuensi dan mencari frekuensi dominan.
6.  Mengonversi frekuensi dominan menjadi periode fisik.

## Hasil

-   Dominant Frequency: **0.0923 cycles/year**
-   Solar Cycle Period: **10.84 years**

## Analisis

Analisis FFT berhasil mengidentifikasi komponen periodik dominan pada
data historis sunspot. Frekuensi dominan yang diperoleh adalah 0.0923
cycles per year yang menghasilkan periode sekitar 10.84 tahun. Hasil ini
sangat dekat dengan nilai Schwabe Solar Cycle yang diterima secara luas,
yaitu sekitar 11 tahun. Hal ini menunjukkan bahwa metode FFT efektif
dalam mengekstraksi informasi periodik penting meskipun data mengandung
noise dan fluktuasi alami. Puncak-puncak sekunder pada spektrum dapat
berasal dari harmonik, variasi aktivitas matahari lainnya, atau efek
keterbatasan sampling data.

## Tools dan Software

-   Python
-   NumPy
-   Pandas
-   Matplotlib
-   Jupyter Notebook
-   Visual Studio Code

## Penggunaan AI dalam Pengerjaan

Dalam pengerjaan tugas Case Study 1 ini, digunakan beberapa tools berbasis kecerdasan buatan (AI) untuk membantu proses pemahaman, debugging, dan penyusunan laporan, yaitu:

1. **ChatGPT (GPT-5.3-mini)**  
   Digunakan untuk membantu penjelasan konsep Fast Fourier Transform (FFT), debugging error pada Python, serta pembuatan laporan dalam format Markdown.
2. **Google Gemini (Gemini 3.1 Pro)**  
   Digunakan untuk membantu generate kode Python dan memberikan alternatif solusi dalam analisis data time series.
3. **Anthropic Claude (Claude Sonnet 4.6)**  
   Digunakan untuk membantu memahami referensi teori dan memberikan penjelasan tambahan terkait interpretasi hasil analisis FFT.

### Software dan Tools
- **Visual Studio Code (VS Code)**  
  Digunakan sebagai text editor utama untuk menulis dan menjalankan file Python serta Jupyter Notebook.

- **Jupyter Notebook**  
  Digunakan untuk melakukan komputasi interaktif, analisis data, serta visualisasi grafik.

- **Git & GitHub**  
  Digunakan untuk version control, menyimpan repository tugas, serta proses fork, commit, dan push.

- **Jupyter nbconvert**  
  Digunakan untuk mengonversi file notebook (.ipynb) menjadi format HTML sebagai laporan akhir.

### Bahasa Pemrograman
- **Python 3.13**  
  Bahasa pemrograman utama yang digunakan dalam analisis data.

### Library Python
- NumPy (untuk komputasi numerik dan FFT)
- Pandas (untuk manipulasi data)
- Matplotlib (untuk visualisasi data)


## Kesimpulan

Analisis menggunakan Fast Fourier Transform (FFT) berhasil mengidentifikasi adanya pola periodik dominan pada data jumlah bintik matahari (sunspot). Hasil perhitungan menunjukkan bahwa frekuensi dominan berada pada 0.0923 cycles/year yang setara dengan periode sekitar 10.84 tahun. Nilai ini sangat mendekati siklus matahari yang dikenal sebagai Schwabe Cycle, yaitu sekitar 11 tahun.

Hal ini menunjukkan bahwa metode FFT sangat efektif dalam mengekstraksi informasi periodik dari data observasional yang bersifat noisy. Selain itu, keberadaan beberapa puncak kecil pada spektrum frekuensi mengindikasikan adanya variasi aktivitas matahari lainnya atau efek harmonik dari sinyal utama.

