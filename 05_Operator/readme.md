06-12-2022
# OPERATOR
Operator dalam javascript adalah simbol untuk melakukan operasi.

Operator terbagi berdasarkan jumlah operand nya yaitu : 
- Binary    
    Operator yang membutuhkan 2 operand (operand1 operator operand2).   
    Aritmatika, Penugasan, Perbandingan, Logika, String.
- Ternary   
    Operator yang membutuhkan 1 operand (operator operand/operand operator).    
    Kondisional
- unary     
    Operator yang membutuhkan 3 operand.    
    Typeof

## Aritmatika
    Terdapat 5 operator pada aritmatika yaitu : 
    - +, Penjumlahan
    - -, Pengurangan
    - *, Perkalian
    - /, Pembagian
    - &, Modulo/Modulus/Sisa bagi.  
         Jika tidak terdapat sisa bagi maka akan menjadi 0 dan jika terdapat sisa bagi maka akan muncul 1.

    Terdapat juga Operator precedence atau urutan operasi matematika yaitu : 
    () * / + -     
## Penugasan
    Biasa disebut juga assignment, Operaot dibawah ini akan menimpa/mengganti nilai dari sebuah variabel.
    - =
    Operator dibawah ini tidak akan menimpa nilai variabel yg sudah ada.
    - +=, contoh x += y | x = x + y 
    - -=
    - *=
    - /=
    - %=
## Perbandingan
    Biasa disebut juga comparison. berfungsi untuk membandingankan 2 buah operand. 
    hasil perbandinganya akan menghasilkan nilai boolean (True or False).
    Operatornya : 
    - == , sama dengan
    - != , tidak sama dengan
    - === , strict (membandingkan identitas tipe data juga) sama dengan
    - !== , strict tidak sama dengan
    - > , lebih besar dari
    - < , lebih kecil dari
    - >= , lebih besar sama dengan 
    - <= , lebih kecil sama dengan
## Logika
    Biasa disebut juga logical operator. operator ini digunakan untuk menentukan logka dari beberapa ekspresi yang kita gabungkan. Yaitu :  
    - &&, AND , dua-dua nya harusnya true agar muncul true,jika hanya salah satu maka akan muncul false.
    - ||, OR , asal salah satu benar maka akan muncul true.
    - !, NOT , bisa juga dibilang mengubah nilai true menjadi false dan sebaliknya.
## String
    Menggunakan operator +, jika operandnya angka maka akan menjadi operator aritmatika dan jika operandnya adalah string/teks maka akan menjadi operator penggabung string.    
    - Jika awalnya string maka hasilny akan menjadi string semua.
    - Jika awalny angka maka hasilny akan menjumlahkan angka terlebih dahulu lalu baru menjadi string. 
## Kondisional
    Berfungsi untuk melakukan pengecekan pada sebuah kondisi dan menentukan hasil dari nilai true dan false.
    - (kondisi) ? true : false
    - (10 < 11) ? "benar" : "salah".
## Typeof
    Berfungsi untuk melihat tipe data pada sebuah variabel.
    - type(operand)