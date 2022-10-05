## NAMA KELOMPOK
## MUHAMMAD HARIS
## 
## 

# Cara Konfigurasi SSH Server dengan Debian
1. Pertama tahap ini silahkan login sebagai user bisa klik su  

2. Kedua Sebelumnya kita akan mengecek kembali, bahwa adapter 1 / eth0 ter bridge ke internet, karena pada saat ini koneksi internet saya menggunakan VirtualBox Host-Only Network #2 , maka disesuaikan dengan adapter nya, oleh karena itu saya menggunakan Intel(R) Wireless-AC 9560 160Mhz 

![adapter](https://user-images.githubusercontent.com/112459285/193231461-10a5eda4-6b36-4182-8734-dedf4c6da21d.png) 

Jika sudah, saat nya kita lakukan konfigurasi IP Address pada Linux Debian, tapi sebelum itu kita akan mengecek berapakah IP Address Internet yang kita dapatkan dari ISP.Untuk mengecek IP Address di windows, saya menggunakan CMD, lalu ketik ipconfig /all ![virtual](https://user-images.githubusercontent.com/112459285/193234601-f1e68ec2-9807-4209-9874-387361af8105.png)

3. ketiga jika sudah, berikutnya kita akan mengkonfigurasi IP Address pada Linux Debian caranya ketikan perintah nano /etc/network/interfaces , crtl+x dan ctrl+s  

![inter](https://user-images.githubusercontent.com/112459285/193235042-9f34d0e4-166e-48a7-904c-b127a507cd5f.png) Jika sudah, silahkan di save dengan cara
ctrl+x lalu y lalu enter
atau cara cepatnya
ctrl+x y enter

4. Keempat ketikan ip a mengecek konfigurasi IP Address yang sudah kita buat 

![4 ssh bjr](https://user-images.githubusercontent.com/74998124/194046219-de1fdc8e-262d-4375-9bf1-483289dd52c5.PNG)

Tahap berikutnya adalah, kita akan menginstall SSH atau openssh-server pada Linux Debian kita, Berikut ini adalah cara nya. 

5. Kelima jalankan ketik apt-get install openssh-server


6. Keenam berikutnya kita akan diperintahkan, untuk memasukkan ISO DEBIAN Paket 1  dengan klik devices > optical disk > iso 
![6 ssh](https://user-images.githubusercontent.com/74998124/194046859-e7b897a2-11f5-461c-8f02-133c97d8f66f.PNG)


7. Ketujuh silahkan tunggu beberapa saat, jika sudah selesai hal yang akan kita lakukan adalah, mengecek status dari SSH Server yang sudah kita install, dengan perintah ketikan /etc/init.d/ssh status

![77ssh](https://user-images.githubusercontent.com/74998124/194047363-745a99d4-5ab5-4bb3-b41a-e12186994216.PNG)



8. buka aplikasi futty masukkan ip 192.168.43.105

![9ssh](https://user-images.githubusercontent.com/74998124/194047642-497b1a68-c475-4feb-ae0f-03663ae4dfba.PNG)

9. dan akan muncul 


![12ssh](https://user-images.githubusercontent.com/74998124/194048071-c32e4e7b-394b-4e11-990d-4ca64fd686ff.PNG)
