# insertion-sort
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

çözüm:

[22,27,16,2,18,6]  n 

[2, | 27,16,22,18,6] n-1 

[2,6, | 16,22,18,27] n-2 

[2,6,16,18, | 22,27] 1 

Big-O gösterimini yazınız.

çözüm: 

Big-O: => İşlemler n'den 1'e kadar gideceği için, 1'den n'e kadar olan sayıların toplamı sonucu verecektir. 

n.(n+1)/2 
= n^2 
=> o(n^2) 
 
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması 

Worst case: Aradığımız sayının sonda olması 

Best case: Aradığımız sayının dizinin en başında olması.

çözüm:

Time Complexity: sıralama bu şekilde [2,6,16,18, 22,27] olduğu için Lower = 2 , Higher = 27 ve Middle = 18 olacaktır. Bu durumda 18 sayısı Average Case için uygundur. 

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

çözüm:

[7,3,5,8,2,9,4,15,6] n 

[2, | 3,5,8,7,9,4,15,6] n-1 

[2,3,4, | 8,7,9,5,15,6] n-2 

[2,3,4,5, | 7,9,8,15,6] n-3 

[2,3,4,5,6, | 9,8,15,7] n-4 

 
