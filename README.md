# Veri Yapıları ve Algoritmalar

## Insertion Sort

### [22,27,16,2,18,6] -> Insertion Sort
- [22,16,27,2,18,6] --> [16,22,27,2,18,6] -->[16,22,2,27,18,6] --> [16,2,22,27,18,6] --> [2,16,22,27,18,6] --> [2,16,22,18,27,6] --> [2,16,18,22,27,6] --> [2,16,18,22,6,27] --> [2,16,18,6,22,27] --> [2,16,6,18,22,27] --> [2,6,16,18,22,27]
- Big-O gösterimi --> O(n^2)
- The worst case time complexity:O(n^2), the average case time complexity:O(n^2), the best case time complexity:O(n)
- 18 sayısı avarage case kapsamına girer.
- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız. --> [3,7,5,8,2,9,4,15,6] --> [3,5,7,8,2,9,4,15,6] --> [3,5,7,2,8,9,4,15,6] --> [3,5,2,7,8,9,4,15,6]

## Merge Sort

### [16,21,11,8,12,22]
- [16,21,11] [8,12,22] ---> [16] [21,11] - [8] [12,22] ---> [16] - [21] [11] -- [8] - [12] [22] ---> [16] [11,21] - [8] [12,22] ---> [11,16,21] - [8,12,22] ---> [8,11,16,12,21,22]
- Big-O gösterimi ---> O(nlogn)

## Binary Search Tree
- [7,5,1,8,3,6,0,9,4,2]

![Ekran görüntüsü 2022-05-12 164753](https://user-images.githubusercontent.com/95437125/168090620-9373cb6e-52a3-434f-9279-5e7e491b6d85.png)
