# *UAS SEMESTER 1* 

## NAMA  : Kartika Tunggal Dewi
## NIM   : 312110257
## KELAS : TI.21.C5

Pada UAS di pertemuan kali ini, saya di beri tugas oleh dosen saya, yaitu di antaranya : 

![](img/soal1.png)

Dan ini adalah hasil package yang sudah saya buat :

![](img/2.png)

# SOAL 1 (Daftar_Nilai)

Pada soal pertama, dibawah ini saya telah menyantumkan beberapa syntax yang nantinya akan menghasilkan semua modul dari package Daftar_Nilai yang diantaranya adalah (Tambah Data, Ubah Data, Hapus Data, Dan Cari Data)

```py

from view.input_nilai import *
data={}
class daftarnilai():
    def tambah_data(self):
        tambah_nama = nama()
        tambah_nim = nim()
        tambah_tugas = tugas()
        tambah_uts = uts()
        tambah_uas = uas()
        tambah_akhir = akhir()
        data[tambah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir

    def ubah_data(self):
        ubah_nama = nama()
        if ubah_nama in data.keys():
           
            tambah_nim = nim()
            tambah_tugas = tugas()
            tambah_uts = uts()
            tambah_uas = uas()
            tambah_akhir = akhir()
            data[ubah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir
        else:
            print('data tidak ditemukan !!!')

    def hapus_data(self):
        hapus_nama = nama()
        if hapus_nama in data.keys():
            del data[hapus_nama]
            print('data berhasil di hapus')
        else:
            print('data tidak ditemukan !!!')

    def keluar(self):
        print('TERIMAKASIH')
```

Jadi kesimpulannya jika kalian menggunakan syntax yang saya tunjukan diawal dan memasukan angka '1' pada kolom yang tersedia dan kalian run, maka akan mendapat output seperti dibawah ini, yang dimana itu adalah hasil untuk menambahkan data.

![](img/tambah.png)

Kedua untuk menghasilkan modul Ubah Data kamu perlu memasukan '2' dan menghasilkan output seperti di bawah ini :

![](img/ubah.png)

ketiga untuk menghasilkan modul hapus data kamu perlu memasukan '4' dan menghasilkan output seperti di bawah ini :

![](img/hapus.png)

Untuk mencari data itu sendiri kalian hanya perlu memasukan inisial dari modul tersebut. Misalkan kalian ingin mencari moodul untuk Menghapus Data, maka kamu hanya perlu memasukan angka '4' pada kolom yang tersedia.

# SOAL 2 (View_Nilai)

Untuk menjawab soal nomer 2, kalian hanya perlu mengetikan angka "5" pada kolom yang di sediakan untuk melihat hasil pencarian ataupun daftar nilai. Maka nanti akan mendapatkan hasil output seperti gambar dibawah ini.

![](img/nilai.png)

# SOAL 3 (Input_Nilai)

Pada soal ke-3 ini, jika kalian ingin menginput suatu data yaitu sama halnya seperti kalian memasukan angka "1" untuk menambahkan suatu data. Dan hasil output yang dihasilkan pun sama yaitu sebagai berikut.

![](img/input.png)

## **TERIMAKASIH**


