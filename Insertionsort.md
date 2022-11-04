# Insertion Sort Projesi
## Proje 1

**[22,27,16,2,18,6]** ->  Insertion sort



1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


5. **[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**


```
1. [22,27,16,2,18,6] -> Başlangıç

​   [2,27,16,22,18,6] -> 1.Adım

​   [2,6,16,22,18,27] -> 2.Adım

​   [2,6,16,18,22,27] -> 3.Adım
```

 ```
2. n.(n+1)/2 -> 0(n^2)
```

```
3. Time Complexity:       

- Average case -> 0(n^2)

- Worst case -> 0(n^2)

- Best case -> 0(n)
```

```
4. [18] sayısı dizinin ortanca değeri olduğundan dolayı Average case girer.
```

```
5. [7,3,5,8,2,9,4,15,6] -> Başlangıç

   [2,3,5,8,7,9,4,15,6] -> 1.Adım

   [2,3,4,8,7,9,5,15,6] -> 2.Adım

   [2,3,4,5,7,9,8,15,6] -> 3.Adım

   [2,3,4,5,6,9,8,15,7] -> 4.Adım
```

 [patika.dev](https://app.patika.dev/emirhanbalci "patika.profilim")







