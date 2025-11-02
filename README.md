# Tugas P6 
# labpy02
# Latihan 1
#Masukan input 
bil150 = int (input("Masukan bilangan : "))
bil250 = int (input("Masukan bilangan : "))
bil350 = int (input("Masukan bilangan : "))
bil450 = int (input("Masukan bilangan : "))

#Nilai terbesar

if (bil450 > bil150):
   print("Bilangan terbesar :",bil450)

#Nilai terkecil

if (bil150 < bil250):
   print("Bilangan terkecil :",bil150)


# Latihan 2
#Masukan inputan
bil150 = int(input("Bilangan ke-1: "))
bil250 = int(input("Bilangan ke-2: "))
bil350 = int(input("Bilangan ke-3: "))

#Buat variable data
data = [bil350, bil150, bil250]

#Menampilkan data
print("Data sebelum di urutkan :", data)
list.sort(data)
print("Data setelah di urutkan :", data)


# Latihan 3
baris = 10
kolom = baris

for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()


# Latihan 4
import random
print("===========================================")
print("= Bilangan acak yang lebih kecil dari 0,5 =")
print("===========================================")
jum = int(input("Masukan nilai: "))
for i in range(1, jum + 1):
    angkarandom = random.uniform(0, 0.5)
    print("Bilangan ke :", i, " : ", angkarandom)
