# Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- min=2 -> swap 2 and 22 -> [2, | 27, 16, 22, 18, 6]
- min=6 -> swap 27 and 6 -> [2, 6, | 16, 22, 18, 27]
- min=16 -> no need to swap -> [2, 6, 16, | 22, 18, 27]
- min=18 -> swap 18 and 22 -> [2, 6 16 18 ,22, 27]

2) Big-O gösterimini yazınız.

Step 1 -> n
Step 2 -> n-1
Step 3 -> n-2
....
Step n-1 -> 1

sum = (n*(n-1))/2 -> O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
3) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Worst Case

4) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

- min=2 -> swap 7 and 2 -> [2, | 3, 5, 8, 7, 9, 4, 15, 6]
- min=3 -> no need to swap [2, 3, | 5, 8, 7, 9, 4, 15, 6]
- min=4 -> swap 5 and 4 -> [2, 3, 4, | 8, 7, 9, 5, 15, 6]
- min=5 -> swap 8 and 5 -> [2, 3, 4, 5, | 7, 9, 8, 15, 6]



Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


[16,21,11,8,12,22]
[16,21,11]        [8,12,22]
[16]  [21,11]     [8,12]  [22]
[16] [21] [11]    [8] [12] [22]
[16]  [21,11]     [8,12]  [22]
[16,21,11]        [8,12,22]
       [16,21,11,8,12,22]
       
       
       
Proje 3

Soru ([7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.)

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Bu dizideki root 7'dir.

                                                              5
                                                             / \
                                                            1   7
                                                            
                                                            
                                                                                                                         5
                                                           /   \
                                                          1      7
                                                         / \    / \
                                                        0   3  6   9
                                                        
                                                        
                                                                                                                      5
                                                           /     \
                                                          1        7
                                                         / \      / \
                                                        0   3    6   9
                                                           / \      /
                                                          2   4    8
