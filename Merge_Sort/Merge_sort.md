### [16,21,11,8,12,22] -> Merge Sort
***
### 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
                         
                            [16,21,11,8,12,22]
                           /                  \            İlk önce sayı dizisini ikiye böleriz.   
                          /                    \              
                [16,21,11]                      [8,12,22]
               /          \                    /         \  Daha sonra böldüğümüz dizileri tekrar ikiye böleriz.
              /            \                  /           \
       [16,21]              [11]        [8,12]             [22]
              \            /                  \           /  Elde edilen diziler 2 veya daha az eleman sayısına ulaştığı için bölme işlemini durduruz.
               \          /                    \         /   Alt dizileri kendi içinde sıralarız. 
                [11,16,21]                      [8,12,22]                       
                          \                    /             Sıralı iki alt diziyi tek bir sıralı dizi olacak şekilde birleştiririz.
                           \                  /
                            [8,11,12,16,21,22]
***
#### 2) Big-O gösterimini yazınız.
