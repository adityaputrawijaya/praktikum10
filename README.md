 # praktikum10
  
 Nama  : ADITYA PUTRA WIJAYA
  
 NIM   : 312210207
  
 Kelas : TI.22.A.2
  
 ## DAFTAR ISI <br> 
 | No | Description | Link | 
 |-----|------|-----| 
 |1|Python String|[Click Here](#Python-String)| 
 |2|Latihan 1|[Click Here](#Latihan-1)| 
 |3|Latihan 2|[Click Here](#Latihan-2)| 
  
 ### Python String 
 - String adalah jenis yang paling populer di Python. 
 - Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip. 
 - Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" "). 
 - Membuat string semudah memberi nilai pada sebuah variabel. 
  
 ### Latihan 1 
  
 ![Soal Latihan 1](https://user-images.githubusercontent.com/115867244/209518488-643ebee6-ed6b-48af-bb5f-08c9196e24d4.png) 
  
 #### Penjelasan Latihan 1 
 - Untuk menghitung jumlah karakter, gunakan fungsi `len()`. 
  
       # Menghitung jumlah karakternya 
       print(len(txt)) 
        
 - Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku `[ ]` dan deklarasi nomor di dalam kurung siku dengan urutan **ARRAY** dan menggunakan titik dua lalu masukan nomor **ARRAY** selanjutnya. 
 Untuk mengambil karakter terakhir, gunakan **index [-1]**. Sedangkan untuk mengambil karakter *index ke-2* sampai *ke-4*, gunakan **index [2:5]**. 
  
       # Mengambil karakter terakhir 
       print(txt[-1]) 
       # Mengambil karakter index ke-2 sampai index ke-4 (llo) 
       print(txt[2:5]) 
        
 - Jika ingin menghilangkan spasi pada string, gunakan method `replace()`. Method **replace()** mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan. 
 - Di dalam method **replace**, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan `(txt.replace(" ", ""))` dan kedua dengan cara `(txt.replace(txt[5], ""))`. 
  
       # Menghilangkan spasi pada text tersebut (HelloWorld) 
       print(txt.replace(" ", "")) 
        
 - Untuk mengubah huruf menjadi besar, gunakan method `upper()`. Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method `lower()`. 
  
       # Mengubah text menjadi huruf besar 
       print(txt.upper()) 
       # Mengubah text menjadi huruf kecil 
       print(txt.lower()) 
        
 - Untuk mengganti karakter `'H'` dengan karakter `'J'`, gunakan method `replace()`. 
  
       # Mengganti karakter H dengan karakter J 
       print(txt.replace("H", "J")) 
       print() 
        
 #### Output Latihan 1 
 ![1](https://user-images.githubusercontent.com/115678251/209728549-66533d53-3cf7-44a5-92e4-402e97fb2913.png) 
  
  
  
 ### Latihan 2 
  
 ![Soal Latihan 2](https://user-images.githubusercontent.com/115867244/209519946-c3b1ec80-a683-48d6-a43b-0dbd2d716631.png) 
  
 #### Penjelasan Latihan 2 
 Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal `{}` untuk menempatkan variable sebelumnya. 
  
       umur = 24 
       txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n" 
  
       print(txt.format(umur)) 
        
 #### Output Latihan 2 
 ![2](https://user-images.githubusercontent.com/115678251/209728614-8e1d57be-5b02-497e-9fef-3ee2bcd602bf.png) 
  
  
  
 ## Terima Kasih
