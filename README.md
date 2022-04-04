# Sakila: Store n Staff

## Tujuan
Analisis performa toko dan staff dari Database Sakila.

## Sumber
https://dev.mysql.com/doc/sakila/en/

## Tools
* Python
    * Numpy
    * Pandas
    * Seaborn
    * Matplotlib
    * Scipy
    * Statsmodels
* Jupyter notebook
* MySQL


## Fokus Analisis
* Penjualan
* Transaksi
* Periode buka dan tutup
* Rental
* Lokasi pelanggan dan staff

## Tahapan
1. Mengambil data dari MySQL
2. Analisis dan visualisasi
3. Rangkuman

## Rangkuman Hasil 
* Dapat dilihat bahwa dari data sampai 2006 ini toko sakila memiliki pola buka toko dan transaksi yang cukup aneh.
* Toko tampak buka 24 jam dalam 8 hari periode dan akan tutup selama 21 hari berikutnya.
* Kebijakan 24 jam buka ini sebenarnya tidaklah salah, namun karena pada 1 toko hanya ada 1 staff, maka shift 24 jam selama 8 hari berturut-turut tidaklah masuk akal.
* Total sales dan sales per hari dalam 1 tahun tidaklah buruk, namun karena tidak ada data profit membuat susah menganalisis performa secara menyeluruh.
* Dalam hal rental, terdapat kerugian karena ada beberapa rental yang belum kembali.
* Potensi untuk replacement costnya adalah $1.800.
* Dalam hal pengembalian rentalpun banyak yang terlambat, hampir sekitar 40%.
* Kebijakan harus dibuat untuk menurutkan tingkat keterlambatan dan mencegah adanya rental yang tidak kembali.
* Salah satu caranya adalah mensyaratkan penyewa harus berada di 1 kota yang sama dengan pegawai dan toko.
* Ini berlandaskan bahwa ternyata banyak penyewa yang berasal dari luar negeri.
* Secara keseluruhan tidak ada perbedaan tingkat performa antara kedua toko dan kedua staff.
* Memang paling akhir adalah kebijakan perusahaan harus dibenahi.
