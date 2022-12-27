# Praktikum12

Nama : Amanda Puspa Negara

NIM : 312210129

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Python String|[Click Here](#pythonstring)|
|2|Latihan 1|[Click Here](#latihan1)|
|3|Latihan 2|[Click Here](#latihan2)|

# Python String
- String adalah jenis yang paling populer di Python.
- Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
- Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").
- Membuat string semudah memberi nilai pada sebuah variabel.

## Latihan 1

![picture1](https://user-images.githubusercontent.com/115678845/209599902-6bc8f11b-a66d-4ce9-a396-7855dbc3b080.png)

#### Penjelasan Latihan 1
- Untuk menghitung jumlah karakter, gunakan fungsi `len()`.

      # Menghitung jumlah karakternya
      print(len(txt))
      
- Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku `[ ]` dan deklarasi nomor di dalam kurung siku dengan urutan *ARRAY* dan menggunakan titik dua lalu masukan nomor *ARRAY* selanjutnya.
Untuk mengambil karakter terakhir, gunakan *index [-1]. Sedangkan untuk mengambil karakter *index ke-2 sampai ke-4, gunakan *index [2:5]*.

      # Mengambil karakter terakhir
      print(txt[-1])
      # Mengambil karakter index ke-2 sampai index ke-4 (llo)
      print(txt[2:5])
      
- Jika ingin menghilangkan spasi pada string, gunakan method `replace()`. Method *replace()* mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.
- Di dalam method *replace*, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan `(txt.replace(" ", ""))` dan kedua dengan cara `(txt.replace(txt[5], ""))`.

      # Menghilangkan spasi pada text tersebut (HelloWorld)
      print(txt.replace(" ", ""))
      
- Untuk mengubah huruf menjadi besar, gunakan method `upper()`. Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method `lower()`.

      # Mengubah text menjadi huruf besar
      print(txt.upper())
      # Mengubah text menjadi huruf kecil
      print(txt.lower())
      
- Untuk mengganti karakter `'H'` dengan karakter `'J'`, gunakan method `replace()`.

      # Mengganti karakter H dengan karakter J
      print(txt.replace("H", "J"))
      print()
      
#### Output Latihan 1
      
![Screenshot (185)](https://user-images.githubusercontent.com/115678845/209603666-7ec3210e-db31-4fe7-b19e-278734a6e932.png)

### Latihan 2

![picture2](https://user-images.githubusercontent.com/115678845/209603716-e42a6ef8-87d7-4806-94e3-4a44d2be68ce.png)

#### Penjelasan Latihan 2
Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal `{}` untuk menempatkan variable sebelumnya.

      umur = 24
      txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

      print(txt.format(umur))
      
#### Output Latihan 2

![Screenshot (184)](https://user-images.githubusercontent.com/115678845/209603755-cf07128a-625d-4004-a8bc-c1f33e843c09.png)

## Sekian, Terima Kasih
