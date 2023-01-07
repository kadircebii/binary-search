# binary-search
Kodluyoruz eğitim kapsamında binary search ödev
Binary search tree algoritmasında ilk olarak kök değer belirlenir. kök değerin sağı ve solu olmak üzere ikiye ayrılarak her seferinde sayı dizisi ikiye ayrılır.

{7,5,1,8,3,2,0,9,4,2} sayı dizisini binary search algoritmasında:

Aşama: Root 4'dür. 4'in sağında 5 solunda 3 olmak üzere sayı dizisi ikiye ayrılır.
aşama: 3 elemanı 4'ten küçük olduğundan sol tarafa yazılır. 5 elemanı büyük olduğundan sağ tarafa yazılır.
aşama: 2 elemanı 3'ten küçük olduğundan sol tarafa 6 ise 5'ten büyük olduğundan sağ tarafa yazılır.
aşama: 2 elemanı 3'ten küçük olduğundan sol tarafa 7 ise 6'dan büyük olduğundan sağ tarafa yazılır.
aşama: 1 elemanı 2'den küçük olduğundan sol tarafa 8 ise 7'den büyük olduğundan sağ tarafa yazılır.
aşama: 0 elemanı 1'den küçük olduğundan sol tarafa 9 ise 8'den büyük olduğundan sağ tarafa yazılır.
4
3 5
2 6
1 7
0 8
9
Sayı dizisi her aşamada ikiye bölündüğünden algoritmanın time complexity 2 üzeri X= n= logn
