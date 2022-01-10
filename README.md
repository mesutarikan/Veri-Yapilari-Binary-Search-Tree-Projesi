# Veri-Yapilari-Binary-Search-Tree-Projesi
## İkili Arama Ağacı Yapımı
### Aşağıdaki sayı dizisi için bir İkili Arama Ağacı (BST) oluşturun-
```
[7,5,1,8,3,6,0,9,4,2]
```
### Öğeler bir sırayla verildiğinde,
* Her zaman ilk öğeyi kök düğüm olarak düşünün.
* Verilen öğeleri göz önünde bulundurun ve bunları tek tek BST'ye yerleştirin.
 

## İkili arama ağacı aşağıda açıklandığı gibi oluşturulacaktır.

### 7 ekleme
```
        7
```
### 5 ekleme
```
        7
       /
      5
```
### 1 ekleme
```
         7
       /
      5
     /
    1
```
### 8 ekleme
```
         7
       /  \
      5    8
     /
    1
```
### 3 ekleme
```
         7
       /  \
      5    8
     /
    1
     \
      3
```
### 6 ekleme
```
         7
       /  \
      5    8
     / \
    1   6
     \
      3
```
### 0 ekleme
```
         7
       /  \
      5    8
     / \
    1   6
   / \
  0   3
```

### 9 ekleme
```
         7
       /  \
      5    8
     / \    \
    1   6    9
   / \
  0   3
```
### 4 ekleme
```
        7
       / \
      5   8
     / \   \
    1   6    9
   / \
  0   3
       \
        4
```
### 2 ekleme
```
        7
       /  \
      5    8
     / \    \
    1   6    9
   / \
  0   3
     / \
    2   4
```
