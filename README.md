# VisualisasiWSN

Untuk mennjalankan program gunakan ELH4691.jar yang ada di dalam folder dist

simpan data berformat .txt yang ingin di baca didalam folder data yang berada satu folder bersama ELH4691.jar
overwrite data yang ada saat ini didalam folder tersebut
gunakan nama file 2.txt jika banyak sensor >=1
gunakan nama file 4.txt jika banyak sensor >=3
gunakan nama file 6.txt jika banyak sensor >=5

contoh format data yang dapat dibaca adalah
SENSE 1 efef 2018-3-28 07:35:16.762 [62, 1115, -268]
SENSE 1 beba 2018-3-28 07:35:16.762 [-976, 307, -1385]
SENSE 1 efef 2018-3-28 07:35:16.762 [1513, -216, -622]
SENSE 1 beba 2018-3-28 07:35:16.762 [975, 265, 200]

SENSE 1-∞ = occurence (angka kemunculan ke x)
efef,beba = nama sensor
2018-x-xx = tanggal
07:xx:xx.xxx = jam
[xx,yy,zz] = nilai tangkap sumbu x,y,z

skala nilai tangkap adalah *1000
16g di sumbu x artinya [1600, 0, 0]

pastikan format data yang digunakan sudah seperti contoh diatas

pastikan nama sensor yang digunakan terdaftar

daftar nama sensor
efef beba
affe aaaa
bbbb abab
