def faktoriyel(n):
    sonuc = 1
    for i in range(1, n + 1):
        sonuc *= i
    return sonuc

print("5'in faktoriyeli:", faktoriyel(5)
