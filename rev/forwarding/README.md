# Forwarding

## Deskripsi
It can't be that hard... right?

## Flag
```tjctf{just_g3tt1n9_st4rt3d}```

## Solusi 
Hal pertama yang perlu kita lakukan adalah mendownload file yang diberikan setelah itu kita membuka terminal pada linux dan mengetikkan perintah ```Strings``` dan ```Grep```. 

Perintah full nya adalah

```strings d9c4527bc1d5c58c1192f00f2e2ff68f84c345fd2522aeee63a0916897197a7a_forwarding | grep "tjctf"```

Perintah Strings berfungsi membaca file yang ada sementara grep akan mengambil kata yang cocok dengan yang kita inginkan dimana adalah ```tjctf```. Setelah mengetikkan perintah tersebut maka akan muncul flagnya.