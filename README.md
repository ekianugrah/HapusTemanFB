# HapusTemanFB
Menghapus teman facebook yang sudah tidak aktif.

Delete Non Aktif User Facebook

Recode by Eki Anugrah Ramadhan

## Alat Yang Diperlukan
      - Aplikasi Browser (saya sarankan pake VIA Browser,biar garibet nyari AccessTokennya)
      - Link untuk mengambil AccessToken (https://mobile.facebook.com/composer/ocelot/async_loader/?publisher=feed)

## Pemasangan
      $ pkg install php
      $ git clone https://github.com/ekianugrah/HapusTemanFB.git
      $ cd HapusTemanFB

## Jalankan
      $ php nonaktifuser.php

## Perbarui
      $ git pull --force

## Penjelasan :
- Memasukan :
    - Facebook token `Contoh Token Facebook (EAAAAA...)`
    - Tahun `Misalnya: 2017, batalkan pertemanan pengguna di mana tidak memperbarui status sebelum 2017`
