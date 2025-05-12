# Advanced Programming - Module 10 Broadcast
**Nama:**   &nbsp; Stefanus Tan Jaya<br>
**NPM:**    &nbsp;&ensp; 2306152456<br>
**Kelas:**  &nbsp; Pemrograman Lanjut A<br>

### 2.1 Original code and How It Runs
#### Client 1 View
![Client 1](client1.png)
#### Client 2 View
![Client 2](client2.png)
#### Client 3 View
![Client 3](client3.png)
#### Server View
![Server](server.png)
<br><br>
Bisa dilihat bahwa Server berperan sebagai _listener_ dan menerima _connection_ dari tiap Client. Server akan menerima tiap pesan dari berbagai Client, kemudian memberitakan (_broadcast_) pesan yang baru diberikan kepada semua Client. Tiap Client dapat membuat pesannya sendiri dan menerima pesan dari Client lain yang terkoneksi dengan Server.

### 2.2 Modifying the Websocket Port
#### Client 1 View at 8080
![Client 1](client1-8080.png)
#### Client 2 View at 8080
![Client 2](client2-8080.png)
#### Client 3 View at 8080
![Client 3](client3-8080.png)
#### Server Port 8080
![Server](server8080.png)
<br><br>
Jika port Server dan Client diganti dengan port yang sama, maka aplikasi tetap berjalan normal. Namun, bila salah satu port diganti menjadi yang berbeda dengan satu sama lain, akan muncul error karena Client tidak menemukan target Server dengan port yang sesuai. Tampak errornya sebagai berikut.
![Error](errorport.png)