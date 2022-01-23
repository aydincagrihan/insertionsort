Insertion sort worst case n2
Örnek Veri Kümesi, [22,27,16,2,18,6]
Insertion Sort en basit tabiri ile veri kümesi içerisindeki indisleri tek tek gezerek sıralama yapar.
Örneğimizde bulunan 6 elemanlı dizide küçükten büyüğe sıralama işlemi yapalım.
i=1 için yani dizinin ikinci elemanı ile ilk elemanını karşılaştırıyoruz.
22<27 ? true i++
i=2 
27<16? false ve ilk elemanıda kontrol ediyor
[16,22,27,2,18,6] son durumu
i=3
2<27? true diğer sıraladıklarımızlada karşılaştırıyoruz ve 0.indexe alıyoruz 
[2,16,22,27,18,6]
i=4
27<18?true 2.index 18 oluyor
[2,16,18,22,27,6]
i=5
27<6 last step
[2,6,16,18,22,27] küçükten büyüğe verilerimiz sıralanmış oluyor.

