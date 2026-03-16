# Remote Instance with SSH putty

1. Pastikan sudah install Putty 

![alt text](image.png)

2. Konversi file Public Key dari .pem menjadi .ppk di putty
 - buka puttyGen
 ![alt text](image-1.png)
 - load File .pem
 ![alt text](image-2.png)
 - Save as .ppk
 ![alt text](image-3.png)

3. Set Up Putty untuk Remote SSH
 - buka apps Putty
 ![alt text](image-4.png)
 - Isi IP Public sesuai instance
 ![alt text](image-5.png)
 - isi Port untuk SSH sesuai Security Group di Instance
 ![alt text](image-7.png)
 - isi Nama session agar saat connect lagi tinggal load saja
 ![alt text](image-8.png)
 - load file .ppk (Klik SSH-> Auth -> Credentials ->load file .ppk)
 ![alt text](image-6.png)
 - Kembali ke Session klik Save
 ![alt text](image-10.png)
 - Klik Open
 ![alt text](image-9.png)
 - Masukan username sesuai instance
 ![alt text](image-11.png)

4. "Sudo apt-get Update" (Update OS) lanjut "sudo apt-get Upgrade"
![alt text](image-12.png)

5. Pembuktian Remote SSH secara visual
 - Copy public IP Address instance paste ke Browser
    ![alt text](image-13.png)
 - Install Web Server seperti Apache/Nginx 
 - sudo apt install apache2
 ![alt text](image-14.png)
 - Reload Browser
 ![alt text](image-15.png)

6. Matikan Instance agar tidak kena tagihan
 - sudo shutdown now 
![alt text](image-16.png)