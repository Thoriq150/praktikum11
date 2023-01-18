# Praktikum11

# Pertemuan 15
<img width="959" alt="213110642-f9553a9d-c8b8-409c-8777-b5779b34bce4" src="https://user-images.githubusercontent.com/115950790/213148995-d9f9159f-ccbf-48a9-963f-cdb9a1994f4a.png">


# Penjelasan
!pip install pandas digunakan untuk menginstall package pandas di python. Package pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis. Fungsi dari package pandas sangat luas, seperti melakukan operasi pada data, mengimport dan mengeksport data dari berbagai format, dan lainnya. !pip install requests digunakan untuk menginstall package requests di python. Package requests digunakan untuk melakukan HTTP request dari python.

!pip install BeautifulSoup4 digunakan untuk menginstall package BeautifulSoup4 di python. Package BeautifulSoup4 digunakan untuk parsing dan mengelola data dari HTML atau XML.

import pandas as pd digunakan untuk mengimport library pandas dan menyebutnya sebagai pd. Library pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis.

from bs4 import BeautifulSoup digunakan untuk mengimport class BeautifulSoup dari package BeautifulSoup4. Class BeautifulSoup digunakan untuk mengelola dan mengolah data dari HTML atau XML.
![arat](https://user-images.githubusercontent.com/115950790/213149086-5530054c-3a19-4c14-aaa4-e11764f941b6.png)

# Penjelasan

mengambil data lowongan kerja dari situs web Glints. Dengan menggunakan library Python 'requests', kodingan mengirim permintaan GET ke URL "https://glints.com/id/lowongan-kerja" yang merupakan halaman web yang berisi informasi lowongan kerja. Kemudian, dengan menggunakan library 'BeautifulSoup', kodingan menganalisis konten halaman web yang didapat dari permintaan GET tersebut dengan menggunakan parser HTML.

Selanjutnya, kodingan mencari semua elemen HTML dengan atribut 'div' dan 'id' yang sesuai, yaitu '__next'. Kemudian, dari elemen-elemen tersebut, kodingan mengekstrak informasi pekerjaan, lokasi, dan nama perusahaan dengan mencari elemen yang memiliki atribut 'class' yang sesuai. Informasi yang diambil kemudian disimpan dalam sebuah list yang sesuai.

Setelah itu, kodingan menggunakan library pandas untuk membuat dataframe dari list yang didapat dan menyimpannya dalam variabel 'df'. Kemudian kodingan mencetak dataframe tersebut, sehingga kita dapat melihat informasi lowongan kerja yang diambil dari situs web Glints.

# OUTPUT
![image](https://user-images.githubusercontent.com/115771479/213117818-5dd167e1-17b8-40ab-81f1-5ae5aca0e996.png)
