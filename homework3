
import random as rnd

name=input("Kullanıcı adı giriniz:")
print(f'Welcome {name}')
kelimeler=["kalem","silgi","python","java","bilgisayar","mühendis"]
def word():

  kelime_sec=rnd.choice(kelimeler)
  alınan_kelime=["_"]*len(kelime_sec)
  tahmin=5
  print(alınan_kelime)

  while tahmin > 0:
    harf = 0

    for karakter in kelime_sec:
        if karakter in alınan_kelime:
            print(karakter)
        else:
            print("_")
            harf+= 1

    if harf == 0:
        print("kazandınız")
        break

    ziyaretci = input("lütfen harf girin :")
    alınan_kelime+= ziyaretci

    if ziyaretci not in kelime_sec:
        tahmin -= 1
        print("hatalı !")
        print(f"kalan hakkınız {tahmin} ")

        if tahmin == 0:
            print("canınız kalmadı")

word()
