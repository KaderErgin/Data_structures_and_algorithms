## Binary Search Tree Projesi
### [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
***
##### Root'un sağ tarafından kendinden büyük elemanlar, sol tarafında ise kendinden küçük elemanlar yer alır.
- <b>```Root -> 7 alırsak``` </b>.
-  <b>```5```</b>, 7'den küçük olduğu için 1. Düğüm Satırı'nda 7'nin sol tarafında yer alır.

                    7          -> Root Satırı
                   /
                  /
                 5             -> 1. Düğüm Satırı
               
- <b> ```1``` </b>, 7 ve 5'ten küçük olduğu için  2. Düğüm Satırı'nda 5'in sol tarafında yer alır. 

                   7          -> Root Satırı
                  /
                 /
                5             -> 1. Düğüm Satırı
               /
              /
             1                -> 2. Düğüm Satırı

- <b>```8```</b>, 7'den büyük olduğu için 1. Düğüm Satırı'nda 7'nin sağ tarafında yer alır.            
        
                  7           -> Root Satırı
                 / \
                /   \
               5     8        -> 1. Düğüm Satırı
              /
             /
            1                 -> 2. Düğüm Satırı

- <b>  ```3``` </b> , 7 ve 5'ten küçüktür ama  1'den büyük olduğu için  3. Düğüm Satırı'nda 1'in sağ tarafında yer alır.   
        
                  7           -> Root Satırı
                 / \
                /   \
               5     8        -> 1. Düğüm Satırı
              /
             /
            1                 -> 2. Düğüm Satırı
             \
              \
               3              -> 3. Düğüm Satırı
               
- <b>  ```6``` </b> , 7'den küçüktür ama 5'ten büyük olduğu için  2. Düğüm Satırı'nda 5'in sağ tarafında yer alır.   
        
                  7          -> Root Satırı
                 / \
                /   \
               5     8       -> 1. Düğüm Satırı
              / \
             /   \
            1     6          -> 2. Düğüm Satırı
             \
              \
               3             -> 3. Düğüm Satırı
               
- <b> ```0``` </b> , 7, 5, ve 1'den küçük olduğu için 3. Düğüm Satırı'nda 1'in sol tarafında yer alır.
                  
                  7          -> Root Satırı
                 / \
                /   \
               5     8       -> 1. Düğüm Satırı
              / \
             /   \
            1     6          -> 2. Düğüm Satırı
           / \
          /   \
         0     3             -> 3. Düğüm Satırı
         
- <b> ```9``` </b> , 7 ve 8'den büyük olduğu için 2. Düğüm Satırı'nda 8'in sağ tarafında yer alır.

                  7          -> Root Satırı
                 / \
                /   \
               5     8       -> 1. Düğüm Satırı
              / \     \
             /   \     \
            1     6     9    -> 2. Düğüm Satırı
           / \
          /   \
         0     3             -> 3. Düğüm Satırı
         
 - <b> ```4``` </b> , 7 ve 5'ten küçüktür ama 1 ve 3'ten büyük olduğu için 4. Düğüm Satırı'nda 3'ün sağ tarafında yer alır. 

                  7          -> Root Satırı
                 / \
                /   \
               5     8       -> 1. Düğüm Satırı
              / \     \
             /   \     \
            1     6     9    -> 2. Düğüm Satırı
           / \
          /   \
         0     3             -> 3. Düğüm Satırı
                \
                 \
                  4          -> 4. Düğüm Satırı
                  
 
 - <b>  ```2``` </b> , 7 ve 5'ten küçük 1'den büyük ve 3'ten küçük olduğu için 4. Düğüm Satırı'nda 3'ün sol tarafında yer alır.

                  7          -> Root Satırı
                 / \
                /   \
               5     8       -> 1. Düğüm Satırı
              / \     \
             /   \     \
            1     6     9    -> 2. Düğüm Satırı
           / \
          /   \
         0     3             -> 3. Düğüm Satırı
              / \
             /   \
            2     4          -> 4. Düğüm Satırı
                  

 <br>
 
 [Patika.dev](https://app.patika.dev/kadergin)
 
