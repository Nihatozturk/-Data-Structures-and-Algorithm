# -Data-Structures-and-Algorithm
Merge Sort : 
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
 
 
1) Merge Sort Adımları :
[16, 21, 11, 8, 12, 22]

Ayırma işlemi
[16, 21, 11]    [8, 12, 22]
[16, 21]  [11]    [8, 12]  [22]
[16]  [21]  [11]    [8]  [12]  [22]

Birleştirme işlemi
[16, 21]  [11]    [8, 12]  [22]
[11, 16, 21]    [8, 12, 22]
[8, 11, 12, 16, 21, 22]

2)Big-O Notation:
O (n*(logn))
