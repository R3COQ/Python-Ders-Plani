# Ders 1 – Algoritma ve İlk Python Programı
## 🧩 Algoritma Nedir?
- Algoritma: **Bir problemi çözmek için adım adım talimat listesi**.  
- Çay demleme örneği (6 adım).

## 🐍 İlk Python Programı
```python
print("Merhaba Dünya")
```

## 🔑 Değişkenler
```python
isim = "Recep"
yas = 20
print("Benim adım", isim)
print("Yaşım", yas)
```

## 🔎 Kullanıcıdan Veri Alma
```python
isim = input("Adın nedir? ")
yas = input("Yaşın kaç? ")
print("Merhaba", isim, "sen", yas, "yaşındasın.")
```

## ✅ Ödev
- Konsola kendi adını ve yaşını yazdır.
- Kullanıcıdan isim + yaş alıp yazdır.

---

# Ders 2 – Değişkenler ve Veri Tipleri
## 🔢 Veri Tipleri
- `int`, `float`, `str`, `bool`
- `type()` fonksiyonu

## 🔡 String İşlemleri
```python
isim = "Ali"
print(len(isim))       # uzunluk
print(isim.upper())    # büyük harf
print(isim.lower())    # küçük harf
print(isim + " Can")   # birleştirme
```

## ✅ Ödev
- Kullanıcıdan isim ve yaş al, ekrana yazdır.
- İsim uzunluğunu ekrana yaz.

---

# Ders 3 – Operatörler ve Koşullar
## ➕ Operatörler
- Matematiksel: + - * / // % **
- Karşılaştırma: == != < > <= >=
- Mantıksal: and, or, not

## 🔀 Koşul Yapısı
```python
yas = 18
if yas >= 18:
    print("Reşitsin")
else:
    print("Çocuk sayılırsın")
```

## ✅ Ödev
- Not ortalaması 50’den büyükse “Geçtin”, küçükse “Kaldın” yazan program.

---

# Ders 4 – Döngüler
## 🔁 For Döngüsü
```python
for i in range(1, 6):
    print("Merhaba", i)
```

## 🔁 While Döngüsü
```python
sayi = 1
while sayi <= 5:
    print(sayi)
    sayi += 1
```

## 🚪 break ve continue
```python
for i in range(10):
    if i == 5:
        break
```

## ✅ Ödev
- 1’den 100’e kadar sayıların toplamını bulan program.

---

# Ders 5 – Fonksiyonlar
## 🛠 Fonksiyon Tanımlama
```python
def selamla(isim):
    print("Merhaba", isim)
```

## 🔙 Return Kullanımı
```python
def kare(sayi):
    return sayi * sayi
```

## ✅ Ödev
- Bir fonksiyon → sayının karesini döndürsün.
- Bir fonksiyon → 2 sayının ortalamasını döndürsün.

---

# Ders 6 – Mini Proje
## 📝 Küçük Projeler
1. Kullanıcıdan notlar al → ortalama hesapla.  
2. Basit hesap makinesi (toplama, çıkarma, çarpma, bölme).  
3. Taş-Kağıt-Makas oyunu.

## ✅ Ödev
- Kendi seçtiği basit bir oyunu veya uygulamayı yazsın.

---

