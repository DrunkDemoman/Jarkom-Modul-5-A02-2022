# VLSM

Kelompok kami memutuskan untuk menggunakan metode pembagian IP VLSM

## 1. Penentuan Netmask
Berikut tabel subnet yang digunakan untuk menentukan kebutuhan netmask dari setiap node. Ditentukan bahwa netmask /21 sudah cukup untuk menjadi root node dari tree VLSM karena hanya terdapat /22, /23, /24, /25, /29, /29, /30, /30, di mana pembagian netmask /21 sudah cukup untuk menutupi kebutuhan setiap node.

![Subnet Table](/VLSM/img/subnet-table.png)

## 2. Pembagian IP
Dibuatkan tree dari penentuan subnet dan node root. Berdasarkan tree VLSM yang dibuat, didapatkan pembagian alamat IP dari setiap subnet.

![VLSM Tree](/VLSM/img/vlsm-tree.png)

## 3. Hasil VLSM
Berikut hasil akhir dari pembagian alamat IP VLSM yang dimasukkan ke dalam tabel untuk memudahkan proses routing dan penyetelan setiap node.

![VLSM Table](/VLSM/img/vlsm-table.png)

