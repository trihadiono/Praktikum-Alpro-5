# Praktikum-Alpro-5
Struktur Kontrol Perulangan
#NAMA: TRI HADIOMO
#NIM: 71200536
#GRUP: D
#UNIVERSITAS KRISTEN DUTA WACANA
#REFERENSI: MODUL

awal=int(input("Saldo awal: "))
sisa=awal
while(True):
    pengeluaran=int(input("Masukkan pengeluaran hari ini: "))
    if pengeluaran==0:
        print("Sisa saldo: ", sisa)
        break
    sisa=sisa-pengeluaran
    if sisa<0:
        print("Saldo tidak cukup")
        print("Sisa saldo: ", sisa+pengeluaran)
