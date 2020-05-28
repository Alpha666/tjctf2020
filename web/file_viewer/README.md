# File Viewer

## Deskripsi
So I've been developing this really cool site where you can read text files! It's still in beta mode, though, so there's only six files you can read.

## Flag
```tjctf{n1c3_j0b_with_lf1_2_rc3}```

## Solusi
Cara untuk mendapatkan flag nya adalah dengan menggunakan ```LFI``` atau biasa di sebut dengan ```Local File Inclusion``` sehingga kita bisa mencari dimana flag tersebut berada. Selain itu juga digunakan ```dirb``` yang digunakan untuk melakukan bruteforce terhadap directory yang ada. Flag nya di encode dalam base64 sehingga untuk mendapatkan flag nya kita perlu melakukan decode terhadap flag nya.