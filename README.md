# odev-01/Çınar Kağan CENGİZ/202607131013
1.01
numbers = [4, 7, 2, 9, 5, 1, 8]
total = 0
result = []

for i in range(len(numbers)):
    if numbers[i] % 2 == 0:
        total = total + numbers[i]
    else:
        result.append(numbers[i])

print(total)
print(result)
i ye 5 total e 7 result a 9 değerleri verdim ama kod çalışmadı hiç bir türlü ve sebebini bilmiyorum.
1.02
-SÖZDE KOD-
current ← 0
longest ← 0
listedeki her okuma için:
    eğer okuma > eşik ise:
        current ← current + 1
        eğer current > longest ise:
            longest ← current
    değilse:
        current ← 0
longest değerini yazdır
-PYHTON KOD-
readings = [18, 21, 23, 25, 24, 26, 27, 19, 20, 22, 23, 24, 25, 26]
threshold = 22

current = 0
longest = 0

for value in readings:
    if value > threshold:
        current = current + 1
        if current > longest:
            longest = current
    else:
        current = 0

print(longest)
1.03
readings = [18, 21, 23, 25, 24, 26, 27, 19, 20, 22, 23, 24, 25, 26]
threshold = 22

current = 0
longest = 0

for value in readings:
    if value > threshold:
        current = current + 1
        if current > longest:
            longest = current
    else:
        current = 0

print(longest)
Aynı öğrenci aynı dersi iki kez yazılmış olsaydı bu kodu onu iki kez sayardı. Bu veride böyle bir kayıt yok ama gerçek veride olabilir.an yaptırıyorum.
-ÖDEV 2-
1-Excel Sorunları ve Veritabanı Çözümleri
Aynı bilgi birçok dosyada tekrar eder ve biri güncellenince diğerleri eski kalır.
2- Birincil Anahtar
Tablodaki her kelimeyi tek tek tanımlar ve böylece iki kayıt asla karışmaz.Öğrenci numaraları gibi isimler aynı olsa her öğrencinin kendine özgü bir öğreni numarası bulunur.
3- DBMS ile Veritabanı
Veritabanı, düzenli biçimde saklanan verinin kendisidir. DBMS ise bu veriyi oluşturup, koruyan yazılımdır.
4- Eşzamanlı Değişiklik
iki kişi aynı anda kaydı değiştirirse son yazanın değişikliği sessizce ezilir.

Bu ödevi Claude Aİ üzerinden yaptım. Pek fazla bilgim olmadığı için doğruda yapamadım yanlış yaptım hepsini ve doğrularını gördüm az çok teşekkürler.
