# BINARY SEARCH TREE PROJESİ

## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
> Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
```
1.Aşama: Root 3 olsun. 3'ün sağında: [7,5,8,6,9,4], solunda: [0,1,2] bulunur.
    >             [3]
    >     [0,1,2]     [7,5,8,6,9,4] 
```
```
2.Aşama: 3'ün sağındakileri için root 6, solundakiler için root 1 olsun.
          Bu durumda 6'nın sağında: [7,8,9], solunda: [4,5] bulunur.
          Diğer taraftan 1'in sağında: [2], solunda: [0] bulunur.
    >              [3]
    >       [1]             [6]
    >   [0]     [2]   [4,5]     [7,8,9]
```
```
3.Aşama: 3'ün sol tarafı için tree tamamlandı. Sağ tarafında ise son aşama kaldı.
         6'nın sağındakileri için root 8, solundakileri için root 5 olsun.
         Bu durumda 8'in sağında: [9], solunda: [7] bulunur.
         Diğer taraftan 5'in sağında eleman bulunmaz, solunda [4] bulunur.
    >               [3]
    >       [1]              [6]
    >   [0]     [2]      [5]       [8]
    >                 [4]       [7]   [9]
```