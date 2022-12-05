# Laporan Resmi Praktikum Modul 5 Jaringan Komputer

Penyelesaian Soal Shift Modul 5 Jaringan Komputer 2022 <br>
Kelompok C03
- Aqil Ramadhan Hadiono - NRP 5025201261
- Christhoper Marcelino Mamahit - NRP 5025201249
- Zahra Fayyadiyati - NRP 5025201133

## Table of Contents
* [A](#A)
* [B](#B)
* [C](#C)

## A
### Instalasi Server
Berikut ini adalah isi dari script yang digunakan untuk melakukan instalasi yang sesuai pada Eden, WISE, Garden dan SSS.

**Eden**
```
apt-get update
apt-get install bind9 -y
```
**WISE**
```
apt-get update
apt-get install isc-dhcp-server -y
```
**Garden**
```
apt-get update
apt-get install apache2 -y
apt-get install php -y

service apache2 start

echo "
<?php
        echo \"Ini Garden\";
?>" > /var/www/html/index.php
```

**SSS**
```
apt-get update
apt-get install apache2 -y
apt-get install php -y

service apache2 start

echo "
<?php
        echo \"Ini SSS\";
?>" > /var/www/html/index.php
```

## B
