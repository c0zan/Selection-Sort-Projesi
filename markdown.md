# Soru 1
## [22,27,16,2,18,6] -> Insertion Sort

# Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

# Big-O gösterimini yazınız.

# Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

* Average case: Aradığımız sayının ortada olması
* Worst case: Aradığımız sayının sonda olması
* Best case: Aradığımız sayının dizinin en başında olması.

# Cevap 1
- [2,27,16,22,18,6] , [2,6,16,22,18,27] , [2,6,16,18,22,27]

- n+(n-1)+n(n-2)+(n-3)+(n-4) = n(n+1) / 2 = n^2 +n ise BigO = O(n^2)

- 18 sayısı, 16 sayısı ile birlikte bu dizi için best case kapsamına girer.

# Soru 2
## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Cevap 2
 [2,3,5,8,7,9,4,15,6] - [2,3,4,8,7,9,5,15,6] - [2,3,4,5,7,9,8,15,6] - [2,3,4,5,6,9,8,15,7]

