# morrisprattalgorithm
Bir arama algoritmasıdır. Bir metnin içinde arama yapmamızı sağlar. <br>
Bu algoritmada aranan metindeki bütün ihtimaller denenmez.  <br>Kalıp arama işlemi sırasında herhangi bir karakter karşılaştırması yapmadan önce, önceden hesaplanmış bir dizi kullanır. <br>Bu dizi, kalıbın herhangi bir pozisyonunda oluşabilecek tekrarlanan desenleri takip eder ve böylece daha hızlı bir eşleşme sağlar. <br>
Algoritmanın temel fikri, bir metin içinde kelime ararken, eşleşme başarısız olduğunda önceden hesaplanmış bir dizi değer kullanarak kelimenin hangi pozisyondan devam edeceğini belirlemektir. <br> Bu sayede, eşleşme işlemi daha verimli hale getirilir. <br>
Diğer algoritmalarla karşılaştırıldığında karşılaştırma sayısı daha azdır. Hızlı çalışır. Büyük metin dosyalarında tercih edilir. <br>
##Çalışma zamanı :## <br>
En iyi durumda, Morris-Pratt algoritması O(m+n) zamanda çalışır. <br>En iyi durum metinle tam olarak eşleştiği durumdur. <br> Bu durumda, Morris-Pratt algoritması, tüm metni ve deseni sadece bir kez tarar ve bir eşleşme bulduğunda hemen durur. <br><br>
Ortalama durumda, Morris-Pratt algoritması da O(m+n) zamanda çalışır. <br> Ortalama durumda, desenin metinle tam olarak eşleştiği durumun aksine, desen ve metin arasında bir kısmi eşleşme oluşabilir. <br><br>
En kötü durumda, Morris-Pratt algoritması da O(m+n) zamanda çalışır. En kötü durum, desenin metinde hiçbir karakterle eşleşmediği durumdur.
