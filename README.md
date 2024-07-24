# Submission-DS-Terapan-1
# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Jaya Jaya Maju
## Business Understanding
Perusahaan Jaya Jaya Maju menghadapi masalah tingginya tingkat keluarnya karyawan (attrition). Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%. Oleh karena itu, perlu dianalisis faktor-faktor yang mempengaruhi tingkat keluarnya karyawan untuk membantu departemen HR dalam mengurangi tingkat attrition.
### Permasalahan Bisnis
Perusahaan kesulitan untuk mengelola karyawan. Hal ini akan berdampak pada penurunan kredibilitas perusahaan.
### Cakupan Proyek
1. Pengumpulan dan pengelolaan data karyawan
2. Membangun model machine learning
3. Melakukan analisa dari hasil model
4. Membuat dashboard untuk memvisualisasikan analisa
5. Memberikan rekomendasi tindakan
### Persiapan
[Sumber Data](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee)

Setup Environtment
```
!pip install pycaret
!pip install pycaret[analysis]
!pip install numpy==1.24.4 pandas==2.1.4 matplotlib==3.7.5 seaborn==0.13.2
```
## Business Dashboard
Dashboard dibuat berdasarkan analisis yang telah ditentukan sebelumnya. Pada dashboard terdapat setidaknya 6 faktor yang mempengaruhi tingginya angka attrition di perusahaan. Pada halaman pertama menjelaskan tentang faktor attrition secara umum. Pada Halaman kedua menjelaskan secara spesisfik di department mana yang menjadi angka attrition terbesar beserta faktornya.
[Link Dashboard](https://lookerstudio.google.com/reporting/24d8290c-bf4d-4ff4-9f2e-6502ae3e9ac5)
### Rekomendasi Action Items
Berikut adalah rekomendasi yang dapat dilakukan perusahaan Jaya Jaya Maju untuk mengurangi tingkat attrition:
1. Department
   Perusahaan perlu mengevaluasi di bidang R&D karena pada bidang ini attrition paling tinggi yaitu 107 pekerja dari total 179 pekerja. Sehingga diperlukan evaluasi mendalam di bidang ini.
2. Marital Status
   Pekerja dengan status single paling tinggi attritionnya yang mencapai 9%. Perusahaan perlu melakukan dukungan mental atau sosial kepada pekerja dengan status single.
3. Business Travel
   Perusahaan perlu mengevaluasi perjalanan bisnis perusahaan. karena pekerja keluar karena jarang melakukan perjalanan bisnis mencapai 10% dari keseluruhan pekerja.
4. Job Satisfaction
   Perusahaan perlu meninjau kembali apakah pekerja nyaman dengan pekerjaan yang diberikan atau tidak. Karena 4% dari keseluruhan pekerja merasa bahwa pekerjaan yang diberikan tidak nyaman atau berada di indikator low
5. Overtime
   Sebanyak 9% pekerja yang keluar dan 20% pekerja yang tetap bekerja dari keseluruhan pekerja terjadi overtime atau lembur. Perusahaan perlu melakukan manajemen pengelolaan pekerjaan sehingga pekerja tidak terlalu terbeban.
6. Promosi Jabatan
   Perusahaan perlu meninjau kembali kebijakan tentang promosi jabatan. Karena pekerja yang keluar mencapai 12% pada tahun pertama. Promosi jabatan yang dilakukan juga harus disertakan dengan bertambahnya benefit-benefit lainnya.
