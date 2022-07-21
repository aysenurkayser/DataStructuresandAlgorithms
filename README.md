# DataStructuresandAlgorithms
This project is the final project of the course named Data Structures and Algorithms given by patika.dev.
# 1. Insertion Sort Projesi

``[22,27,16,2,18,6]`` -> Insertion Sort

*  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.  
*  Big-O gösterimini yazınız.
 ```
 Worst case: O(n^2)
 Average case: O(n^2)
 Best case: O(n)
 ```
*  Time Complexity: Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 ```
 Aranan sayı 2 olsun. 
 
 Best case: [2, 6, 16, 18, 22, 27]
 Worst case: [27, 22, 18, 16, 6, 2]
 ```
*  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 ```
 Dizinin sıralı versiyonu --> [2, 6, 16, 18, 22, 27]
 Bu durumda 18 sayısını ortada kabul edebiliriz. Bu nedenle avarage case kapsamına girer.
 
 
 ``` 
 * ``[7,3,5,8,2,9,4,15,6]``dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 

# 2. Merge Sort Projesi

``[16,21,11,8,12,22]`` -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

```
[16, 21, 11, 8, 12, 22]

[16, 21, 11] || [8, 12, 22]

[16, 21] | [11] || [8,12] | [22]

[16] | [21] | [11] || [8] | [12] | [22] 

[16, 21] | [11] || [8] | [12, 22]

[11, 16, 21] || [8, 12, 22] 

[8, 11, 12, 16, 21, 22 ]


```

```
 Worst case   : O(n*logn)
 Average case : O(n*logn)
 Best case    : O(n*logn)
 ```
 



# 3. Binary Search Tree Projesi

``[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]`` dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

```
Root = 7
```
```
7
```
```
  7
 /
5
```
```
    7
   /
  5
 /
1
```
```
    7
   / \ 
  5   8
 /
1
```
```
    7
   / \ 
  5   8
 /
1
 \ 
  3
```
```
    7
   / \ 
  5   8
 / \
1   6
 \ 
  3
```
```
      7
     / \ 
    5   8
   / \
  1   6
 / \ 
0   3
 

```
```
      7
     / \ 
    5   8
   / \   \
  1   6   9
 / \ 
0   3
 

```
```
      7
     / \ 
    5   8
   / \   \
  1   6   9
 / \ 
0   3
     \ 
      4
```
```
      7
     / \ 
    5   8
   / \   \
  1   6   9
 / \ 
0   3
   / \ 
  2   4
```
www.patika.dev
