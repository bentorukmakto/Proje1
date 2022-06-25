
#Patika.dev Proje 2 Merge Sort

[16,21,11] | [8,12,22]

[16,21]  [11] | [8] [12,22]

[16]  [21]  [11] | [8]  [12]  [22] Bölme islemi bittiginde bu formatta oluyor.

[16]  [21]  [11] | [8]  [12]  [22] Birlestirme islemi baslangici

[16,21]  [11] | [8,12]  [22] ikişerli halde kücük sayilari büyük sayilarin soluna alarak birlestiriyoruz

[11,16,21]  [8,12,22] Tekrar birlestirme yapılıyor.

[8,11,12,16,21,22] Birleştilirmiş ve sıralanmış son halini aliyor.

#Big O Notasyon : O(n*(logn)

 