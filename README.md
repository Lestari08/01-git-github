# 01-git-github

Langkah-langkah instalasi Git pada windows
1. Mendownlod Git pada website https://www.git-scm.com/


![01](img/images1.png)

2. Jika sudah selesai mendownload, klik setup aplikasi maka akan muncul lisensi dari Git kemudian pilih next


![02](img/images2.jpg)

3. Kemudian akan muncul pilihan untuk menetukan lokasi instalasi, bisa memilih local C atau jika ingin di simpan pada tempat lain bisa pilih browser, lalu pilih next


![03](img/images3.jpg)

4. Kemudian akan muncul komponen tambahan apa saja, bisa di biarkan default saja langsung pilih next


![04](img/images4.png)

5. Selajutnya akan muncul select start menu folder yang di gunakan untuk mengubah nama atau di biarkan seperti default kemudan pilih next


![05](img/images5.jpg)

6. Memilih file editor yang akan digunakan, bisa menggunakan notepad++ seperti pada default atau menggunakan file editor lain seperti visual studio code, kemudian pilih next


![06](img/images6.jpg)

7. Mengatur path environment, pilih git form the command and aslo from 3-rd party software agar cmd dapat mengenali perintah git. kemudian klik next


![07](img/images7.png)

8. Pilih OpenSLL library kemudian pilih next


![08](img/images8.jpg)

9. Memilih line ending, pilih checkout windows-style, commit unix-style line endings, kemudian pilih next


![09](img/images9.jpg)

10. Memilih terminal emulator untuk mengakses ke Git Bash. pilih yang use MinTTY (the default terminal of MSYS2). kemudian pilih next


![10](img/images10.jpeg)

11. Pada mengatur opsi extra pilih enable file system caching dan enable git credential manager. kemudian pilih install


![11](img/images11.jpeg)


12. Setelah itu proses instalasi akan berlangsung. kemudian setelah selesai pilih finsih.


![12](img/images12.jpeg)



Konfigurasi Git


- Pertama-tama buka Git Bash


![10](img/config1.png)

- Kemudian ketikan 

$ git config --global user.name "username di Github"

$ git config --global user.email alamatemail@gmail.com

$ git config --list


![11](img/config.png)



Mengolah repo sendiri


1. pilih tanda + pada pojok kanan atas kemudian pilih new repository


![12](img/repo1.png)


2. Kemudian isikan repository name, untuk description bisa di biarkan kosong kemudian pilih public atau public


![13](img/repo2.png)


3. Kemudian untuk initialize this repository with bisa di biarkan kosong saja kemudian langsung pilih create repsitory


![14](img/repo3.png)


4. Kemudian untuk menambahkan folder, pilih klik kanan kemudian add git bash here


![15](img/repo4.png)


5. Setelah itu ketikan git echo "# 01-git-github" >> README.md


![16](img/repo5.png)




Melakukan push
- klik kanan kemudian pilih git bash here


![15](img/push0.png)

- kemudian ketikan git status untuk mengecek status pada folder


![16](img/push1.png)

- kemudian ketikan git add README.md untuk menambahkan file README.md


![17](img/push2.png)

- setelah itu ketikan git add img (nama folder foto yang digunakan)


![18](img/push3.png)

- selanjutnya ketikan git -m "frist commit"


![19](img/push4.png)

- terakhir ketikan git push


![14](img/push5.png)

- kemudian cek kembali pada akun github akan muncul data tersebut


![15](img/push6.png)


Melakukan clone
- klik kanan pada folder dimana pun yang di inginkan untuk menyimpan file yang akan di clone


![16](img/clone0.png)

- kemudian ketikan git clone dan link dari folder github pada git bash here


![17](img/clone2.png)


![18](img/clone1.png)


- kemdian cek kembali pada local disk atau folder yang akan di gunakan untuk menyimpan

![19](img/clone3.png)

![20](img/clone4.png)