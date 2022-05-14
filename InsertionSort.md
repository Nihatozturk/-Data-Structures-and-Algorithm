# -Data-Structures-and-Algorithm
Proje 1 
Insertion Sort :
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Cevap:
 Insertion Sort: 
 [22,27,16,2,18,6]  
 [2,27,16,22,18,6]
 [2,6,16,22,18,27]
 [2,6,16,18,22,27]
 [2,6,16,18,22,27]
 [2,6,16,18,22,27]
 
 Big-O Notation:
 İlk olarak n işlem, ardından n-1 işlem, en son ise 1 işlem yapılmış olacak. Bu yüzden Big-O 1 den n'e kadar olan sayıların toplamı oluyor.                 
 Diğer bir deyişle (n * (n+1)) / 2 = (n^2 + n) / 2 

O(n^2)  
Time Complexity:

Best Case: O(n)   (Best case: Aradığımız sayının dizinin en başında olması demektir)  n
Worst Case: O(n^2) (Worst case: Aradığımız sayının sonda olması demektir)  n^2
Average Case: O(n^2) (Average case: Aradığımız sayının ortada olması demektir)  n^2

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? :
Average Case
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. :

[3,7,5,8,2,9,4,15,6] 
[3,5,7,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[2,3,5,7,8,9,4,15,6]

