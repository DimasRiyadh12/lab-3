# lab-3     
Latihan 1
![image](https://user-images.githubusercontent.com/73042485/98520323-75b96f80-22a4-11eb-896b-7c6ce1e10d1d.png)


![Screenshot (37)](https://user-images.githubusercontent.com/73042485/98521749-6dfaca80-22a6-11eb-9835-b2651d47fce8.png)

Penjelasan:

for row in range(0, 10): dan for col in range(0, 10): untuk membuat list antara 0 sampai 10
num = row + col nilai row dan col akan di tampung di variabel num
if num < 10: jika num lebh kecil dari 10 maka empty = " "
else: selain itu jika if num < 100: maka empty = " "
dan cetak print(empty, num, end = '') print()
Output:

![Screenshot (38)](https://user-images.githubusercontent.com/73042485/98522643-86b7b000-22a7-11eb-8b3e-6d9bd745dda5.png)


Latihan 2
latihan2

code-2

Penjelasan:

import random berfungsi untuk memanggil library random, dimana random berfungsi untuk menentukan pilihan secara acak
nilai = int(input('Masukan nilai n : ')) untuk menginputkan nilai berupa integer
range() berfungsi menghasilkan list
masukkan i = random.uniform (.0,.5) di gunakan untuk menampilkan bilangan float random, lalu masukkan a+=1 untuk memberi nomer pada bilangan float.
print('data ke :',a,'==>', i) untuk menampilkan output data
Output:

latihan2.2

Modul Praktikum 2
Latihan 1: Membuat program menentukan nilai akhir
code-1-2

Penjelasan:

Masukkan nilai yang sudah di tentukan oleh variabel, seperti nama, uts, uas,tugas
untuk akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uts) * .4)
if akhir > 80: Jika nilai akhir diatas 80, maka huruf = 'A'
elif akhir > 70: dan jika nilai akhir diatas 70, maka huruf = 'B'
elif akhir > 50: dan jika nilai akhir diatas 50, maka huruf = 'C'
elif akhir > 40: dan jika nilai akhir diatas 40, maka huruf = 'D'
else: selain itu maka huruf = 'E'
cetak nilai akhir print
Output:

latihan1-modul2

Latihan 2: Membuat program menampilkan status gaji karyawan
code-2-2

Penjelasan:

gaji = int(input("Masukkan gaji:")) masukkan jumlah gaji
if gaji > 3000000: jika gaji diatas 3jt, maka print ("Gaji sudah diatas UMR") jika tidak, maka else: print("Gaji belum UMR") dan juga pengkondisian yang lainnya
maka data akan di cetak sesuai data yang di isi
Output:

latihan2-modul2

Latihan 3: penggunaan kondisi OR program membandingkan 3 input bilangan, apabila penjumlahan 2 bilangan hasilnya sama dengan bilangan lainnya, maka cetak pernyataan “BENAR”
code-2-2

Penjelasan:

a = int(input('Masukkan bilangan A: ')) Masukkan bilangan A pada saat runtime, lakukan juga pada bilangan B dan C
if a+b == c or b+c == a or c+a == b: jika a+b = c atau b+c = a atau c+a = b maka print('benar')
selain itu maka else: print('salah')
Output:

latihan3-modul2

Tugas Praktikum 2
soal-praktikum-modul2

code-3-2

Penjelasan:

A = int(input('Masukkan bilangan pertama: ')) masukkan nilai bilangan pertama, dan lakukan juga pada bilangan kedua dan ketiga pada saat runtime
if A > B and A > C: jika A lebih besar dari B dan A lebih besar dari C maka print('Nilai', A, 'terbesar dari 3 bilangan yang di inputkan')
elif B > A and B > C: dan jika B lebih besar dari A dan B lebih besar dari C maka print('Nilai', B, 'terbesar dari 3 bilangan yang di inputkan')
else: selain itu maka print('Nilai', C, 'terbesar dari 3 bilangan yang di inputkan')
Output:

tugas-praktikum-modul2

Flowchart flowchart-praktikum-modul2

Modul Praktikum 3
Latihan 1
latihan1-modul3

code-1-3

Penjelasan:

import random berfungsi untuk memanggil library random, dimana random berfungsi untuk menentukan pilihan secara acak
nilai = int(input('Masukan nilai n : ')) untuk menginputkan nilai berupa integer
range() berfungsi menghasilkan list
masukkan i = random.uniform (.0,.5) di gunakan untuk menampilkan bilangan float random, lalu masukkan a+=1 untuk memberi nomer pada bilangan float.
print('data ke :',a,'==>', i) untuk menampilkan output data
Output:

latihan2.2

Latihan 2
latihan2-modul3

code-2-3

Penjelasan:

Integer max = 0

fungsi perulangan while true hingga menampilkan perulangan sampai batas tertentu.

Memasukan bilangan integer pada "a"

Menggunakan fungsi if jika max kurang dari nilai a, maka max sama dengan a

Mengunakan fungsi if jika nilai a adalah 0 maka fungsi break artinya perulangan berhenti jika menulis nilai 0

Mencetak nilai paling terbesar setelah break, sehingga menampilkan nilai terbesar diantara bilangan tersebut dalam perulangan.

Output:

latihan-2-out-modul3

Tugas Praktikum 3
program-1-modul3

code-3-3

Penjelasan:

Variabel a = 100.000.000 modal awal

Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan bulan 1 sampai bulan 8.

Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai 8

Bulan pertama dan kedua laba adalah 0

Bulan ke 3 dan ke 4 mendapat laba 1% sehingga modal di kali 1% = keuntungan

Bulan ke 5 mendapatkan laba 5%, sehingga modal dikali 5% = keuntungan

Bulan ke 8 mendapatkan laba 2% sehingga keuntungan menurun dari bulan sebelumnya, modal dikali 2% = keuntungan.

Menghitung jumlah total laba dengan menjumlah keuntungan dari bulan ke 1 sampai bulan 8, hasilnya adalah total keuntungan yang didapat total=b+b+c+c+d+d+d+e

print("\Total : ",total), untuk menampilkan hasil keseluruhan laba dari bulan pertama sampai bulan kedelapan.

Output:

program-1-out-modul3
