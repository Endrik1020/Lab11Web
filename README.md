# Lab11Web
# Praktikum 11
~~~
Nama  : Endrik
NIM   : 311910088
Kelas : TI.19.C1
~~~
# Persiapan 
Buat folder baru dengan nama lab11_php_ci pada docroot webserver (htdocs)
![1](https://user-images.githubusercontent.com/81820421/122064547-6e021080-ce1b-11eb-95f5-84ff3bef9fe3.JPG)

# Langkah-langkah Praktikum
Persiapan
Sebelum memulai menggunakan Framework Codeigniter, perlu dilakukan konfigurasi 
pada webserver. Beberapa ekstensi PHP perlu diaktifkan untuk kebutuhan 
pengembangan Codeigniter 4.
Berikut beberapa ekstensi yang perlu diaktifkan:
• php-json ekstension untuk bekerja dengan JSON;
• php-mysqlnd native driver untuk MySQL;
• php-xml ekstension untuk bekerja dengan XML;
• php-intl ekstensi untuk membuat aplikasi multibahasa;
• libcurl (opsional), jika ingin pakai Curl.
## Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian  Apache klik Config -> PHP.ini

![3](https://user-images.githubusercontent.com/81820421/122065064-d94be280-ce1b-11eb-8fe0-f55f9fe0b826.png)
## Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan  diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.
![2](https://user-images.githubusercontent.com/81820421/122065942-87578c80-ce1c-11eb-9430-215d7d4db5e8.JPG)

# Instalasi Codeigniter 4
Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara 
manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara 
manual.
• Unduh Codeigniter dari website https://codeigniter.com/download
• Extrak file zip Codeigniter ke direktori htdocs/lab11_ci.
![3](https://user-images.githubusercontent.com/81820421/122070538-419cc300-ce20-11eb-88ac-37684f775373.JPG)

• Ubah nama direktory framework-4.x.xx menjadi ci4.
![4](https://user-images.githubusercontent.com/81820421/122070758-6d1fad80-ce20-11eb-8093-3c1089c6a724.JPG)

• Buka browser dengan alamat http://localhost/lab11_php_ci/ci4/public
