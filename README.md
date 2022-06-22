# Veri-Yapilari-ve-Algoritmalar-Proje1
patika.dev Veri Yapıları ve Algoritmalar Proje 1

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

<img width="414" alt="Merge sort" src="https://user-images.githubusercontent.com/75563269/175070299-69e3fa78-0742-46dc-b35d-0308217a2e10.png">


I. [2,27,16,22,18,6] Verilen örüntüde en küçük sayı ile yer değiştirdik. (2 ve 22)
II. [2,6,16,22,18,27] İkinci en küçük sayı bulunup, yer değiştirildi. (6 ve 27)
III. [2,6,16,18,22,27] 22 ve 18 yer değiştirdik. Görüldüğü üzere sayılar büyükten küçüğe sıralandı ve işlem tamamlandı.
IV. [2,6,16,18,22,27] beşinci sayı doğru yerde. Dokunma devam et.
V. [2,6,16,18,22,27] altıncı sayı en büyük. Dokunma devam et.

2. Big-O gösterimini yazınız.

O(n²) = O(6²) = O(36)

3. Time Complexity

Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

Cevap 4: Average case (Aradığımız sayının ortada olması)

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

I. [2,3,5,8,7,9,4,15,6] 2 ve 7 sayıları yer değiştiriyor.
II. [2,3,5,8,7,9,4,15,6] 2,3 sayıları doğru yerde, dokunma devam et.
III. [2,3,4,8,7,9,5,15,6] 4 ve 5 sayıları yer değiştiriyor.
IV. [2,3,4,5,7,9,8,15,6] 8 ve 5 sayıları yer değiştiriyor. ilk 4 adım tamamlandı.
