### [22,27,16,2,18,6]

1.Aşama : Dizideki en küçük eleman bulunur. En küçük eleman 2'dir  .Daha sonra 2 sayısı ilk sıraya yerleştirmek için 22 ile yer değiştirilir.

2.Aşama : Dizideki 2 sayısından sonra en küçük eleman bulunur.En küçük eleman 6'dır. Daha sonra 6 sayısı dizinin ikinci sayısı olması için 27 ile yer değiştirilir.

3.Aşama : Dizideki 6 sayısından sonra en küçük eleman bulunur.En küçük eleman 16 dır. 16 sayısı olması gereken yerde olduğu için değişiklik yapılmaz

4.Aşama : Dizideki 16 sayısımdan sonra en küçük eleman bulunur.En küçük eleman 18 dır. Daha sonra 18 sayısı dizinin dördüncü sayısı olması için 22 ile yer değiştirilir.

5.Aşama : Dizinin beşinci ve altınıcı elamanı olan 22 ve 27 olması gereken sırada oldukları için değişiklik yapılmaz.

##### Son Hali : (2,6,16,18,22,27)

##### Big-O gösterimi O(n2) dir.

##### Time Complexity:aradıgımız 18 sayısı ortada oldugu için Average case dir.

1.Adım :[2,3,5,8,7,9,4,15,6] 2 ile 7 sayısı yer değişti

2.Adım :[2,3,5,8,7,9,4,15,6] 3 sayısı yerinde değişiklik yok

3.Adım :[2,3,4,8,7,9,5,15,6] 5 ile 4 sayısı yer değişti.

4.Adım :[2,3,4,5,7,9,8,15,6] 8 ile 5 yer değiştirdi.