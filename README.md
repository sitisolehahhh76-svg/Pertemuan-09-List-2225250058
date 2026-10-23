# pertemuan 09 - List dan Pengolahan Data Numerik

Nama: siti solehah
NIM: 2225250058
Kelas: 3B

## Tujuan

Menggunakan list Python untuk menyimpan dan mengolah kumpulan data numerik, melakukan akses dan manipulasi elemen, menggunakan perulangan dan fungsi, serta menghitung statistik sederhana seperti total, rata-rata, nilai minimum, dan maksimum.

## Cara Menjalankan

Jalankan file latihan menggunakan Python 3 di terminal VS Code.

Contoh:

python3 latihan/01_buat_list.py

Untuk menjalankan program praktik utama:

python3 praktik/analisis_nilai_mahasiswa.py

## Struktur Program

- "01_buat_list.py": Membuat list berisi lima nilai dan menghitung banyak data.
- "02_indeks_slicing.py": Mengakses elemen pertama dan terakhir serta mengambil bagian list menggunakan slicing.
- "03_manipulasi_list.py": Mengubah, menambah, menyisipkan, dan menghapus elemen list.
- "04_agregasi_nilai.py": Menghitung total, rata-rata, nilai minimum, dan maksimum.
- "05_filter_kelulusan.py": Menampilkan nilai yang memenuhi batas kelulusan 60 dan menghitung jumlahnya.
- "06_fungsi_statistik.py": Membuat fungsi untuk menghitung rata-rata dengan memperhatikan list kosong.
- "analisis_nilai_mahasiswa.py": Mengolah data nilai mahasiswa, menghitung statistik, serta menampilkan jumlah mahasiswa yang lulus dan belum lulus.

## Hasil Pengujian

Pengujian dilakukan berdasarkan contoh dan test case pada modul Pertemuan 09.

- Membuat list "[75, 80, 65, 90, 88]" menghasilkan 5 data.
- Mengakses elemen pertama menghasilkan "75".
- Mengakses elemen terakhir menghasilkan "88".
- Total nilai "[75, 80, 65, 90, 88]" adalah "398".
- Rata-rata nilai tersebut adalah "79.60".
- Nilai minimum adalah "65" dan maksimum adalah "90".
- Data "[59, 60, 61]" menghasilkan 2 nilai lulus dengan batas kelulusan 60.
- Fungsi rata-rata pada list kosong tidak menghasilkan error dan mengembalikan "0".

## Refleksi

Melalui praktikum ini, saya memahami bahwa list dapat digunakan untuk menyimpan banyak data dalam satu variabel sehingga lebih mudah diolah. Saya juga belajar menggunakan indeks dan slicing untuk mengambil data, serta melakukan perubahan elemen menggunakan "append", "insert", dan "remove". Selain itu, saya memahami penggunaan perulangan dan fungsi untuk menghitung statistik serta memeriksa kelulusan mahasiswa. Pengujian dengan beberapa test case membantu memastikan program berjalan dengan benar.