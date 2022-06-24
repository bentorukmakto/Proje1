https://app.patika.dev/  Veri Yapilari ve Algoritmalar odevi


# Patika.dev Proje 1

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.





# 1. INSORTION SORT

[22,27,16,2,18,6] -> Insertion Sort Yapılacak Işlem

 
[22,|27,16,2,18,6] işlemlerde dizinin 2nci elemanı ile başlanır | işareti takip ediniz. 27--> 22'den büyük olduğu için yer değiştirme olmaz.
[22,16,|27,2,18,6] işleme bir sonraki elemandan devam eder. 27--> 16'dan büyüktür ve yer değiştirir.
[16,22,|27,2,18,6] bir sonraki rakam 22'de 16'dan büyük olduğu için işlem durmaz ve yine yer değistirirler.


[16,22,27,|2,18,6] Bir sonraki siraya geçilir.
[16,22,2,|27,18,6] 27 --> 2 den büyüktür yer değiştirir ve durmaz bir sonraki isleme geçer.
[16,2,22,|27,18,6] 22 --> 2 den büyüktür yer değiştirir ve durmaz bir sonraki isleme geçer.
[2,16,22,|27,18,6] 16 --> 2 den büyüktür yer değiştirir ve işlem biter.


[2,16,22,27,|18,6] 5nci eleman 18'i bir üsteki işlemle aynı şekilde kendinden büyüklerle yer değiştiriyoruz.
     ---------
[2,16,22,18,|27,6] 27 --> 18'den büyük olduğu için yer degistiriyor. 
[2,16,18,22,|27,6] 22 --> 18 den büyük olduğu icin yer değiştiriyor.


[2,16,18,22,|27,|6] 6nci eleman olan 6'yi diger islemlerde oldugu gibi kendinden büyüklerle yer değiştiriyoruz.
     ---------  
[2,16,18,22,6,27] 27 --> 6 dan büyük olduğu icin 
[2,16,18,6,22,27] 22 --> 6 dan büyük oldugu icin
[2,16,6,18,22,27] 18 --> 6 dan büyük oldugu icin
[2,6,16,18,22,27] 16 --> 6 dan büyük oldugu icin


# 2. Big-O Notasyon   O(n^2)

Time Complexity: Best case: Aradığımız sayının dizinin en başında olması. Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması.

Bu durumda 18 ortada olduğu icin " Average case "
