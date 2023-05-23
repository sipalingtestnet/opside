---
layout: '~/layouts/MarkdownLayout.astro'
title: Installation Node
logo: https://mirror-media.imgix.net/publication-images/Hd912XuoV8ekUmD_THtHV.jpeg?h=346&w=346
network: Testnet
chain: pre-alpha-testnet
version: v1.1.1
---

```
Untuk menjalankan opside dengan baik, disarankan memenuhi kebutuhan hardware sebagai berikut:
- Sistem Operasi: 64-bit Linux, Mac OS X 10.14+, Windows 10+ 64-bit
- CPU: 4 core atau lebih dengan kecepatan minimal 2.8 GHz
- Memori: Minimal 16GB
- Penyimpanan: SSD dengan ruang kosong minimal 500GB (kami merekomendasikan 2TB untuk mainnet)
```

###### Step 1 : Membuat Vps 
- Pertama buat vps menggunakan cloud yang biasa teman teman gunakan lalu pilih os **Ubuntu 20**

###### Step 2 : Menjalankan Auto Installer 
- Copy semua command di bawah ini lalu pastekan ke vps kalian
```
wget -c https://pre-alpha-download.opside.network/testnet-auto-install-v2.tar.gz 
tar -C ./ -xzf testnet-auto-install-v2.tar.gz
chmod +x -R ./testnet-auto-install-v2
cd ./testnet-auto-install-v2 
```

###### Step 3 : Menginstall Validator Clients
```
./install-ubuntu-en-1.0.sh
```
- Setelah menginstall anda akan dimintai addres untuk widdraw nantinya
- contohnya **0xBD4607D96707e2Db677DEc672F9EA61Caedf3469**
- Lalu masukan password 8 digit
- Lalu masukan lagi addres 
- Lalu masukan lagi password
- **Setelah itu anda akan di berikan pharse tolong di simpan dengan baik**
- jika sudah maka akan muncul
<a href="https://ibb.co/BzKJTjy"><img src="https://i.ibb.co/w0rqpCS/image.png" alt="image" border="0"></a>
- Yang artinya bahwa penginstalan sudah selesai

###### Step 4 : Sebelum Melakukan Stake Validator Silahkan Cek Block Terlebih Dahulu
```
opside-chain/show-geth-log.sh
```
- Cek disini https://pre-alpha.opside.info/
- Pastikan block pada explorer dan di vps anda sudah benar dengan menggunakan command di atas
-  **Number adalah block**
<a href="https://imgbb.com/"><img src="https://i.ibb.co/q0p2Fdw/image.png" alt="image" border="0"></a>
- Jika sudah sesuai maka teman teman bisa lanjut ke step berikutnya

###### Step 5 : Menjalankan Validator
- Pertama teman teman masuk ke https://opside.network/validator
- Selanjutnya scrool kebawah lalu cari start staking
- Lalu tekan continue sampai ke upload deposit data
<a href="https://ibb.co/R96Qqm9"><img src="https://i.ibb.co/SPmVz8P/image.png" alt="image" border="0"></a>
- Jika sudah sampai seperti gambar di atas teman teman kembali ke vps untuk mengambil file json
- Masuk ke vps lalu lihat di sebelah kiri ada file pilih **testnet-auto-install-v2**
<a href="https://ibb.co/DCC8ntP"><img src="https://i.ibb.co/mqqX7Gr/image.png" alt="image" border="0"></a>
- Lalu masuk kedalam **validator_keys**
<a href="https://imgbb.com/"><img src="https://i.ibb.co/WcVvxvc/image.png" alt="image" border="0"></a>
- Lalu tarik Deposit data ke deskop kalian
<a href="https://imgbb.com/"><img src="https://i.ibb.co/2NV7Nb7/image.png" alt="image" border="0"></a><br />
- Lalu upload file data yang kita ambil dari vps ke 
<a href="https://ibb.co/Km2WFvH"><img src="https://i.ibb.co/4J8pPrx/image.png" alt="image" border="0"></a>
- Lalu centang semua baru tekan continue
<a href="https://ibb.co/9cKT7Ry"><img src="https://i.ibb.co/WG8yLSB/image.png" alt="image" border="0"></a>
- Selanjutnya **connect wallet** lalu tekan confirm deposit baru tekan continue
<a href="https://ibb.co/vDDwKq0"><img src="https://i.ibb.co/d77WzM8/image.png" alt="image" border="0"></a>

###### Step 6 : Selesai 
<a href="https://ibb.co/TTgfYgY"><img src="https://i.ibb.co/sPVfbVb/photo-6298480913390089415-w.jpg" alt="photo-6298480913390089415-w" border="0"></a>
