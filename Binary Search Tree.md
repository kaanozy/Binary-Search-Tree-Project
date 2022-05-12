# Binary-Search-Tree-Project
Question: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Answer: 

- Verilen sayı öbeği dikkate alınarak sayılar soldan sağa sırayla seçilerek ağaca yerleştirilmelidir. Bu yüzden ağacın rootu 7 dir.

```
                        7
```

- Yediden küçük sayılar  7 nin solunda   olmalı.            
- Yediden büyük sayılar  7 nin sağında   olmalı.

- 7 yerleştirildikten sonra 5 sayısı 7 nin soluna yazılmalıdır çünkü 5 daha küçük bir sayıdır.

```
                        7
                5
```

- Ardından 1 sayısı ağaca yerleştirilmeldir. Sayı 7 den küçük olduğundan sol tarafta olmaldır. Ayrıca 5 sayısından da küçük olduğu için 1 sayısı 5 in de sol tarafında olmalıdır.

```
                        7
                 5
        1
```

- 8 sayısı 7 den büyük olduğu için ağacın veya 7 nin sağına yazılmalıdır.

```
                         7
                 5                  8
        1                                       
```
- 3 sayısı 7 ve 5 ten küçüktür, ancak 1 den büyüktür. Bu durumda 3 sayısı 7 ve 5 in solunda fakat 1 in sağına yazılmalıdır.

```
                         7
                 5                   8
        1
            3
```

- 6 sayısı 7 den küçük ama 5 den büyüktür. Bu yüzden 6 sayısının 7 nin soluna ve 5 in sağına yazılması gerekir.

```
                         7
                 5                   8
    1                 6
           3
```

- 0 sayısı 7, 5 ve 1 den küçük olduğundan 1 in soluna yazılması gerekir.

```
                         7
                 5                   8
     1                6
0          3
```
- 9 sayısı soruda verilen sayı öbeğindeki en büyük sayıdır, 7 ve 8 in sağına yazılmalıdır. 

```
                         7
                 5                   8
     1                6                        9
0          3       
```
- 4 sayısı 7 ve 5 den küçüktür fakat 1 den büyüktür. Aynı zamanda 3 ten de büyüktür. Bu yüzden 3 ün sağına ve 5 in soluna yazılmalıdır.

```
                         7
                 5                   8
     1                6                        9
0          3
              4
```
- 2 sayısı 7 ve 5 den küçük fakat 1 den büyüktür. Ek olarak 3 den küçüktür. Bu durumda sayı 1 in sağına fakat 3 ün soluna yazılmalıdır.

```
                         7
                 5                   8          
     1                6                        9
0          3
        2     4
```

## Licence

[MIT](https://www.mit.edu/)

[Patika.dev](https://www.patika.dev/tr)

