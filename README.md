# Tugas-1-Python
Fhujangga I.2310049

import datetime

def hitung_umur():
  nama = input("Masukkan nama kamu: ")
  tahun_lahir = int(input("Masukkan tahun lahir kamu: "))

  tahun_sekarang = datetime.datetime.now().year
  umur = tahun_sekarang - tahun_lahir

  print(f"\nHalo {nama}, umur kamu sekarang {umur} tahun.")

hitung_umur()

