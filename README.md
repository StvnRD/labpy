                                      + MENGINSTAL GIT DAN MEMBUAT FOLDER REPOSITORY +

1.	Download software Git melalui website resminya ( git-scm.com ).

    ![gambar](https://user-images.githubusercontent.com/56438848/67144681-25e9af80-f22e-11e9-9e10-062e29b6ded5.png)

2.	Setelah selesai download, install software Git. Pilih Next saja sampai muncul tombol Instal, kemudian klik Instal.

    ![GIT 02](https://user-images.githubusercontent.com/56438848/67144761-58e07300-f22f-11e9-91af-ea76583357fa.PNG)

3.	Proses install selesai, kita lakukan konfigurasi user.name dan user.email dengan perintah :
    gitconfig –global user.name “masukan user name sesuai selera kamu”
    
4.  Setelah itu klik Enter, dan konfigurasi user.email dengan perintah :
    ->  gitconfig –global user.name “masukan gmail kamu”
    
    Akan jadi seperti ini..
    
    ![GIT 1](https://user-images.githubusercontent.com/56438848/67144766-6695f880-f22f-11e9-9fa6-36226b759b47.PNG)

5.  Buka File Explorer, pilih Folder Lab_Pemrograman 1, misal Folder D:\, Klik kanan pada Folder tersebut, Pilih   Git Bash.

      ![Git Bash](https://user-images.githubusercontent.com/56438848/67145698-4a4a8980-f238-11e9-83c5-b4e93b85d7a4.png)

6.  Setelah itu, ketikan perintah ->  mkdir latihan1   , kemudian tekan Enter.
    Dan setelah perintah tersebut di Enter, ketikan perintah selanjutnya  cd latihan1.

    ![05](https://user-images.githubusercontent.com/56438848/67145014-33a13400-f232-11e9-9ba5-f66e31335a08.PNG)

7.  Setelah kedua perintah tersesbut dijalankan, ketikan perintah ->  git init   , dan tekan Enter, kemudian Repository baru berhasil dibuat dengan nama .git (didalam file ini, semua perubahan pada setiap pekerjaan akan tersimpan).

    ![06](https://user-images.githubusercontent.com/56438848/67145036-57fd1080-f232-11e9-8db1-641a61a86e66.PNG)




                                          + MENAMBAHKAN FIE BARU PADA REPOSITORY +

8.  Disini kita akan mencoba membuat File bernama README.md dengan mengetikan perintah berikut .
    ->  echo "Latihan 1" >>README.md

    ![07](https://user-images.githubusercontent.com/56438848/67145089-00ab7000-f233-11e9-8d7b-264b38b541e6.PNG)
    
9.  Setelah mengetikkan perintah diatas, kita akan menambahkan File README.md kedalam GitHub.

     ![08](https://user-images.githubusercontent.com/56438848/67145134-8deec480-f233-11e9-96f0-dc7044f9395e.PNG)
    
10.  Untuk menambah deskripsi pada File README.md, ketikan perintah berikut -> git commit -m "masukan deskripsi" .

    ![09](https://user-images.githubusercontent.com/56438848/67145811-6a2e7d00-f239-11e9-840e-3a85b7e8dbda.PNG)
   
   
   
   
                                             + MEMBUAT REPOSITORY GitHub +

12.  Pastikan Laptop/PC anda sudah terkoneksi ke internet, kemudian buka web browser anda, dan ketikan ->  github.com .

13.  Buat akun terlebih dahulu dengan memilih SignIn

14.  Setelah kamu berhasil membuat akun, Login GitHub, kemudian klik icon ( + ) di sebelah kanan atas, pilih New Repository.

   ![New Repo](https://user-images.githubusercontent.com/56438848/67145306-4c5f1900-f235-11e9-8ed5-3b114ccd4b13.png)

15.  Isi nama Repository nya, misal labpy, lalu yang lain biarkan saja, scroll kebawah dan klik Creater Repository.

   ![New Repo 2](https://user-images.githubusercontent.com/56438848/67145461-ad3b2100-f236-11e9-9403-09ef6120bf91.PNG)

16.  Kemudian buka gitbash yang tadi, kemudian masukkan perintah -> git remote add origin (url GitHub kamu tanpa tanda kurung). Contoh :  $ git remote add origin https://github.com/StvnRD/labpy.git

17.  Setelah itu, ketikan perintah -> git push -u origin master   perintah ini akan meminta anda memasukkan email dan password
     akun GitHub yang tadi anda buat.

18.  Setelah itu, buka GitHub lagi, dan kemudian lihat hasilnya.

   ![12](https://user-images.githubusercontent.com/56438848/67145777-25a2e180-f239-11e9-9829-41e5d64928e1.PNG)

19.  Langkah terakhir yaitu melakukan clone, guna meng-copy Repository server secara otomatis ke Folder Explorer dengan perintah
    ->  git clone (ketikan url GitHub kamu tanpa tanda kurung).


   
