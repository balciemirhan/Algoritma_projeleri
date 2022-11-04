# Merge Sort Projesi
## Proje 2
**[16,21,11,8,12,22] -> Merge Sort**

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
```
Parçalama:

[16,21,11,8,12,22] 



[16,21,11] - [8,12,22]



[16] - [21,11] - [8] - [12-22]



[16] - [21] - [11] - [8] - [12] - [22]

```
```
Birleştirme: 

[16] - [11-21] - [8] - [12-22]



[11-16-21] - [8-12-22]



[8-11-12-16-21-22]




```


```
Big-O gösterimi:

2^x = n

= O(nlogn)
```
![](C:\Users\Monster\Desktop\Ekran görüntüsü 2022-11-04 040914.jpg)
