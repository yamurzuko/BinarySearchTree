# Proje 3 - BinarySearchTree

[Patika.dev](https://www.patika.dev/tr) Veri Yapıları ve Algoritmalar dersinde olan Binary Search Tree Projesi.

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* Root = 7.
* (5 < Root) olduğu için ***"5, Root'un sol tarafına yazılır."***
* (1 < Root) && (1 < 5) olduğu için ***" 1, 5'in sol tarafına yazılır."***
* (8 > Root) olduğu için ***"8, Root'un sağ tarafına yazılır."***
* (3 < Root) && (3 < 5) && (3 > 1) olduğu için ***"3, 1'in sağ tarafına yazılır."***
* (6 < Root) && (6 > 5) olduğu için ***"6, 5'in sağ tarafına yazılır."***
* (0 < Root) && (0 < 5) && (0 < 1) olduğu için ***"0, 1'in sol tarafına yazılır."***
* (9 > Root) && (9 > 8) olduğu için ***"9, 8'in sağ tarafına yazılır."***
* (4 < Root) && (4 < 5) && (4 > 1) && (4 > 3) olduğu için ***"4, 3'ün sağ tarafına yazılır."***
* (2 < Root) && (2 < 5) && (2 > 1) && (2 < 3) olduğu için ***"2, 3'ün sol tarafına yazılır."***



*                                               7
*                               5                                 8
*                     1                   6                                   9
*              0               3
*                        2          4