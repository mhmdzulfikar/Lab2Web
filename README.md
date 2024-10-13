1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS 
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
![Screenshot 2024-10-08 155009](https://github.com/user-attachments/assets/c76f41b4-7c9c-4d33-92e2-995d3a7dedf8)
![Screenshot 2024-10-08 155035](https://github.com/user-attachments/assets/da62e3a4-b9bc-482c-a6ee-4e1384f961aa)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan 
penjelasannya!

Pendeklarasian h1 {...} berlaku untuk semua elemen <h1> di dalam halaman. Sedangkan #intro h1 {...} hanya berlaku untuk elemen <h1> yang berada di dalam elemen dengan ID intro. Jadi, h1 mengatur semua <h1>, sementara #intro h1 lebih spesifik dan hanya mengatur <h1> dalam elemen dengan ID tertentu

4. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada 
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan 
penjelasan dan contohnya!

![image](https://github.com/user-attachments/assets/b8d228eb-f4ac-4c46-8fe2-e3634fe5aed8)

Jawabannya CSS inline.. inline CSS memiliki prioritas tertinggi. Jika ada konflik antara aturan-aturan ini, browser akan menampilkan gaya dari inline CSS terlebih dahulu, diikuti oleh CSS internal, dan terakhir CSS eksterna

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut 
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? 
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

![image](https://github.com/user-attachments/assets/18ff3128-4301-4b4e-8cfd-d350c512e470)
Jika ada deklarasi CSS untuk ID dan Class yang diterapkan pada elemen HTML yang sama, declaration dari ID akan memiliki prioritas lebih tinggi daripada Class. Artinya, jika terdapat gaya yang bertentangan, gaya dari ID yang akan ditampilkan di browser.
