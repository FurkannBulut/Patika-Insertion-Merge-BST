# Insertion Sort Projesi
 www.patika.dev
## [22,27,16,2,18,6] -> Insertion Sort 

1.**Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
>
    1.   22 | 27 16 2 18 6
    2.   22 27 | 16 2 18 6
    3.   16 22 27 | 2 18 6
    4.   2 16 22 27 | 18 6
    5.   2 16 18 22 27 | 6
    6.   2 6 16 18 22 27 |
2.**Big-O gösterimini yazınız.**
>
    Her adımda bir eleman ele alınır. Birinci eleman bi kontrol durumu tutmaz , ikinci eleman 1 durum , üçüncü eleman 2 durum ... 
    şeklinde ilerler. Formülümüz burdan n e kadar toplam ilerleyeceği için ve ilk eleman durum temsil etmediği için (n-1) olur. 
    Bu yüzden bunların toplamı ((n-1*n)/2). Big-O da en büyük katsayı ele alındığı için n^2 olarak ifade ederiz.
    O(n^2)
3.***Time Complexity*:**

    - Best Case
        O(n) -> Dizinin sıralı olması durumudur.
    - Worst Case
        O(n^2) -> Bütün değerleri gezme zorunda olma durumudur. 
    - Average Case
        O(n^2) -> Ortalama durumdur. Ne çok iyi ne de çok kötü sonuçlar verir. 
        
4.**Dizi sıralaması sonrası 18 sayısı hangi kapsama girer ?**
>
    Average case kapsamına girer.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
>
    1.  7 | 3 5 8 2 9 4 15 6
    2.  3 7 | 5 8 2 9 4 15 6
    3.  3 5 7 | 8 2 9 4 15 6
    4.  3 5 7 8 | 2 9 4 15 6
    5.  2 3 5 7 8 | 9 4 15 6
