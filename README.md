# PERTEMUAN-7-PPT2-LABPY03

# PERTEMUAN 7

---------------------------------------------------
## NAMA: RAFI UBAIDILLAH
## KELAS: TI. 20. A. 1
## NIM: 312010090

--------------------------------------------------
## TUGAS PRAKTIKUM 3

Pada pertemuan 7 di PPT3 ini saya diberikan beberapa tugas diantaranya yaitu:

![uby1](foto/uby1.png)

## LATIHAN 1

Untuk saat ini saya akan mencoba untuk mengerjakan Latihan 1 seperti gambar dibawah ini terlebih dahulu.

![uby2](foto/uby2.png)

untuk mengerjakannya kalian perlu memasukan sytax berikut

````
import random
print(40*"=")
print("Bilangan random yang lebih kecil dari 0,5")
print(40*"=")
jum = int( input("Masukan nilai n : "))
i = 0
for i in range(jum):
    i += 1
    angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
````