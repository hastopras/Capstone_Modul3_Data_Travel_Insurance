# Capstone_Modul3_Data_Travel_Insurance

Latar Belakang

Asuransi perjalanan adalah jenis asuransi yang memberikan perlindungan selama kita melakukan perjalanan baik di dalam negeri maupun di luar negeri. Beberapa negara bahkan mewajibkan pelancong untuk memiliki asuransi perjalananPermasalahan yang terjadi yaitu orang-orang setelah melakukan perjalanan mengajukan klaim asuransi dan orang-orang setelah melakukan perjalanan tidak mengajukan klaim asuransi dalam hal ini perusahaan agen merekrut freelance data science untuk memprediksi orang-orang mengajukan klaim dan orang-orang tidak mengajukan klaim setelah perjalanan. sasaran yang dituju untuk freelance yaitu Divisi Marketing pada perusahaan asuransi karena orang-orang mengajukan awal claim dari Divisi Marketing.

Modelling Data
Modelling Data rincian dapat lihat di Jupiter Notebook, ini hanya sedikit menjabarkan Modelling Data yang telah dilakukan. Sebagai berikut:
-	Model yang terbaik Logistic Regression dengan hasil sebelum tuning test set sebesar 0.791, nilai Train set sebelum tuning adalah 0.712. Nilai Train set setelah tuning adalah 0.733, hasil sesudah tuning test set sebesar 0.812
-	Berdasarkan model yang terbaik kita dapat menghitung kerugian asuransi perjalanan yang prediksinya tidak klaim dapat menurunkan kerugian persentase sebesar 80.6% sekali perjalanan.
-	Limitasi model pada data set ini yaitu berdasarkan net sales, karena harga net sales bergantung pada 5% dari total kesuluruhan biaya perjalanan yang dikeluarkan oleh calon penumpang

Rekomendasi
Harga total perjalanan sangat berpengaruh untuk mengurangi kerugian dari asuransi, maka perlu menambahkan harga total perjalanan dalam dataset ini
