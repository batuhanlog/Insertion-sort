# Insertion-sort
patika.dev

Insertion Sort diziyi, dizinin sol tarafından başlayarak sıralayan bir sıralama algoritmasıdır. Bu algoritma, dizinin her elemanını sıralanmış bir parçaya eklemek için kullanır. Aşağıdaki gibi çalışır:

Dizinin ilk elemanı sıralanmış bir parça olarak kabul edilir.
İkinci eleman dizinin sol tarafından sağa doğru geçirilir ve sıralanmış parçaya uygun bir yerde yerleştirilir.
Üçüncü eleman aynı şekilde dizinin sol tarafından sağa doğru geçirilir ve sıralanmış parçaya uygun bir yerde yerleştirilir.
Bu işlem dizinin sonuna kadar devam eder.
Insertion Sort dizinin boyutu n olsun, a worst case senaryosunda, her elemanın dizinin en başına gitmesi gerektiğinde O(n^2) olur. Best case senaryosunda ise, dizinin baştan sona sıralı gelmesi halinde sadece O(n) olur. Average case senaryosu ise O(n^2) olur.



[22]
[22,27]
[16,22,27]
[2,16,22,27]
[7,3,5,8,2,9,4,15,6] 

[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
