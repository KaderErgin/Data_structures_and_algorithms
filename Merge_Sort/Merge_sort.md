### [16,21,11,8,12,22] -> Merge Sort
***
### 1) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
                
   
              /            \                  /           \
       [16,21]              [11]        [8,12]             [22]
              \            /                  \           /  Elde edilen diziler 2 veya daha az eleman sayısına ulaştığı için bölme işlemini durduruz.
               \          /                    \         /   Alt dizileri kendi içinde sıralarız.
                [11,16,21]                      [8,12,22]                       
                          \                    /
                           \                  /              Sıralı iki alt diziyi tek bir sıralı dizi olacak şekilde birleştiririz.
                            [8,11,12,16,21,22]
                            
                            
                            
                        [16,21,11,8,12,22]
                       /                  \     Sıralı olmayan diziyi ilk önce ikiye böleriz.
                      /                    \
            [16,21,11]                      [8,12,22]
           /          \                    /         \   Daha sonra böldüğümüz dizileri tekrar ikiye böleriz.
          /            \                  /           \
   [16,21]              [11]            [8]            [12,22]
   /      \             /                  \           /      \   Tek elemanlı diziler elde edene kadar devam ederiz.
  /        \           /                    \         /        \
[16]      [21]       [11]                   [8]     [12]       [22]
  \        /           \                    /         \        /  Elde ettiğimiz dizileri adım adım birleştirme işlemi yaparız.
   \      /             \                  /           \      /
    [16,21]             [11]             [8]            [12,22]
          \            /                    \          /
           \          /                      \        /     Dizi elemanlarını kıyaslıyarak sıralanmış diziler elde ederiz.
            [11,16,21]                       [8,12,22]
                      \                     /
                       \                   /       En son aşamada tek bir sıralanmmış dizi olucak şekilde birleştirmiş oluruz.
                         [8,11,12,16,21,22]
***
#### 2) Big-O gösterimini yazınız.
2^x=n -> logn=x  <br>
<b>```O(nlogn)``` <br></b>

[Patika.dev](https://app.patika.dev/kadergin)
