"""
Nama : Mukmanad Rizqi
Nim  : 17210596
Kelas: 17.1C.12
"""

#Input
Nama        = input("Masukan nama anda                 : ")
Nim         = input("Masukan nim anda                  : ")
Kelas       = input("Masukan kelas anda                : ")
Matakuliah  = input("masukan matakuliah anda           : ")
nilaiabsen  = int(input("masukan nilai absen anda          : "))
nilaitugas1 = int(input("masukan nilai tugas 1 anda        : "))
nilaitugas2 = int(input("masukan nulai tugas 2 anda        : "))
nilaiuts    = int(input("masukan nilai uts anda            : "))
nilaiuas    = int(input("masukan nilai uas anda            : "))

print("<><><><><><><><><><><><><><><><><>")

#Proses
nilaiakhir = nilaiabsen * 0.20 + nilaitugas1 * 0.10 +\
nilaitugas2 * 0.10 + nilaiuts * 0.30 + nilaiuas * 0.30

#Output
print("Nama          :"+str(Nama))
print("Nim           :"+str(Nim))
print("Kelas         :"+str(Kelas))
print("Matakuliah    :"+str(Matakuliah))

if nilaiakhir >= 85:
    print("GRADE A")
    print("SELAMAT ANDA LULUS")

elif nilaiakhir >= 75:
    print("GRADE B")
    print("SELAMAT ANDA LULUS")

elif nilaiakhir >= 65:
    print("GRADE C")
    print("SELAMAT ANDA LULUS")
else:
    print("GRADE D")
    print("ANDA BELUM LULUS")

print("<><><><><><><><><><><><><><><><><>")
print("TOTAL NILAI KESELURUHAN = "+str(nilaiakhir))
