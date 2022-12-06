06-12-2022
# TIPE DATA
Kali ini saya mempelajari tipe data STRING dan BOOLEAN. 

## STRING   
    Tipe data string dalam javascript digunakan untuk mempresentasikan data tekstual (plain text).
    String ditentukan menggunakan " " atau ' '. Jika didalam string ingin menggunakan kutip dua (" ") maka kita bisa menggunakan kutip satu untuk menentukan string dan sebaliknya. dan jika kita ingin menggunakan kedua ' dan " pada sebuah string maka kita harus menggunakan escape character (\).
    - escape Character 
      - \0 untuk karakter NULL
      - \' untuk '
      - \" untuk "
      - \\ untuk \
      - \n untuk newline/baris baru
      - \t untuk tab
      - \b untuk backspace
      - \uxxxx untuk unicode
    di dalam string terdapat beberapa operator yaitu : 
    - == untuk membandingkan antar string
    - + untuk menggabungkan sebuah string
    terdapat juga beberapa fungsi, contohny : 
    - .length untuk menghitung panjang string, digunakan setelah " ".(fungsi)
## BOOLEAN
    Tipe data yang mempresentasikan True or False. biasanya digunakan pada statement pengkodisian, untuk menentukan aksi yang berbeda dan mengatur alur kendali program.
    - True, ketika kondisi benar.
    - false, ketika kondisi salah.
    di source code menggunakan boolean(nilai). di javascript nilai-nilai menyimpan nilai true or false disebut nilai truthy dan falsy.
    - Truthy
      - true
      - Non-zero number, seluruh angka selain 0
      - "string", string dengan isi
      - object 
      - arrays
      - functions
    - falsy
      - false
      - 0
      - "", string tanpa isi
      - undefined, variabel yang tidak memiliki nilai/isi.
      - null, Nilai kosong yang bisa kita berikan pada variabel contoh : x = null.
      - NaN
     
