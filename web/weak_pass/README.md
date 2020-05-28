# Weak Password

## Deskripsi
It seems your login bypass skills are now famous! One of my friends has given you a challenge: figure out his password on this site. He's told me that his username is admin, and that his password is made of up only lowercase letters and numbers. (Wrap the password with tjctf{...})

## Flag
```tjctf{blindsqli14519}```

## Solusi
Pertama, informasi yang kita punya adalah bahwa username nya adalah admin sehingga kita bisa melakukan bruteforce terhadap database dengan cara manual dan cara yang kita gunakan adalah ```blindsql``` dan setelah melakukan bruteforce cukup lama akhirnya kita menemukan passwordnya adalah ```blindsqli14519```.