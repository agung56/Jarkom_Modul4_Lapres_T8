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
Atur IP pada interface **SURABAYA** yang mengarah ke **PASURUAN**<br>
