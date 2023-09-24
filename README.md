
vize1 = int(input("Birinci vize notunuzu giriniz :"))
vize2 = int(input("İkinci vize notunuzu giriniz :"))
final = int(input("Final notunuzu giriniz :"))

hesap1 = (vize1 * (30/100))
hesap2 = (vize2 * (30/100))
hesap3 = (final * (40/100))

if (hesap1 + hesap2 + hesap3) >= 90:
    print("AA")
elif (hesap1 + hesap2 + hesap3) >= 85:
    print("BA")
elif (hesap1 + hesap2 + hesap3) >= 80:
    print("BB")
elif (hesap1 + hesap2 + hesap3) >= 75:
    print("CB")
elif (hesap1 + hesap2 + hesap3) >= 70:
    print("CC")
elif (hesap1 + hesap2 + hesap3) >= 65:
    print("DC")
elif (hesap1 + hesap2 + hesap3) >= 60:
    print("DD")
elif (hesap1 + hesap2 + hesap3) >= 55:
    print("FD")
elif (hesap1 + hesap2 + hesap3) < 55:
    print("FF")
