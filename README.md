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

![image](https://user-images.githubusercontent.com/73705686/197874890-7018aa94-ec0d-4a75-ae42-fb1bbafb8b34.png)


satışlar (bağımlı değişken) ve reklamlar(bağımsız değişken) arasındaki ilişki yukarıdaki gibi formülize edilir.


![image](https://user-images.githubusercontent.com/73705686/197875227-bb8ecd57-abae-4760-a0e1-459a1be3a6cd.png)


regresyon fonksiyonu olarak ise yukarıdaki gibi formülize edebiliriz.

