# Sorting Algoritmaları 
[patika.dev](https://app.patika.dev/paths)

## Proje 1 Insertion Sort

[22,27,16,2,18,6]

Searching 

1)Verilen örüntüye ait en küçük elamanı bulur en baştaki ile yer değiştirir.
2)2. en küçük elamanı bulur 2. sıraya yerleştirir 
3) 3.en küçün elamanı bulur 3. sıraya yerleştirir
4) 4.en küçün elamanı bulur 4. sıraya yerleştirir

n + (n-1) + (n-2 ) + .... +1   O(n^2)


Dizide 18 sayısını aramak worst case kapsamına girer çünkü böyle bir sayı yoktur.

## Proje 2 Merge Sort

[16,21,11,8,12,22]

1) [16,21,11] [8,12,22]
2) [16] [21,11]    [8] [12,22]
3) [16] [21] [11]  [8] [12] [22] 
4 [11,16,21]  [8,12,22]
5 [8,11,12,16,21,22]

O(nlogn)