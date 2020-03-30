# PENGENALAN-BIG-DATA
145410091 I PUTU NGURAH PRAYOGA
JAWABAN UTS
1. Cari dan sebutkan 3 DBMS yang bisa digunakan untuk mengelola big data!
    Jawab:
    - MySQL
    - Oracle
    - Firebird
2. Carilah contoh masalah big data yang bisa dikelola menggunakan salah satu DBMS tersebut, jelaskan mulai dari instalasi sampai CRUD untuk data menggunakan DBMS tersebut. Asumsikan anda akan memecahkan masalah big data yang sudah anda cari contoh tadi, jelaskan kira-kira bagaimana arsitektur dari solusi big data menggunakan DBMS tersebut, gambarkan diagramnya.
    Jawab : 
    - DBMS MySQL
    - Contoh masalah seperti sebuah toko online yang mencatat seluruh transaksi pembeli pada suatu basis data (database) misalkan MySQL. Tidak ada yang salah dalam hal ini, semua baik-baik saja, sampai suatu saat query yang dilakukan ke database tadi sudah tidak reliable lagi karena toko semakin berkembang, pelanggan semakin banyak, yang awalnya toko hanya melakukan transaksi dibawah 100 dalam sehari pada ahirnya toko dapat melakukan 1.000.000 transaksi dalam sehari.
Solusi umum yang dilakukan adalah melakukan scale up (meningkatkan kapasitas server, baik meningkatkan kapasitas komputasi, penyimpanan, dan lain-lain) pada server MySQL yang dimiliki. Hal ini wajar, namun perlu diingat scale up memiliki keterbatasan, dalam satu mesin/ instance/ host/ node (kita sebut node kedepannya) jumlah disk yang terpasang memiliki batas maksimal, kapasitas komputasi (core) juga memiliki batasan, bandwith keluar/masuk juga ada batas maksimal, dan lain sebagainya. Sehingga pada suatu titik dalam satu node sudah tidak dapat lagi di-scale up, misal per hari 1.000.000 transaksi tadi jika dikonversi ke penyimpanan data menjadi 20GB per hari, dalam sebulan sudah menjadi 600GB dan terus bertambah.
untuk proses instalasi MySQL, saya biasanya menggunakan server phpmyadmin dari PHP, langkahnya yaitu:
    1. install XAMPP
    2. ikuti proses instalasi, kemudian centang semua pilihan server yang diinginkan (server MySQL) 
    3. setelah semua proses dilakukan, buka XAMPP dan pilih icon start untuk menjalankan MySQL
    3. buka pada browser dan ketikkan phpmyadmin
    4. akan muncul tampilan mysql

