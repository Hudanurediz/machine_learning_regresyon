**Denetimli öğrenme algoritmaları: Regresyon (Basit Doğrusal regresyon ve çoklu regresyon) nedir, çalışma mantığı nedir, kullanım alanları, örnekleri**

Denetimli öğrenme, alınan veriler ve bu veriler sonucu elimizdeki oluşan bilgileri etiketleyerek modelleme işlemidir.Öngöremediğimiz verilerle ilgili yapılan tahmin yürütme algoritmasıdır. 

Denetimli öğrenme algoritmaları sürekli ve kategorik olmak üzere iki gruba ayrılır.

Regresyon bağımsız değişken(ler) ve bağımlı değişken arasındaki ilişkiyi açıklamak için kullanılan denetimli algoritma modelleridir. Bu çeşit algoritmalar bağımlı değişkeni tahmin etmeye çalışırlar.

**Makine Öğrenmesinde Regresyon** 


Makine öğrenmesinde regresyon eldeki veri setlerini makineye öğretmeyi amaçlar. Makinenin veri setini ezberlemesinin önüne geçmek ister. Yani tutarlı tahminler yapmasını sağlar.

Bir eğitim seti ve fonksiyonları ile bir veri modeli oluşturup gelen yeni veriler için tahminler yapmaya çalışılır. Yapılan tahminleri sonucu numeric (sayısal) bir değer olmalıdır.

Regresyon analizi işleminde kullanılan regresyon yöntemleri büyük önem arz etmektedir. Kullanılan regresyon yöntemi sonucunda hatalı sonuçlar alınabilir.


**Basit Doğrusal Regresyon**


Basit doğrusal regresyon açıklayan yani bağımlı değişken ile tek bir açıklayıcı yani bağımsız değişken arasındaki ilişkinin modellenmesidir. Başka bir şekilde ifade edecek olursak bağımlı değişkenin bağımsız değişkenin bir fonksiyonu olarak en doğru biçimde tahmin edilmesidir. Yani basit doğrusal regresyon işlemlerinde tahmin edilmek istenen bağımlı değişkendir.

Basit doğrusal regresyon

- İki değişken arasındaki ilişkinin ne kadar güçlü olduğuna

- Bağımsız değişkenin herhangi bir değerinde bağımlı değişkenin değerlerine

ulaşmak için kullanılır.

**Basit Doğrusal Regresyon Hesaplamaları**

![image](https://user-images.githubusercontent.com/73705686/197873049-8a96866e-e1ad-43fa-9d09-492f2ac355c9.png)

Basit doğrusal regresyon formülünde y değeri yanıt değişkeni yani bağımlı değişkenimizdir. Bu değişkenin bağımsız değişken x ile aralarındaki ilişki doğrusal regresyon modelinde incelediğimiz ilişkidir.
Formülde bulunan 𝓔 değeri Gerçek değer ve tahmini değer arasındaki farktır.

![image](https://user-images.githubusercontent.com/73705686/197874374-6e7b297b-c982-4313-8879-75f79510e1ee.png)

Bu farka göre modeller arasındaki doğruluk kontrolü yapılır.

Bir örnek verecek olursak bir pazarlama firmasının televizyon, gazete ve radyoya verdiği reklamların satışlar üzerindeki etkisini araştırdığını düşünelim.

![image](https://user-images.githubusercontent.com/73705686/197875886-902fd1d3-1d14-49f8-b007-b2f492f9af3f.png)


satışlar (bağımlı değişken) ve reklamlar(bağımsız değişken) arasındaki ilişki yukarıdaki gibi formülize edilir.


![image](https://user-images.githubusercontent.com/73705686/197875227-bb8ecd57-abae-4760-a0e1-459a1be3a6cd.png)


regresyon fonksiyonu olarak ise yukarıdaki gibi formülize edebiliriz.

![image](https://user-images.githubusercontent.com/73705686/197875988-4a268731-f071-4790-a600-f5f009c2c683.png)


Yukarıda tv ve satış verilerine göre oluşturulmuş bir grafik gösterilmektedir. Bu grafikte bulunan mavi renkli doğru regresyon çizgisidir yani tahmini değerimizdir. Kırmızı olarak gösterilen noktalar ise gerçek değerlerimizdir. Regresyon çizgisi ve gerçek değerler arasındaki fark 𝓔 yani hata payıdır.

Basit doğrusal regresyon analizi sonucu parametre kestirimlerinin güvenli olabilmesi için bazı varsayımların geçerli olması gereklidir .
Modeldeki bağımsız değişkenlerin, bağımlı değişkeni ne kadar açıkladığı R2 değeri ile ölçülür.

R2 değeri 

-Toplam Kareler Toplamı

-Artık Kareler Toplamı

değerleri ile hesaplanır.

![image](https://user-images.githubusercontent.com/73705686/197877258-01c1c364-18ac-4284-ae39-a40e373de3be.png)


R2  0-1 arasında bir değer alır. R2 değerinin 1’e yakın olması bağımsız değişkenlerin, bağımlı değişkenleri iyi bir şekilde açıkladığını gösterir.

**Çoklu Regresyon Nedir?**

Doğrusal basit regresyonun bağımsız değişken sayısı birden fazla olan versiyonudur. Yani çoklu regreson denkleminde yanıt değişkenimiz olan bağımlı değişkeni etkileyen birden fazla bağımsız değişken vardır.

![image](https://user-images.githubusercontent.com/73705686/198046006-37d7e82f-0e39-4614-8e27-fc66a84b1306.png)

Çoklu regresyon denklemini yukarıdaki gibi tanımlayabiliriz.

Çoklu doğrusal regresyonda her bağımsız değişkenin bağımlı değişkene etkisi birbirinden farklıdır. Bundan dolayı basit lineer her değişkenin katsayısı birbirinden farklı olabilir. 

**P değeri nedir?**
Varsayımlarımızın doğruluğunu belirlememize yardımcı olan istatistiksel bir sonuçtur. Yapılan analiz sonucunda eldeki verinin normal değer aralığında olup olmadığını kontrol etmemizi sağlar.

Genellikle, bir veri setinin P değeri önceden belirlenmiş belirli bir miktarın altındaysa (örneğin, 0.05 gibi), bilim insanları deneylerinin "boş hipotezini" reddedeceklerdir. Çünkü değişkenin üzerinde anlamlı bir etkisi olmadığı anlaşılmış olur.

**Çoklu Doğrusal Regresyon Modeli Oluşturmak**






