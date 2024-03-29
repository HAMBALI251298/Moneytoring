## Hi, I'm HAMBALI 👋
<img src="hambali.png">

## APLIKASI INI DIBUAT OLEH HAMBALI


# Moneytoring
## Aplikasi Pencatatan Transaksi e-wallet atau mobile banking otomatis melalui Notifikasi

## Preview (MockUp)

![money toring (1)](https://user-images.githubusercontent.com/43540712/206912989-e32d1eaf-a62e-4812-9d50-a273736cd38f.png)


## Support Notification
Untuk saat ini Aplikasi Moneytoring masih sangat terbatas, sehingga hanya support pada beberapa notifikasi Aplikasi saja, diantaranya :
- BSI to OVO
- BRI to OVO
- OVO to BRI
- OVO to OVO 
- BRI to DANA
- PERMATA BANK to DANA
- BRI to BRIVA

## HAMBALI

| Channels (HAMBALI)              | Mantra (Snap)                       | Xendit (ewallet/XenInvoice) |
| ------------------------------- | ----------------------------------- | --------------------------- |
| JENIUS VA <img src="logo-jenius.png"> | :white_check_mark:                  | :white_check_mark:          |
| JAGO VA <img src="logo-jago.png">   | :white_check_mark:                  | :x:                         |
| BCA VA    <img src="logo-bca.png">                      | :white_check_mark:                  | :white_check_mark:          |
| Mandiri VA    <img src="logo-mandiri.png">                  | :white_check_mark:                  | :white_check_mark:          |
| BNI VA     <img src="logo-bni.png">                     | :white_check_mark:                  | :white_check_mark:          |
| bsi VA   <img src="logo-bsi.png">                   | :white_check_mark:                  | :white_check_mark:          |
| Other VA                        | :white_check_mark:                  | :x:                         |
| BRI VA     <img src="logo-bri.png">                     | :heavy_exclamation_mark:            | :white_check_mark:          |
| MUAMALAT VA <img src="logo-muamalat.png">    | :white_check_mark:                  | :white_check_mark:          |
| SEABANK VA <img src="logo-seabank.png">                       | :white_check_mark:                  | :white_check_mark:          |
| Gopay  VA   <img src="logo-gopay.png">                      | :white_check_mark:                  | :x:                         |
| OVO VA       <img src="logo-ovo.png">                     | :x:                                 | :white_check_mark:          |
| DANA  VA    <img src="logo-dana.png">                      | :x:                                 | :white_check_mark:          |
| LINKAJA VA  <img src="logo-linkaja.png">                     | :x:                                 | :white_check_mark:          |
| DANAMON VA   <img src="logo-danamon.png">                   | :white_check_mark:                  | :white_check_mark:          |
| CIMB NIAGA VA <img src="logo-cimb-niaga.png">                        | :white_check_mark:                  | :x:                         |
| BTN VA <img src="logo-btn.png">                     | :x:                                 | :heavy_exclamation_mark:    |
| OCBC NISP VA <img src="logo-ocbc-nisp.png">

# Feature 
Kami dengan senang hati dan selalu mengedepankan kenyamanan user untuk itu kami sediakan fitur-fitur pada Aplikasi Moneytoring sebagai berikut :
- Automatic Grab Notification 
  <br><i>Data otomatis tersimpan ke aplikasi ketika ada notifikasi transaksi di berbagai Aplikasi yang telah disebutkan di atas.</i>
  <br><i>Kami mengedepankan privasi user sehingga ingin kami sampaikan, bahwa Aplikasi Moneytoring hanya mencatat notifikasi berupa transaksi, kami tidak menyimpan data yang bersifat probadi atau bahkan merugikan user.</i>
- Manual Input 
  <br><i>Anda tidak mengizinkan notifikasi? tenang, aplikasi Moneytoring masih dapat input data secara manual.</i>
- Show total Pengeluaran
- Show total Pemasukan
- Show all transaksi 
- Show all transaksi with filter
- Use as guest with best fitur

## How its Work
Auto save transaksi ketika Aplikasi Moneytoring ditutup/close akan tetap bekerja, namun dengan ketentuan close/clear aplikasi by _swipe_ karena jika by _clear all button_ transaksi tersimpan otomatis tidak akan bekerja, anda dapat mengaktifkan ulang service auto save transaksi jika anda ingin terus dapat menyimpan transaksi secara Automatic.<br><br>
![how its work](https://user-images.githubusercontent.com/43540712/208590263-135a2db0-3b62-4bba-bd56-e801ab0a9419.png)



## Dataset

Dataset disini yang dimaksud adalah sekumpulan data notifikasi transaksi pada aplikasi-aplikasi seperti m-banking, e-money, maupun, aplikasi dengan sistem pembayaran lainnya.

```
OVO - IN : 
Top up sebesar Rp100.000 melalui BANK BRI, telah berhasil
Top up Rp 10.000 dari BSI - TOP UP telah berhasil
Top up sebesar Rp20.000 melalui BANK BRI, telah berhasil
Loremipsum mengirimkan dana sebesar Rp 10.000 melalui aplikasi OVO

OVO - OUT :
Transfer Rp100.000.00 ke HAXIM berhasil. Kamu dikenakan biaya transaksi Rp5.000
Rp1.000 telah dipotong dari OVO Cash untuk biaya top up dari BANK BRI
Rp 1.500 telah dipotong dari OVO Cash untuk biaya top up dari BSI - TOP UP


BRI - OUT : 
08/12/2022 11:23:48 - Transaksi Top Up OVO 08999999999 sebesar Rp20.000,00 BERHASIL. Info lebih lanjut hubungi Call Center BRI 14017

DANA - IN :
Berhasil top up saldo Rp20.000 dari BRI BANK RAKYAT INDONESIA. Lihat detailnya di sini!
Berhasil top up saldo Rp 10.000 dari PERMATA BANK. Lihat detailnya di sini!

GOPAY - IN
Top up saldo sebesar Rp10.000 via ATM Bersama Permata berhasil.

SHOPEE - IN
Isi saldo
GSJGDJHGSJDGJSDGSDJGHSJ sebesar Rp10.000 telah ditambahkan ke
ShopeePay-mu. Saldo saat ini Rp140.329

Paypal - IN
Paypal.co.Ltd telah mengirimkan anda $1000

```

## Resource 
- Database 
  * Room Database
- Bahasa 
  * Kotlin
- Other 
  * https://developer.android.com/reference/kotlin/android/service/notification/NotificationListenerService#NotificationListenerService()
  * https://developer.android.com/jetpack/androidx/releases/room
  * https://facebook.github.io/shimmer-android/
  * https://github.com/bumptech/glide

## Contribution

Kami persilahkan siapa saja untuk kontribusi dalam penambahan dataset notifikasi, tujuannya agar aplikasi kami semakin berkembang dan lebih baik lagi. <br>
kemudian bagaimana cara kontribusinya? anda dapat melakukan submit pada google form ini
https://forms.gle/d5xbGkECTyWEBJG19
<br>Thanks!

## License
```
Copyright (C) C22 - 163 / besthora

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

```
