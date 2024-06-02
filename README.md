Praktikum Jaringan Komputer

Nama : Hafizhan awadh
NIM : 09030582226039

Kelas : TK4A

Pengertian SWITCH:

Switch merupakan perangkat jaringan yang bekerja pada OSI Layer 2, Data Link Layer. dia bekerja sebagai penyambung / concentrator dalam Jaringan. Switch mengenal MAC Adressing shingga bisa memilah paket data mana yang akan di teruskan ke mana. Dan switch ini digunakan sebagai repeater/penguat. Berfungsi untuk menghubungkan kabel- kabel UTP ( Kategori 5/5e ) komputer yang satu dengan komputer yang lain. Dalam switch biasanya terdapat routing, routing sendiri berfungsi untuk batu loncat untuk melakukan koneksi dengan komputer lain dalam LAN.

Cara Kerja Switch yaitu menerima dan menganalisa seluruh isi paket sebelum meneruskannya ke tujuan. Switch memeriksa satu persatu paket untuk mengetahui adanya kerusakan pada paket tersebut dan mencegahnya agar tidak mengganggu jaringan. Switch mengalokasikan bandwidth secara penuh untuk setiap portnya. Komputer pengguna akan selalu memiliki bandwidth secara penuh seberapapun komputer yang ada. Switch bekerja di lapisan Data Link dan Setiap port didalam swith memiliki domain collision sendiri- sendiri. Switch melakukan transmisi secara 2 arah (Full duplex).

Alat dan Bahan yang diperlukan dalam praktikum Jaringan Komputer ini adalah :

Sebuah PC atau Laptop
Software Jaringan ‘Cisco Packet Tracer’
Langkah - Langkah :

Persiapkan 2 buah PC dan 1 buah Switch.

Pasang kabel penghubung antara PC 0 ke Switch dan PC 1 ke Switch.
<img width="698" alt="312703176-3414e261-732e-4eec-a3a4-698a4290a280" src="https://github.com/09030582226039/Switching/assets/126418106/e95a5f45-96b9-403c-a550-b52533cb840d">
<img width="706" alt="312703381-ca084ba7-af08-479d-a59e-19cac8dd040f" src="https://github.com/09030582226039/Switching/assets/126418106/7ab35ae6-0e1f-4b5f-94cc-45573f8091bd">

Double click pada PC 0 sehingga muncul jendela baru, seperti berikut

Click pada tab Desktop sehingga muncul tampilan sebagai berikut.

<img width="726" alt="312703656-74935a66-e03f-48f8-ba42-12a2051c337a" src="https://github.com/09030582226039/Switching/assets/126418106/7a1107be-2aa5-45f8-8138-2247e57f6054">

Click pada tab IP Configuration, untuk mengatur alamat IP pada PC 0.

<img width="730" alt="312703792-a0df3509-296c-4c76-af80-61179ddf9bab" src="https://github.com/09030582226039/Switching/assets/126418106/1f89e18e-9798-4fb1-90d8-06c6a2b87cb9">

Isikan Alamat IP dan Subnet Mask pada PC 0 dengan alamat seperti dibawah ini dan kosongkan kolom Default Gateaway dan DNS server.

<img width="493" alt="312706334-47725c3a-522e-41ec-bcfd-9d859b5c4899" src="https://github.com/09030582226039/Switching/assets/126418106/76810bce-5cd0-4461-a86c-bb18f3559885">

Lakukan hal serupa pada PC 1 tetapi dengan konfigurasi alamat IP yang berbeda dengan PC 0, tetapi Subnet Mask nya biarkan sama. Selain itu tetap kosongkan kolom Default Gateaway dan DNS server.

<img width="822" alt="312706495-fe7cd784-4efa-43b9-9972-a6adb7c6f9d2" src="https://github.com/09030582226039/Switching/assets/126418106/470652dc-9607-46fb-a0df-8890b7587cea">

Setelah mengkonfigurasi IP maka 3 buah device tersebut akan saling terhubung ditandai dengan dot / node yang berwarna hijau.

<img width="831" alt="312706651-c14fd027-e0f2-45ab-b316-13c49d6d9ae0" src="https://github.com/09030582226039/Switching/assets/126418106/24806e43-4151-45b4-a03c-86eea86691ce">

Untuk melakukan testing pada jaringan tersebut, kita dapat melakukan “ping”

Caranya dengan double clik salah satu dari dua PC (antara PC 0 atau PC 1) dan clik pada tab Desktop.

Kemudian pilih tab Command Prompt dan akan muncul jendela seperti di bawah ini.

<img width="1169" alt="312706892-f01f65d2-7455-432f-b66f-97690bdf4a0d" src="https://github.com/09030582226039/Switching/assets/126418106/2381034e-5ddb-4b4d-a169-6a787eb8c937">

Kemudian ketik “PING (alamat IP tujuan) “ ; Contoh nya adalah ‘PING 192.168.123.2’ maka jaringan kita telah terhubung, akan jadi seperti di bawah ini

<img width="807" alt="312707158-72b1f90d-437f-4148-9b11-855a1743d14b" src="https://github.com/09030582226039/Switching/assets/126418106/35174be4-16fb-422d-9d82-e90176b00f53">


Selesai










