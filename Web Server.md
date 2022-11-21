# WEB SERVER 

1. Langkah pertama buka Debian kemudia masuk ke super user dengan command **sudo su atau su** dan masukkan password Linuxnya.
![1](https://user-images.githubusercontent.com/112592881/202994916-bbb22d6d-f9f0-4d49-af3d-498ef4058d9c.PNG)



2. Langkah kedua silahkan install web server dengan mennjalankan command **apt-get install apache2**
![2](https://user-images.githubusercontent.com/112592881/202994961-0e853add-632a-4c64-8a72-b20f266b55e0.PNG)



3. Langkah ketiga jika sudah berhasil silahkan jalankan penginstalan bahasa pemprograman php dengan command **apt-get install php8.1**(php8.1 artinya php versi 8.1) jika gagak coba jalankan command **sudo apt -y install php8.1**
![3](https://user-images.githubusercontent.com/112592881/202995007-d0324017-bbf1-4ab6-8036-1c5619a8b16e.PNG)



4. Langkah keempat selanjutnya konfigurasi, kita bisa melihat hasil dengan mengunjungi web browser dan mengetikkan alamat IP server kita (jalankan command **ip a** untuk melihat IP server) maka akan muncul seperti gambar dibawah ini.
![4](https://user-images.githubusercontent.com/112592881/202995062-72067871-e50d-47f3-ac8e-5acdbc307d3e.PNG)

![127 0 0 1](https://user-images.githubusercontent.com/112459285/198182282-10c652f6-d1fb-4db4-942d-412e5fa2f52c.png)



5. Langkah kelima selanjutnya kita akan menguji menggunakan script php untuk menampilkan info php pada server kita, Kita akan membuat skrip php pada folder **/var/www**  Jalankan command **nano /var/www/html/test/php** atau jika gagal **nano /var/www/test.php**. Setelah itu masukkan skrip seperti gambar dibawah ini 
![5](https://user-images.githubusercontent.com/112592881/202995105-8315b393-a760-4bb1-be0d-4f535a18ab81.PNG)


6. Langkah keenam yaitu yang langkah terakhir selanjutnya buka browser dalam linuxnya lalu ketik (**IP server kalian)/test.php.** Maka akan muncul laman tentang info dari php yang kita install pada server. 
![hasill](https://user-images.githubusercontent.com/112459285/198182948-cf185910-0a2d-48c6-8268-555c0578129e.png)
