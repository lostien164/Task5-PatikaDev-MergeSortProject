# MergeSortProject

Project 2

\*\*Task:

        1.[16, 21, 11, 8, 12, 22] dizisini Merge Sort a göre düzenle ve asamalarini yaz.

        2.Big-O gösterimini yaz.

> > 1.Adim : Siralama

\*\*Merge Sort`ta "Böl ve Fethet" yolu izlenerek siralama yapildigi icin öncelikle diziyi ikiye ayirmak gerekir.

1.Böl : [16, 21, 11] ve [8, 12, 22]  
2.Böl : [16, 21] ve [11] ve [8, 12] ve [22]  
3.Böl : [16] [21] [11] [8] [12] [22]  
4.Birlestir : [16 , 21] [8 , 11] [12 , 22]  
5.Birlestir : [6, 8, 11, 21] [12, 22]  
6.Birlestir : [6, 8, 11, 12, 21, 22]

> \*Bu sayede Sirali Dizi [6, 8, 11, 12, 21, 22] elde edilmis olur.

> > 2.Adim : Big-O Gösterimi

\*\*Liste her seviyede ikiye bölündügü icni rekürsif cagri sayisi = log2(n) olurken, birlestirme icin gereken islem sayisi O(n)`dir.

> > Böylece "Big-O = O(n . log2(n))" olmus olur.
