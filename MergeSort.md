www.patika.dev
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Answers

16 21 11 8 12 22

Divide array by 2 until every group has 1 or 2 elements

16 21 11 | 8 12 22 => 1st step
16 | 21 11 || 8 | 12 22 => 2nd step

Sort the elements of each group

16 | 11 21 || 8 | 12 22 => 3rd step

Conquer the groups down to up 

11 16 21 | 8 12 22 => 4rd step

8 11 12 16 21 22 => 5th step

Complexity => O(nlogn)