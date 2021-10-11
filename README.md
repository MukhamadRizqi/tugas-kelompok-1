nim = input("Masukan nim: ")
nama = input("Masukan nama: ")
kelas = input("Masukan kelas: ")
Matakuliah = input("Masukan matakuliah: ")
nilaiabsen = int(input("Masukan nilai absen : "))
nilaitugas1 = int(input("Masukan nilai tugas 1 : "))
nilaitugas2 = int(input("Masukan nilai tugas 2 : "))
nilaiuts = int(input("Masukan nilai uts : "))
nilaiuas = int(input("Masukan nilai uas : "))
nilai=("nilaiabsen : ")+("nilaitugas1 : ")+("nilaitugas2 : ")+("nilaiuts : ")+("nilaiuas : ")

print("nim :" +(nim))
print("nama :" +(nama))
print("kelas :" +(kelas))
print("Matakuliah :" +(Matakuliah))
print("nilai absen :" +str(float(1/20))+'%')
print("nilai tugas 1 :" +str(float(1/10))+'%')
print("nilai tugas 2 :" +str(float(1/10))+'%')
print("nilai uts : " +str(float(1/30))+'%')
print("nilai uas : " +str(float(1/30))+'%')


nilai = int(input("Masukan nilai anda :"))

if(nilai>=80):
    print("Grade A")
    print("Selamat Anda LULUS")
elif(nilai>=70):
    print("Grade B")
    print("Selamat Anda LULUS")
elif(nilai>=60):
    print("Grade C")
    print("Anda Belum LULUS")
else:
    print("Grade D")
    print("Nilai Anda Jelek") 
