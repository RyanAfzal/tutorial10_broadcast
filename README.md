# Tutorial 10
Nama : Ryandhika Al Afzal <br>
NPM : 2206081502 <br>
Kelas : Adpro A <br>

### Refleksi

###### 2.1. Original code of broadcast chat.
server side <br>
![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/2e764a3d-7be9-413d-9dae-c1e0d5e618f9)<br>

1st client side <br>
![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/c8944b5f-a33d-4d75-9f07-0b25d192cad9) <br>

2nd client side <br>
![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/7928b4b3-8ac7-4280-b39e-c32715823c82) <br>

3rd client side <br>
![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/e00d4100-8c43-4a88-9385-f3b9f69499b3) <br>

Setelah menjalankan server dengan ```cargo run --bin server``` dan menjalankan client sebanyak client yang ada (ada 3) dengan ```cargo run --bin client``` dapat dilihat bahwa pesan yang dikirimkan dari sisi client akan dikirim ke server dan server mengirimkannya ke semua client yang terhubung ke server itu.

###### 2.2. Modifying the websocket port.
![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/45ff7318-9d9b-4d8c-a5a9-cfc8598ebc66) <br>

![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/2ceea830-811e-428c-b837-c8dc98c9b4cf) <br>
ketika client dan server menggunakan port yang sama dalam hal ini adalah port 8080, seperti gambar di atas program akan berjalan dengan lancar seperti sebelumnya. <br>


![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/1294770b-bbd8-4c51-8039-3b6f04d07a1e) <br>

![image](https://github.com/RyanAfzal/tutorial10_broadcast/assets/137851158/cb4bbe3e-3d7c-4bb6-b25a-cab83a7de9e2) <br>
Ketika client dan server menggunakan port yang berbeda dalam hal ini server pada port 8080 dan client pada port 2000 maka akan terjadi error pada client karena menurut client port tersebut tidak memiliki koneksi dan program akan crash saat dijalankan seperti yang tertera pada gambar di atas.

