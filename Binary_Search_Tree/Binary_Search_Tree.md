## Binary Search Tree Projesi
### [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
***
##### Root'un sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar yer alır.
- ```Root -> 7``` alırsak.
-  ```5```, 7'den küçük olduğu için 1. Düğüm Satırı'nda 7'nin sol tarafında yer alır.

                   7         -> Root Satırı
                 /
                /
               5             -> 1. Düğüm Satırı
               
- ```1```, 7 ve 5'ten küçük olduğu için  2. Düğüm Satırı'nda 5'in sol tarafında yer alır.  

                7           -> Root Satırı
              /
             /
            5               -> 1. Düğüm Satırı
           /
          /
         1                  -> 2. Düğüm Satırı
