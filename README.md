# Veri Yapısı Ve Algoritmalar Proje
---
Kodluyoruz bünyesinde Veri Yapısı Ve Algoritmalar Proje dersi kapsamında hazırlanan projedir.

## Insertion Sort Projesi 1

### Soru 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-[22,27,16,2,18,6]
2-[2,27,16,22,18,6]
3-[2,6,16,22,18,27]
4-[2,6,16,18,22,27] 

2. Big-O gösterimini yazınız.

![Big-O analitik düzlem resim](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/veri-yapilari-algoritmalar/big-o/figures/big-o-grafik.png)

Mevcut dizinin worst case senaryosuna göre Big-O analiz gösterimi O(n^2)'dir. Ancak avarage case'e göre Big-O analiz gösterimi o(n)'dir.

3. Time Complexity: 

Best case   : 1 dir.
Average case: n/2 işlemdir.
Worst case  : n^2 adet işlemdir. 

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Sayı dizi sıralamasında ortada yer aldığından average case kapsamındadır.

### Soru 2

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

  [7,3,5,8,2,9,4,15,6]
1-[2,3,5,8,7,9,4,15,6]
2-[2,3,4,8,7,9,5,15,6]
3-[2,3,4,5,7,9,8,15,6]
4-[2,3,4,5,6,9,8,15,7]



