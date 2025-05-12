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
Bisa dilihat bahwa Server berperan sebagai _listener_ dan menerima _connection_ dari tiap Client. Server akan menerima tiap pesan dari berbagai Client, kemudian memberitakan (_broadcast_) pesan yang baru diberikan kepada semua Client. Tiap Client dapat membuat pesannya sendiri dan menerima pesan dari Client lain yang terkoneksi dengan Server.