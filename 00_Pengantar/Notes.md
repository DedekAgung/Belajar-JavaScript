# Dasar Pemrograman
- Program adalah kumpulan/serangkaian instruksi.
- Pemrograman, cara kita untuk memberikan instruksi yang simpel dan terstruktu pada komputer.
- Instruksi yang kita berikan harus sesuai dengan aturan pada bahasa pemrograman tertentu.
- Statement, perintah untuk komputer dalam bahasa pemrograman.

# Bahasa Pemrograman
- bahasa yang dipahami Komputer/CPU adalah bahasa mesin.
- Bahasa pemrograman adalah bahasa yang menjembatani bahasa manusia dan bahasa mesin.
- Bahasa yang paling mendekati bahasa mesin adalah bahasa Assembly. 
- Bahasa yang paling mendekati bahasa mesin juga desebut bahasa tingkat rendah (low level language).
- Sedangkan bahasa yang mendekati bahasa manusia disebut bahasa tingkat tinggi (High Level Language)
- Semakin tinggi bahasanya maka akan semakin mudah dipahami manusia namun semakin lambat, karena bahasa tersebut harus diterjemahkan dan dioptimasi menjadi bahasa mesin.
- Source Code adalah serangkaian code menggunakan bahasa pemrograman apapun yang akan diterjemahkan menjadi bahasa mesin.
- Terdapat membuat Source Code 
  - Text editor sederhana
    - Text editor adalah software yang berfungsi untuk membuat text sederhana. (Notepad)
  - Code Editor 
    - Code Editor adalah Text Editor namun khusus untuk programming. (VS Code, Sublime Text)
  - IDE
    - Integrated Development Environment (IDE), adalah Code Editor yang memiliki fitur yang lebih lengkap dan complex. (Visual Studio).

# Menterjemahkan Source Code Menjadi Bahasa Mesin
Terdapat 2 cara untuk menerjemahkan Source Code menjadi bahasa mesin, yaitu dengan cara Compiler dan Interprenter.
- Compiler 
  - Source Code akan di compile terlebih dahulu lalu menjadi file baru yaitu .exe file/executable file (file sudah bisa di eksekusi).
  - Kelebihan
    - Siap dijalankan dan lebih cepat karena sudah menjadi Exe file yang tinggal di buka saja tanpa harus di Compile terlebih dahulu.
    - Source Code tidak terlihat dan lebih aman
  - Kekurangan 
    - Tidak lintas Platform, Karena setelah di compile hasil compilenya hanya akan Compatible pada sistem operasi (CPU) tertentu. jadi harus di compile ulang pada sistem operasi tersebut (CPU).
    - Tidak Fleksibel, Karena ketika terjadi kesalahan kita harus Compile ulang.
  - C, C++, Objecctive-C
- Interpreter
  - Source Code akan di Interpreter lalu program pun berjalan.
  - Kelebihan
    - Lintas Platform, Tidak peduli sistem operasinya (CPU) apa, asal punya interpreternya source code nya dapat dijalankan.
    - Fleksibel, karena tidak perlu di compile ulang, jadi mudah untuk dimodifikasi dan lebih mudah di uji.
  - Kekurangan
    - Butuh Interpreter seperti Browser.
    - Lebih lambat karena kita harus intrepretasi terlebih dahulu
    - Source Code mudah diakses oleh orang lain 
  - JavaScript, PHP.
- Namun ada 1 lagi yaitu Hybrid
  - Hybrid atau bisa juga desebut Intermediate Language adalah menggabungkan kelebihan Compiler dan Interpreter
    - Setelah di Compile Source Code menjadi (IL) Intermediate Language/Byte Code dan belum executeable. Byte Code sudah Teroptimalisasi untuk bahasa mesin dan Cross Platform.
    - lalu file IL di JIT (Just In Time) compilation yaitu mengcompile dan menjalankan file tersebut.
  - Java, VB.NET, Python.

