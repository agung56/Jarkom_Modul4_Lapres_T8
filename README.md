# Jarkom_Modul4_Lapres_T8
## Anggota Kelompok:
1. Kadek Nesya Kurniadewi (05311840000009)
2. Agung Mulyono (05311840000035)

### Topologi Jaringan
![1](./img/Soal%20Shift%20Modul%204.png)

### Metode VLSM
**Langkah-langkah:**
+ Pertama membuat topologi seperti pada gambar diatas pada Cisco Packet Tracer (CPT)
+ Kemudian tambahkan port **NM-2FE2W** pada semua router kecuali **SURABAYA**. untuk router **SURABAYA** tambahkan port **NM-4E**
+ Sambungkan kabel pada tiap device
+ Lalu kelompokkan device menggunakan metode **VLSM**<br>
![2](./img/VLSM.png)
+ Setelah dikelompokkan, hitung jumlah total client yang dibutuhkan dan berdasarkan jumlah tersebut tentukan subnet yang diperlukan <br>
![3](./img/Pembagian%20IP%20router%20dan%20client.png)
**Khusus untuk pembagian IP Pada Server menggunakan IP DMZ**
![4](./img/Pembagian%20IP%20Server.png)
+ Atur IP untuk masing-masing interface yang ada di setiap device sesuai dengan pembagian subnet pada VLSM. Interface dapat diatur pada menu Config -> Interface > “nama interface” (contoh: FastEthernet0/0). Kemudian, isi alamat IP dan subnet mask dari subnet interface tersebut. Berikut contoh untuk mengatur IP pada subnet A8.
+ Atur IP pada interface **SURABAYA** yang mengarah ke **PASURUAN** dengan **192.168.0.13**<br>
![5](./img/SURABAYA.png)
+ Atur IP pada interface **PASURUAN** yang mengarah ke **SURABAYA** dengan **192.168.0.14**<br>
![6](./img/PASURUAN1.png)
+ Atur IP pada subnet A8. Atur IP pada interface **PASURUAN** yang mengarah ke *client* dengan **192.168.12.1**<br>
![7](./img/PASURUAN2.png)
+ Kemudian atur IP pada *client*<br>
![8](./img/SIDOARJO.png)
`Catatan: Lakukan hal yang sama pada setiap device`
+ Lakukan routing agar semua device dapat terhubung
+ Routing pada **SURABAYA** yang mengarah ke subnet A8<br>
![9]()
+ Routing pada **PASURUAN** yang mengarah ke **SURABAYA**<br>
![10]()
+ Berikut adalah IP yang diperlukan pada device-device tertentu
  + Pada SURABAYA
    ```
    Network 192.168.12.0 Netmask 255.255.252.0 Next Hop 192.168.0.14
    ```
  + Pada PASURUAN
    ```
    ```
  + Pada BATU
    ```
    ```
  + Pada KEDIRI
    ```
    ```
