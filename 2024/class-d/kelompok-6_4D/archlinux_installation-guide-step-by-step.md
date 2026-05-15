### ini adalah gudie installasi linux berdasarkan pemahaman dan pengalaman langsung penulis Achmad Zanuarta Pattisahusiwa 
#### installasi ini akan mengikuti berdasarkan arch linux wiki https://wiki.archlinux.org/title/Installation_guide, dan sesuai kebutuhan pengguna 
##### konsep arch wiki itu adalah build your own way, jadi arch wiki itu costumizeable dan sesuai dengan jalan dan prinsip dari pengguna dan tergantung dengan keinginan pengguna itu sendiri 
>[!info] step by step yang akan di ikuti: <br>
> [1] mendowload ISO, menentukan UEFI bootloader apakah rufus atau balenaetcher untuk UEFI boot loadernya <br>
> [2] mengecek format UEFI apakah 64 atau 32 UEFI <br>
> [3] mengecek bentuk dari partisi, apakah nvme , sda , atau bentuk lain <br>
> [4] membagi partisi dan membentuk format juga melakukan mount <br>
> [5] koneksi ke internet <br> 
> [6] pacstrap untuk mengambil packages penting untuk berjalannya linux <br> 
> [7] genfstab untuk menentukan partisimana yang akan di mount duluan ketika melakukan boot <br> 
> [8] arch-chroot /mnt dan configurasi juga berbagaimacam penyesuaikan di dalamnya <br> 
>[9]  dari menamai device, menyesuaikan network, bahasa, waktu, pemilihan dekstopenvironment, pembuatan mkinitcpio dan penentuan UEFI boot loader / image loader dan managernya untuk boot linux <br>

 ### mendownload iso dan menentukan live boot UEFI loader
 <img width="1761" height="432" alt="image" src="https://github.com/user-attachments/assets/a1dccf6a-81c8-4aa5-9d0f-6743ada396a1" />

 <img width="1737" height="144" alt="image" src="https://github.com/user-attachments/assets/04e1327c-d10e-454e-b4eb-8c4070320995" />
pertama kalian cari cara untuk download arch linxu kalian dengan masuk ke dalam site https://archlinux.org/download/
kemudian cari mirror untuk arch linux versi terbaru dari ISO nya setelah terinstall maka selanjutnya adalah pemilihan untuk live boot nya 
antara rufus atau balena etcher , saya akan memilih menggunakan balenaetcher karena bentuk dan fungsionalitasnya bisa untuk berbagai macam jenis OS 
