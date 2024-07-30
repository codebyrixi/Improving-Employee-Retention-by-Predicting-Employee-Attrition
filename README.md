# Improving Employee Retention by Predicting Employee Attrition Using Machine Learning
Project ini merupakan project yang bertujuan untuk meningkatkan retensi karyawan dengan memprediksi atrusi karyawannya. Project ini dibuat menggunakan bahasa pemrograman Python 

## Daftar Isi
- Data Preprocessing
- Laporan Tahunan Perubahan Jumlah Karyawan
- Analisis Alasan Mengundurkan Diri Untuk Strategi Manajemen Attrusi Karyawan
-
-

## Bagian 0: Pendahuluan
**1. Background** <br>
Sumber daya manusia (SDM) adalah aset utama yang perlu dikelola dengan baik oleh perusahaan agar tujuan bisnis dapat tercapai dengan efektif dan efisien. Pada kesempatan kali ini, kita akan menghadapi sebuah permasalahan tentang sumber daya manusia yang ada di perusahaan. Fokus kita adalah untuk mengetahui bagaimana cara menjaga karyawan agar tetap bertahan di perusahaan yang ada saat ini yang dapat mengakibatkan bengkaknya biaya untuk rekrutmen karyawan serta pelatihan untuk mereka yang baru masuk. Dengan mengetahui faktor utama yang menyebabkan karyawan tidak merasa, perusahaan dapat segera menanggulanginya dengan membuat program-program yang relevan dengan permasalahan karyawan.<br>

**2. Goals** <br>
Proyek ini bertujuan untuk mengatasi masalah kritis dari pengurangan karyawan dengan memanfaatkan machine learning. Retensi karyawan tidak hanya penting untuk kesejahteraan tenaga kerja, tetapi juga untuk keberhasilan dan stabilitas organisasi apapun.<br>

**3. Objective** <br>
Membuat visualisasi berbasis data sebagai insight bagi perusahaan, terutama HR

**4. Feature Description**
| Feature                            | Description                                                     |
|------------------------------------|-----------------------------------------------------------------|
| `Username`                           | Nama pengguna karyawan yang unik.                               |
| `EnterpriseID`                       | Identitas dalam perusahaan.                                     |
| `StatusPernikahan`                   | Status perkawinan.                                              |
| `JenisKelamin`                       | Jenis kelamin.                                                  |
| `StatusKepegawaian`                  | Status pekerjaan.                                               |
| `Pekerjaan`                          | Posisi pekerjaan.                                               |
| `JenjangKarir`                       | Tingkat karier.                                                 |
| `PerformancePegawai`                 | Peringkat kinerja.                                              |
| `AsalDaerah`                         | Wilayah asal.                                                   |
| `HiringPlatform`                     | Platform digunakan untuk menyewa.                               |
| `SkorSurveyEngagement`               | Skor pertunangan.                                               |
| `SkorKepuasanPegawai`                | Nilai kepuasan karyawan.                                        |
| `JumlahKeikutsertaanProjek`          | Jumlah proyek yang berpartisipasi.                              |
| `JumlahKeterlambatanSebulanTerakhir` | Hitungan keterlambatan bulanan terbaru.                         |
| `JumlahKetidakhadiran`               | Jumlah absen.                                                   |
| `NomorHP`                            | Nomor telepon karyawan.                                         |
| `Email`                              | Alamat email karyawan.                                          |
| `TingkatPendidikan`                  | Tingkat pendidikan.                                             |
| `PernahBekerja`                      | Riwayat pekerjaan sebelumnya.                                   |
| `IkutProgramLOP`                     | Partisipasi dalam program tertentu (LOP).                       |
| `AlasanResign`                       | Alasan pengunduran diri (jika berlaku).                         |
| `TanggalLahir`                       | Tanggal lahir.                                                  |
| `TanggalHiring`                      | Tanggal perekrutan.                                             |
| `TanggalPenilaianKaryawan`           | Tanggal evaluasi karyawan.                                      |
| `TanggalResign`                      | Tanggal pengunduran diri untuk karyawan yang mengundurkan diri. |

## Bagian 1: Data Preprocessing
Pada proses ini dilakukan pemrosesan data sekaligus pembersihan data, yang terdiri dari pemeriksaan null / missing value, duplikasi data, dan konsistensi nilai. Hasilnya tertera pada tabel dibawah.
![image](https://github.com/user-attachments/assets/9b418864-bb5f-4685-b242-eef2a4e7d691)

## Bagian 2: Laporan Tahunan Perubahan Jumlah Karyawan
Grafik dibawah menunjukkan tren perubahan jumlah karyawan dari tahun ke tahunnya.
![image](https://github.com/user-attachments/assets/37d7d3c2-c96b-437f-b2b1-5ec9ea6223f7)
Berdasarkan grafik diatas, dapat dilihat bahwa:
1. Selama 2006-2013, jumlah karyawan yang masuk relatif rendah, dan ada peningkatan bertahap pada karyawan yang keluar.
2. Pada 2013, sejumlah besar karyawan mengundurkan diri, mengakibatkan penurunan tajam pada total karyawan yang tersisa. Tren ini berlanjut pada 2014 dan 2015. Peningkatan karyawan yang keluar mungkin disebabkan oleh berbagai faktor seperti ketidakpuasan pekerjaan, kesempatan kerja di tempat lain, dan lain sebagainya.
3. Jumlah karyawan yang masuk pada 2015-2017 tetap moderat, tetapi jumlah karyawan yang keluar tetap tinggi.
4. Pada 2018, jumlah karyawan yang masuk sangat rendah, sedangkan jumlah karyawan yang keluar secara signifikan lebih tinggi. Hal ini menyebabkan penurunan drastis pada total karyawan yang tersisa. Tren peningkatan pengunduran diri mungkin disebabkan oleh masalah internal atau faktor eksternal yang mempengaruhi stabilitas pekerjaan.

## Bagian 3: Analisis Alasan Mengundurkan Diri Untuk Strategi Manajemen Attrusi Karyawan
![image](https://github.com/user-attachments/assets/1f9f8348-5659-46e5-8307-9fd758f6c5f8)
Terlihat bahwa Software Engineer adalah divisi yang paling dominan pada perusahaan dengan total 73,71% dari persentase dari seluruh divisi menunjukkan betapa pentingnya peran Software Engineer di perusahaan. Kemudian, divisi yang dominan diikuti oleh UI & UX dengan 7,73%, sementara divisi sisanya di bawah 6% menunjukkan beberapa asumsi bahwa ini mungkin ada beberapa hierarki struktural peran penting bagi perusahaan seperti Software Engineer.
