# projeler

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. 

1. Adım [2,27,16,22,18,6]
2. Adım [2,6,16,22,18,27]
3. Adım [2,6,16,18,22,27] son adım

Big-o Gösterimi 0(n^2). Son dizide 18 ortada olduğundan Average Case



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. Adım [2,3,5,8,7,9,4,15,6]
2. Adım [2,3,4,8,7,9,5,15,6]
3. Adım [2,3,4,5,7,9,8,15,6]
4. Adım [2,3,4,5,6,9,8,15,7]
5. Adım [2,3,4,5,6,7,8,15,9]
6. Adım [2,3,4,5,6,7,8,9,15]

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

[16,21,11]    [8,12,22]

[16,21] [11]    [8,12] [22]

[16] [21] [11]  [8] [12] [22] 

[16,21] [11]        [8,12] [22]

[11,16,21]             [8,12,22]

[8,11,1,16,21,22]
Big O --> O(nlogn) olarak değerlendirilir.


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

root = 4

x = 3

y = 6


                                4
                            /       \
                          3          6
                        /          /   \
                       1          5    8
                     /   \           /  \
                    0     2         7    9
