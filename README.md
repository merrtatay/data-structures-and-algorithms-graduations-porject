# data structures and algorithms graduations-porject
[22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2- Big-O gösterimini yazınız.
3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[22,27,16,2,18,6]
first pass:
in first to element, 27 greater than 22 there is no problem.
second pass:
second and third element, 16 is not grater than 27.
thus swap 16 and 27.
[22,16,27,2,18,6]
third pass:
after swapping, 16 is not greater than 22,thus swap again.
[16,22,27,2,18,6]
it is the method, i will show the steps not explain.
[16,22,2,27,18,6]
[16,2,22,27,18,6]
[2,16,22,27,18,6]
[2,16,22,18,27,6]
[2,16,18,22,27,6]
[2,16,18,22,6,27]
[2,16,18,6,22,27]
[2,16,6,18,22,27]
[2,6,16,18,22,27]   
Finally the array completely sorted.

Big-o part:

Worst Case : O(n^2)
Avarage Case : O(n^2)
Best Case : O(n)

Time complexity:

Best Case : [2,6,16,18,22,27]
Worst Case : [27,22,18,16,6,2]

the situation of 18:

after the sorting [2,6,16,18,22,27], 18 can be determine "avarega case" .

first four step of [7,3,5,8,2,9,4,15,6]:

[7|,3,5,8,2,9,4,15,6]
[3,7|,5,8,2,9,4,15,6]
[3,5,7|,8,2,9,4,15,6]
[3,5,7,8|,2,9,4,15,6]

Merge sort project:

[16,21,11,8,12,22] first we divide 2 part of the array
- [16,21,11]     [8,12,22]
Then again dividing two part
- [16,21]   [11]   [8,12]   [22]
Then we stop the dividing, because it shaped our desire
we sort each array among themselves
- [16,21]   [11]   [8,12]   [22]
- [11,16,21]   [8,12,22]
- [8,11,12,16,21,22]
And it is finally sorted.

Big-o part:

Worst case   : O(n*logn)
Average case : O(n*logn)
Best case    : O(n*logn)

Binary search tree project:

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] it is the array.

Binary Search Tree is a node-based binary tree data structure which has the following properties:

The left subtree of a node contains only nodes with keys lesser than the node’s key.
The right subtree of a node contains only nodes with keys greater than the node’s key.
The left and right subtree each must also be a binary search tree.
7




  7
 /
5






  7
   /
  5
 /
1 

  7
   / \
  5   8
 /
1 

    7
   / \
  5   8
 / 
1  
 \
  3
  
     7
   / \
  5   8
 / \
1   6
 \
  3
  
       7
     / \
    5   8
   / \
  1   6
 / \
0   3

     7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3

     7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
      
    7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
  
  www.patika.dev









