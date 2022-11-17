# Proje 1
      [22,27,16,2,18,6] : INSERTION SORT

1.adım: İlk önce dizinin en küçük elemanı belirlenir ve başa yazılır. [2,27,16,22,18,6]

2.adım: İkinci küçük sayı 6, 27 ile yer değiştirir. [2,6,16,22,18,27]

3.adım: Üçüncü en küçük sayı 18 ile 22 yer değiştirir. [2,16,18,22,27] Sıralama doğru hale geldiği için son aşama budur.

     Big O Gösterimi:

Dizide 6 eleman vardır. Sıralama yaparken ilk aşamada 6 tane işlem yapılır. İkinci aşamada 5 tane işlem yapılır. Bu şekilde 1'e kadar ilerlenir.

Toplam yapılan işlemi bulmak için n.(n-1)/2 formülü kullanılır. (n=6)

(n²+n)/2 formülüne ulaşılır. Katsayılar önemsiz olduğu için O(n²) olur.

     Time Complexity (18'e göre)

[2,16,18,22,27] sıralı dizisinde 18 elemanı tam ortada olduğu için Average Case kapsamına girer.

     [7,3,5,8,2,9,4,15,6] : SELECTION SORT
     
1.  [2,3,5,8,7,9,4,15,6]

2.  [2,3,5,8,7,9,4,15,6]

3.  [2,3,4,8,7,9,5,15,6]

4.  [2,3,4,5,7,9,8,15,6]
