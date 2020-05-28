# Login Sequel

## Deskripsi
Login as admin you must. This time, the client is of no use :(. What to do?

## Flag
```tjctf{W0w_wHa1_a_SqL1_exPeRt!}```

## Solusi
Pertama kita perlu melakukan inspect element terhadap web nya dan kita mendapat info bahwa ```username``` dan ```password``` nya menggunakan ```username=\'%s\' AND password=\'%s\'``` dan kita tinggal memasukkan sql injection username berupa ```admin'/*``` dan untuk password bisa di isi dengan bebas.