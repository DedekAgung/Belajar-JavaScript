03-12-2022
# Tipe Data : Numbers/Angka
Kali ini saya belajar Tipe Data pada JavaScript Yaitu Number/Angka.
# Numbers
" numbers in javascript are double-precison floating point 64-bit format IEEE 754 values "

Di JavaScript tidak ada integer (bilangan bulat) yang ada hanya Floating Point (bilangan pecahan).
ukuran angka yang bisa ditampung JavaScript adalah 64-bit (2^64) atau 18 x 10^18. 

64-bit
1 bit untuk penanda jika negatif (-).
11 bit untuk exponent (e)
52 bit untuk angka sebenarnya untuk pecahan termasuk titik (.)
- jangan mengawali dengan angka 0 karena akan dianggap oktal (bilangan basis 8 (0-7))
   - 022 // 18 
- jangan menggunakan 0x karena akan dianggap bilangan hexadesimal (bilangan basis 16 (0-f)
  - 0xff 

- Angka tanpa desimal (integer)
  - 10, 1500, 12345
  - Bila kita melihat bilangan bulat pada JavaScript itu sebenarnya adalah bilangan pecahan namun tingkat akurat hanya sampai 15 digit.
- Angka dengan desimal (pecahan)
  - 3.14, 0.5 , 100.00
  - max 17 digit dibelakang , (koma)
  - hasil dari bilangan pecahan tidak terlalu akurat
- Eksponen
  - e akan menggantikan 0 dan angka setelah e adalah jumlah 0-nya  
  - 123e5 // 123e00000
- Bilangan negatif  
  - bilangan yang awalnya dimulai dari negatif (-)
  - min akan mengurangi 1 bit pada pecahan
- Bilangan Oktal
  - Bilangan basis 8 (0-7)
  - Diawali dengan 0
  - 022 // 18
- Bilangan Hexadesimal
  - Bilangan basis 16 (0-F)
  - Diawali dengan 0x
  - 0xFF // 255   
- Angka spesial
  - Infinty
    - 2/0 // Infinity
  - -Infinity
    - -2/0 // -Infinity
  - NaN (Not an Numbers)    
    - 0/0 // NaN 
    - bisa juga membagi angka dengan string     