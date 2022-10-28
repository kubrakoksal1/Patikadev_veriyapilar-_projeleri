# Patika.dev'de veri yapıları kursu için yapılan proje
[Patika.Dev](https://www.patika.dev/tr)
# Insertion Sort Projesi
SORU: [22,27,16,2,18,6] -> Insertion Sort
## 1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
```
1-) [22,27,16,2,18,6]
2-) 22|,27,16,2,18,6
3-) 22,27|,16,2,18,6
4-) 22,16,27|,2,18,6
5-) 16,22,27|,2,18,6
6-) 16,22,2,27|,18,6
7-) 16,2,22,27|,18,6
8-) 2,16,22,27|,18,6
9-) 2,16,22,18,27|,6
10-) 2,16,18,22,27|,6
11-) 2,16,18,22,6,27|
12-) 2,16,18,6,22,27|
13-) 2,16,6,18,22,27|
14-) 2,6,16,18,22,27| ->Dizi küçükten büyüğe başarıyla sıralandı.
```
## Big-O gösterimini yazınız.
```
O(N^2)
```
## Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
[2,6,16,18,22,27]=> Sıralanmış dizi

Cevap : Aradığımız sayı başta(Best Case) ve sonda(Worse Case) olmadığından beklenilen durum olarak Average Case'dir.
```
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
7|,3,5,8,2,9,4,15,6
3,7|,5,8,2,9,4,14,6
3,5,7|,8,2,9,4,14,6
3,5,7,8|,2,9,4,14,6 -> 4.adımımız bu şekilde olur
```
# Merge Sort Projesi
SORU: [16,21,11,8,12,22] -> Merge Sort
## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
          -[16,21,11,8,12,22]                  Yapı ikiye bölünür.
 -   [16,21,11]               [8,12,22]        Tekrar bölüyoruz
 -  [16]    [21,11]         [8]    [12,22]     Tek eleman kalması için tekrar bölüyoruz.
 -  [16]   [21] [11]        [8]   [12] [22]    Bu yapıyı tekrar kademeli olarak birleştiriyoruz. Birleştirirken sıralama yapıyoruz.
 -  [16]    [11,21]         [8]    [12,22]     Bu diziyi tekrar sıralı olarak birleştiriyoruz.
 -    [11,16,21]              [8,12,22]        Son birleştirme işlemini gerçekleştiriyoruz.
 -           [8,11,12,16,21,22]
```
 ## Big-O gösterimini yazınız.
```
 O(n.logn)
```
 # Binary Search Tree Projesi
 ## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```
       7
      / \
     5   8
    / \    \
   1   6    9
  / \
 0   3
     / \
    2    4

  ```