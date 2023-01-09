# Binary-Search-Tree
Proje kapsamında verilen diziyi Binary search tree aşamalarını yazdığımız hale getirmek üzere oluşturulmuş çalışmadır.

# Proje 3

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

*Öncelikle binary-search-tree oluşturabilmek için verilen dizini sıralanması gerekmektedir.*

[0,1,2,3,4,5,6,7,8,9] şeklinde 10 elemanlı bir dizinimiz mevcuttur. En uygun binary-search-tree için ortanca elemanı alırız. Mevcut dizin 10 elemanlı olup ortalaması 4,5 olduğundan ben 5'i root olarak alacağım. 

**Root 5'tir. Root'un solunda 3, sağında 7 bulunur.**

*Root'un sol tarafını anlatacak olursak:*

**3'ün sağında 4, solunda 1 bulunur. 1'in solunda 0, sağında 2 bulunur.**

*Root'un sağ tarafını anlatacak olursak:*

**7'nin solunda 6, sağında 9 bulunur. 9'un solunda 8 bulunur.**

***Görsel olarak bu şekildedir:***

![Görsel olarak bu şekildedir](https://imgyukle.com/f/2023/01/09/J3D0vt.jpeg)