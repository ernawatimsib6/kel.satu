# kel.satu
tugas Git di msib data warehousing v
repositori berisi tugas assignment python part 4 dan 5
# task 1 ( basic oop)
Di dalamnya berisi beberapa metode:
Extract () : membaca data dari sebuah file csv
transform() : melakukan pembersihan dan transformasi pada data  (seperti mengubah format tanggal atau membersihkan kotak yang kosong )
store () : menyimpan data yang sudah di transformasi ke dalam struktur data framet
# variabel
df = variabel untuk menyimpan data frame
data_tranformed = berisi data marketing data yang telah di transformasi
etl_processor = objek dari kelas marketing data . di buat dengan menggunakan fungsi marketingDataETL ('/content/marketing_data.csv')
# Task 2 inheritance dan polymorphism
menggunakan inheretance untuk membuat class targedmarketingETL yang mewarisi dari marketingdataETL
kemudian  Menambahkan metode segment_customers() yang mengelompokan pelanggan berdasarkan kriteria tertentu
 dan mendemonstrasi polymorphism dengan meng-ovvride metode transform() dalam targedmarketingETL  Untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi
 # variabel
 class targedmarketingETL 
 etl =
 etl.transform =
 etl,segment_customers =
 etl.stored =
 
