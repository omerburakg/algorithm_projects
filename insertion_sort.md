# Insertion Sort Projesi
## [22,27,16,2,18,6] -> Insertion Sort Aşamaları
    1. Aşama = [2,27,16,22,18,6] (n)
    2. Aşama = [2,6,16,22,18,27] (n-1)
    3. Aşama = [2,6,16,18,22,27] (n-2)
***
## Big-O Gösterimi
    (n)+(n+1)+(n+2).....+1
    O(n^2)
***
## Time Complexity
### Best Case
    Aradığımız sayının dizinin en başında olması O(n)
### Average Case
    Aradığımız sayının ortada olması O(n^2)
### Worst Case
    Aradığımız sayının en sonda olması O(n^2)
***
## Dizi Sıralandıktan Sonra 18 Sayısı Hangi Case Kapsamına Girer?
    4.adımda gireceği için average case kapsamına girer.
***
## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    1. Aşama = [2,3,5,8,7,9,4,15,6] (n)
    2. Aşama = [2,3,4,8,7,9,5,15,6] (n-1)
    3. Aşama = [2,3,4,5,7,9,8,15,6] (n-2)
    4. Aşama = [2,3,4,5,6,9,8,15,7] (n-3)