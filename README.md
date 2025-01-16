Maksimum Toplam Bulma Algoritmalarının Analizi



Bu projede, aynı sonucu veren iki farklı algoritmanın zaman karmaşıklıkları karşılaştırılmıştır.
Verilen bir A = [a₁, ..., aₙ] dizisinde, toplamı en büyük olan iki elemanın indekslerini ve toplamlarını bulan algoritmalar geliştirilmiştir.

Örnek:
A = [1, 13, -6, 7, 1] dizisi için, toplamı en büyük olan indeksler (1, 3) ve toplam sonucu 20'dir.

Yavaş Algoritma (Slow) - Brute Force
Bu algoritma, tüm olası indeks çiftlerini değerlendirerek en büyük toplamı bulur.

Zaman Karmaşıklığı: O(n²)
Algoritma, her iki elemanın toplamını her durumda kontrol etmek zorunda olduğu için hiçbir durumda daha hızlı çalışamaz. Hem en iyi hem de en kötü durumda zaman karmaşıklığı aynıdır.
Hızlı Algoritma (Fast) - Merge Sort
Bu algoritma, diziyi önce Merge Sort yöntemiyle sıralar ve ardından sıralı dizinin son iki elemanını toplar.

Zaman Karmaşıklığı: O(n log n)
Merge Sort algoritmasının sıralama işlemi her durumda O(n log n) zaman alır. Sıralı dizide son iki elemanın toplamını bulma işlemi ise O(1) karmaşıklığındadır. Sonuç olarak, algoritmanın toplam karmaşıklığı O(n log n) olarak kalır.


Bu proje, Brute Force ve Merge Sort algoritmalarını analiz ederek, zaman karmaşıklıklarının büyük veri setlerindeki etkilerini karşılaştırmayı amaçlamaktadır. Merge Sort algoritması, daha düşük zaman karmaşıklığı sayesinde büyük boyutlu veri setlerinde çok daha verimli çalışmaktadır.
