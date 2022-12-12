# Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort
***
### 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. [````2````,27,16,```22```,18,6] -> ```2``` dizinin en küçük sayısıdır en başa gelebilmesi için ```22``` ile yer değiştirir.
2. [2,```6```,16,22,18,```27```] İkinci küçük sayı ```6```'dır ikinci sıraya gelebilmesi için ```27``` ile yer değiştirir.
3. [2,6,16,18,22,27] Üçüncü en küçük sayı ```16```'dır,sıralama doğru olduğu için herhangi bir değişiklik yapılmaz.Dördüncü en küçük sayı ```18```'dir ve sıralamaya doğru olması için ```22``` ile yer değiştirir.Beşinci ve altıncı sayıların sıralaması doğru olduğu için sıralamada değişiklik yapılmaz.
***
### 2) Big-O gösterimini yazınız.
 Dizinin eleman sayısına n dersek işlem sayısı da n olur.<br>
- ```[22,27,16,2,18,6]``` dizisinde 6 tane eleman vardır, yani 6 tane işlem yapılacak demektir.
- ilk adımda n tane(büyük mü?,küçük mü? diye tüm elemanlara bakarız en küçük elemanı buluruz) yani-> 6 işlem .
- ikinci adımda en küçük elemandan sonraki elemanı bulmak için (n-1)-> 6-1=5 işlem
- Üçüncü adımda ilk iki en küçük elemandan sonraki en küçük elemanı bulmak için  (n-2)-> 6-2=4 işlem
- Dördüncü adımda ilk üç en küçük elemandan sonraki en küçük elemanı bulmak için (n-3)-> 6-3=3 işlem
- Beşinci adımda ilk dört en küçük elemandan sonraki en küçük elemanı bulmak için (n-4)-> 6-4=2 işlem.Altı elemanlı bir dizi olduğu için işlem yapılmasına gerek yoktur sona kalan altıncı elemandır.
- n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapılır.Bu işlemin formülü:[n(n+1)]/2 (birden n'e kadar olan sayıların toplamı)sadeleştirdiğimizde ise (n²+n)/2
- Big-o Notationda domine eden fonksiyonu aldığımız için ````n²```` değerini alırız.
### Big-O değeri = O(n²)
***
### 3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
- <b>Best case:</b>Aradığımız sayının dizinin en başında olması<br>
  [18,.,.,.,.,.,.,]
- <b>Average case:</b> Aradığımız sayının dizinin ortada olması<br>
  [.,.,.,18,.,.,.] 
- <b>Worst case:</b> Aradığımız sayının dizinin en sonunda olması<br>
  [.,.,.,.,.,.,18]
- [2,6,16,18,22,27] dizisine baktığımızda 18 sayısı orta kısımda olduğu için <b>```Average Case```</b> kapsamına girer.
***
### 4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1.Adım [2|3,5,8,7,9,4,15,6] 
2.Adım [2,3|5,8,7,9,4,15,6]
3.Adım [2,3,4|8,7,9,5,15,5]
4.adım [2,3,4,5|7,9.8,15,6]<br>
[Patika.dev](https://app.patika.dev/kadergin)
