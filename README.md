# Patika-Dev---Merge-Sort
Patika Dev - Merge Sort Projesi

1) [16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- [16, 21, 11] -- [8, 12, 22]
- [16, 21]  [11] -- [8, 12] [22]
- [16] [21] [11] -- [8] [12] [22]
- [16, 21]  [11] -- [8, 12] [22]
- [11, 16, 21] -- [8, 12, 22]
- [8, 11,12, 16, 21, 22]

2) Big-O Notation gösterimini yazınız.
Adım 1 -> n
Adım 2 -> n/2
Adım 3 -> n/4
....
Adım (n-1) -> (n-1)/2^(n-2)

Toplam = n + n/2 + ... = n(1 + 1/2 + ...) = nlogn
Big O Notation : O(nlogn)
