# Proje-1
Insertion Sort Project
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

min=2, swap 2 with 22=              [2, | 27,16,22,18,6]
min=6, swap 6 with 27=              [2,6, | 16,22,18,27]
min=16 16 is already in rigth slot= [2,6,16, | 22,18,27]
min=18 swap 18 with 22=             [2,6,16,18, | 22,27]
min=22 18 is already in rigth slot= [2,6,16,18,22,27]

2.Big-O gösterimini yazınız.

There is n# process
         n-1 for 2nd
         n-2 for 3rd
         .
         .
         .
         [n(n+1)]/2 = O(n^2)
         
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. 

Worst Case 

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. 

min=2, swap 2 with 7= [2, | 3,5,8,7,9,4,15,6]
min=3, 3 is already in rigth slot= [2,3 | 5,8,7,9,4,15,6]
min=5, 5 is already in rigth slot= [2,3,5 | 8,7,9,4,15,6]
min=6, swap 6 with 8= [2,3,5,6 | 7,9,4,15,8]
