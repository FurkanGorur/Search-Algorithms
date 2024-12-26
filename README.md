Başlıca arama algoritmalarını ekleyip iki tanesinin örneğini mevcutta ekleyeceğim yani binary search ve lineer search daha sonra geri kalanları ekleyip anlatımını da yapacağım.

Nedir Arama Algoritmaları?

İstediğimiz verileri veri dizisinin içine dalarak kendine has yöntemlerle arayıp bulmaya çalışan algoritmalara arama algoritması denir.

Lineer Search , Binary Search ,  Jump Search , Exponential Search , 

Boyer-Moore Search , Deep First Search , Breadth First Search



Lineer Search(Doğrusal Arama):

Lineer Search en temel arama algoritmalarından biridir.
Sırayla verileri kontrol ederek elemanı bulmaya çalışır.
Dizinin sıralı olup olmaması önemli değildir.

Karmaşıklık:
En iyi durum O(1) (aranacak veri setindeki ilk eleman hedef elemansa)
En kötü durum O(n) (hedef eleman en sondaysa veya yoksa)

örnek:
sayi dizisi = 12,3,23,16,98,124,46
istenen sayı = 98
bulma adım sayısı= 5
istenen sayı =8
bulma adım sayısı= 7, dizi eleman değeri kadar adım sayısı olur sonuç 0 döner

Binary Search(İkili Arama):

Sayı dizisini ortadan böler eğer verilen sayı ortadan büyükse sağ tarafa küçükse sol tarafa yönelir ve yöenldiği tarafıda ikiye bölerek aynı işlemle devam eder.
Dizinin sıralı olması gereklidir.

Karmaşıklık:
En kötü durumda O(log n) : Dizinin her seferinde bir yarısı arandığı için daha az bir maliyet söz konusu.

Dezavantajı:
Sayılar sıralı olmadan işlem yapamadığı için ilk önce sayıların sıralanması gerekiyor.

örnek:

sayı dizisi(sıralı olduğu varsayılırsa): 24,36,47,51,63,74,77,81

Dizinin ortası olarak daha küçük indeksli elemanı alıyoruz yani:51

aradığımız sayı: 36

36 sayısı 51 ten küçük olduğu için aramayı sol tarafa çeviriyoruz ve sol tarafta ortancayı alıyoruz yani 36.
Aradığımız sayıyı buluyoruz.





