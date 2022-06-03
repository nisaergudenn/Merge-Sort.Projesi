# Merge-Sort.Projesi

[16,21,11,8,12,22] 

Soru-1 ) Yukarıdaki dizinin sort türüne göre aşamalarını :
Öncelikle bu diziyi ikiye bölüyoruz. Sonrasında elimizde olan dizileri de ikiye bölerek dizinin içinde bir tane sayı kalana kadar bölerek ilerliyoruz. 
Ve en sonda sayıları küçükten büyüğe doğru tekrar sıralayarak birleştirip yazıyoruz. İkiye böldüğümüz hali:

            1-[16,21,11] aynı şekilde tekrar bölüyoruz:  [16] , [21,11] bir dizide iki sayı olduğu için onu tekrar bölüyoruz : [21] ve [11] şeklinde olur. 
                     Sonrasında bu diziyi tekrar birleştirirsek = [11,16,21]
            2-[8,12,22] aynı şekilde tekrar bölüyoruz: [8,12] , [22] bir dizide iki sayı olduğu için onu tekrar bölüyoruz : [8] ve [12] şeklinde olur.
                     Sonrasında bu diziyi tekrar birleştirirsek =  [8,12,22]
         
         Bu iki aşamada bittiğine göre hepsini toplayarak birleştiririz : [8,11,12,21,22] şeklinde son halini alır.
         
 Soru-2 ) Big-O gösterimini yazınız.
 
 Merge sort' un Big- o gösterimi : O(nlogn) şeklindedir.
