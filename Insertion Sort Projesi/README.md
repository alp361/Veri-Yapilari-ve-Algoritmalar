# INSERTION SORT PROJESİ

## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
```
İlk hali -> [22,27,16,2,18,6] -> n
1. Aşama -> [2,27,16,22,18,6] -> (n-1)
2. Aşama -> [2,6,16,18,22,27] -> (n-2)
3. Aşama -> [2,6,16,22,18,27] -> (n-3)
```
2. Big-O gösterimini yazınız.
```
O(n²)
```
3. Time Complexity:
``` 
   Average case: Aradığımız sayının ortada olması -> O(n²) ,
   Worst case: Aradığımız sayının sonda olması -> O(n²), 
   Best case: Aradığımız sayının dizinin en başında olması -> O(n).
```

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
Dizinin sıralanmış hali: [2,6,16,18,22,27]

Bu duruma göre 18 sayısı dizinin ortalarında bulunduğu için Average case
kapsamına girer.
```


## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. adım: [2,3,5,8,7,9,4,15,6]
2. adım: [2,3,4,8,7,9,5,15,6]
3. adım: [2,3,4,5,7,9,8,15,6]
4. adım: [2,3,4,5,6,9,8,15,7]
```
