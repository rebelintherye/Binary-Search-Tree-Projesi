## Binary-Search-Tree-Projesi

[patika.dev](www.patika.dev)

#Birinci Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---
```
Root burada 7'dir. Bu durumda 7 ile başlayacağız.
7
```

---
```
    7
   /
  5
```

---
```
      7
     /
    5 
   /
  1 
```

---
```
      7
     / \
    5   8
   /
  1
   \
    3
```

---
```
      7
     / \
    5   8
   /
  1
   \
    3
```

---
```
      7     
     / \
    5   8
   / \
  1   6
   \
    3  
```

---
```

        7     
       / \
      5   8
     / \   
    1   6   
   / \
  0   3 
  
```

  
---
```
      7     
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3 
     \
      4 
```

---
```
      7     
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3 
     \
      4 
```

---
```
       7     
      / \
     5   8
    / \   \
   1   6   9
  / \
 0   3 
    / \
   2   4 
```

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
Açıklaması: Root= 7,
5, 7'den küçüktür, soluna yazılır. 1, 5'ten küçüktür soluna yazılır. 8, 7'den büyüktür sağına yazılır.  3, 1'den büyüktür sağına yazılır. 6, 5'ten büyüktür sağına yazılır. 0, 1'den küçüktür soluna yazılır. 9, 8'den büyüktür sağına yazılır. 4, 3'ten büyüktür sağına yazılır. 2, 3'ten küçüktür soluna yazılır.
   
