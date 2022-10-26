>**Denetimli öğrenme algoritmaları: Regresyon (Basit Doğrusal regresyon ve çoklu regresyon) nedir, çalışma mantığı nedir, kullanım alanları, örnekleri**

Denetimli öğrenme, alınan veriler ve bu veriler sonucu elimizdeki oluşan bilgileri etiketleyerek modelleme işlemidir.Öngöremediğimiz verilerle ilgili yapılan tahmin yürütme algoritmasıdır. 

Denetimli öğrenme algoritmaları sürekli ve kategorik olmak üzere iki gruba ayrılır.

Regresyon bağımsız değişken(ler) ve bağımlı değişken arasındaki ilişkiyi açıklamak için kullanılan denetimli algoritma modelleridir. Bu çeşit algoritmalar bağımlı değişkeni tahmin etmeye çalışırlar.

>**Regresyon Analizi Nedir,Nasıl Yapılır?**

Regresyon analizi iki veya daha fazla değişkenin istatistiksel olarak incelenmesi için kullanılan yöntemdir. Üç adımda gerçekleşir:

- **Hipotez Oluşturulur**

Regresyon analizi yapmak için, ilişkili olduğu varsayılan iki değişkeni seçilmelidir. Mümkün olduğu kadar çok veri toplayarak ilişkileri hakkında hipoteziniz oluşturulur fakat bunu yaparken overfitting yapmamaya dikkat edilmelidir.

- **Hipotez Oluşturulur**

İki veri seti ile doğrusal regresyon için temel bir çizgi grafiği oluşturulabilir. Bir değişken X diğeri ise Y ekseninde çizilir. Bir elektronik tabloya girdiğinizde, değişkenler arasındaki korelasyonu gözlemlenebilir. Düz bir çizgi varsa, bu pozitif bir korelasyon gösterir.

- **Sonuçlar Analiz Edilir**

Grafiği temel bir doğrusal regresyonda inceleyerek kesişim, katsayı ve korelasyonu görebilirsiniz. Bu rakamları bir araya getirmek, iki veri seti arasındaki tarihsel ilişkiyi göstererek modelin gelecekte nasıl görüneceğini tahmin etmenize olanak tanır

>**Regresyon Analizi Kullanım Alanları**

- Tahmin

Örnek verecek olursak işletmelerde regresyon analizinin en yaygın kullanım alanı olarak gelecek ve fırsatları tahmin etmek olduğunu söyleyebiliriz.

- CAPM

Bir varlığın öngörülen getirisi ile ilgili piyasa risk primi arasındaki bağlantıyı kuran The Capital Asset Pricing Model (CAPM), doğrusal regresyon modeline dayanır. Finansal analistler tarafından finansal analizde sıklıkla kullanılır.

- Rekabet Karşılaştırma

İki firma arası finansal kıyaslamalar yapmak için kullanılır.Ayrıca iki firmanın hisse senedi fiyatları arasındaki ilişkiyi belirlemek için de kullanılabilir ve hangi yönlerin satışlarını etkilediğini belirlemede firmaya yardımcı olabilir. Bu teknikler sayesinde küçük işletmelerin kısa sürede yükselmesi gerçekleşebilir.

- Güvenilir Kaynak

Daha iyi iş kararları vermek, varsayımları ve içgüdüleri azaltmak için regresyon analizini kullanılır. Yöneticiler, verileri filtrelemek ve mümkün olan en iyi kararları vermek için regresyon analizinden yararlanır.

>**Regresyon Analizi Hangi Sektörlerde Kullanılır**

- Finans

- Pazarlama

- Üretim

- İlaç

>**Makine Öğrenmesinde Regresyon** 


Makine öğrenmesinde regresyon eldeki veri setlerini makineye öğretmeyi amaçlar. Makinenin veri setini ezberlemesinin önüne geçmek ister. Yani tutarlı tahminler yapmasını sağlar.

Bir eğitim seti ve fonksiyonları ile bir veri modeli oluşturup gelen yeni veriler için tahminler yapmaya çalışılır. Yapılan tahminleri sonucu numeric (sayısal) bir değer olmalıdır.

Regresyon analizi işleminde kullanılan regresyon yöntemleri büyük önem arz etmektedir. Kullanılan regresyon yöntemi sonucunda hatalı sonuçlar alınabilir.


>**Basit Doğrusal Regresyon**


Basit doğrusal regresyon açıklayan yani bağımlı değişken ile tek bir açıklayıcı yani bağımsız değişken arasındaki ilişkinin modellenmesidir. Başka bir şekilde ifade edecek olursak bağımlı değişkenin bağımsız değişkenin bir fonksiyonu olarak en doğru biçimde tahmin edilmesidir. Yani basit doğrusal regresyon işlemlerinde tahmin edilmek istenen bağımlı değişkendir.

Basit doğrusal regresyon

- İki değişken arasındaki ilişkinin ne kadar güçlü olduğuna

- Bağımsız değişkenin herhangi bir değerinde bağımlı değişkenin değerlerine

ulaşmak için kullanılır.

>**Basit Doğrusal Regresyon Hesaplamaları**

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

>**Çoklu Regresyon Nedir?**

Doğrusal basit regresyonun bağımsız değişken sayısı birden fazla olan versiyonudur. Yani çoklu regreson denkleminde yanıt değişkenimiz olan bağımlı değişkeni etkileyen birden fazla bağımsız değişken vardır.

![image](https://user-images.githubusercontent.com/73705686/198046006-37d7e82f-0e39-4614-8e27-fc66a84b1306.png)

Çoklu regresyon denklemini yukarıdaki gibi tanımlayabiliriz.

Çoklu doğrusal regresyonda her bağımsız değişkenin bağımlı değişkene etkisi birbirinden farklıdır. Bundan dolayı basit lineer her değişkenin katsayısı birbirinden farklı olabilir. 

>**P değeri nedir?**
Varsayımlarımızın doğruluğunu belirlememize yardımcı olan istatistiksel bir sonuçtur. Yapılan analiz sonucunda eldeki verinin normal değer aralığında olup olmadığını kontrol etmemizi sağlar.

Genellikle, bir veri setinin P değeri önceden belirlenmiş belirli bir miktarın altındaysa (örneğin, 0.05 gibi), bilim insanları deneylerinin "boş hipotezini" reddedeceklerdir. Çünkü değişkenin üzerinde anlamlı bir etkisi olmadığı anlaşılmış olur.

>**Çoklu Doğrusal Regresyon Modeli Oluşturmak**

Çoklu Regresyon modeli oluştururken birden fazla değişken incelememiz gerekir.Çünkü bu değişkenlerin modele etkileri farklıdır. Birden fazla bağımsız değişken içerdikleri için her bir değişken bağımlı değişkene farklı oranlarda etki edebilir ve bu etkilerin hepsi anlamlı olmayabilir.

Bağımlı değişkeni yüksek oranda etkileyen bir değişkeni veri setinden kaldırdığımız zaman oluşacak hatalar veya gereksiz bir değişkeni veri setinden atmadığımız zaman kaybedeceğimiz verim istenilmeyen bir sonuçtur.

>**Regresyon Modeli Kurulumunda 5 Metod**

![image](https://user-images.githubusercontent.com/73705686/198049144-03ff0322-ed55-4d5a-9195-0e49a6601b3a.png)

>**Geriye Doğru Eleme**

Tüm değişkenleri içeren bir modelden, fazlalıklarını atarak daha verimli daha küçük bir model oluşturma içeren algoritmadır. Burada fazlalık olarak ifade ettiklerimiz modele etki ettiğini düşünmediğimiz değişkenlerdir. Bu değişkenler model için belirlenen önem değeri (Bir çeşit eşik değeri(threshold)) altında kalan değişkenlerdir.(p<0.05)

Belirlenen ve modelle alakasız olan bu değişkenler modelden çıkarılır.

En yüksek P değerine sahip değişken bulunur. Eğer önem değerinden yüksekse (P>SL) bir sonraki adıma geçilir. Eğer düşükse modelin geriye doğru eleme algoritmasını tamamlamış olur.

P değeri önem değerinden yüksek değişken modelden çıkartılır ve 3. adıma dönülür. Aynı işlemler tekrar edilir.


>**İleri Doğru Seçme**

Başlangıçta hiçbir bağımsız değişken içermeyen bir modeldir.Sonrasında ise hipoteze en yararlı olduğu tahmin edilen değişkenleri alarak kendisini daha büyük bir model haline getirir.

Sonrasında bir önem değeri belirlenir. (Örneğin SL=0,05)

Eldeki bağımsız değişkenler ve bağımlı değişkenle ayrı ayrı ikişerli modeller oluşturulur. En küçük P değerine sahip değişken seçilir ve modele eklenir. Sonrasında belirlenen önem değerinden düşük olmakla beraber yine en küçük P değerine sahip değişken modele eklenir. Seçilen yeni değişkenin P değerinin önem değerinden fazla oluncaya dek bu işlem yapılır.
En küçük P değerine sahip yeni değişkenin P'nin önem değerinden fazla olduğunu gözlemlendiğinde daha önce eklediğimiz değişkenlerin model için yeterli olduğu anlaşılır.

>**Basit Doğrusal ve Çoklu Doğrusal Regresyon Örnekleri**

![image](https://user-images.githubusercontent.com/73705686/198070288-03c9707b-a997-4923-9354-d36700d93404.png)

Yukarıdaki görselde reklam harcamalarında kullanılan basit doğrusal regresyon örneği gösteriliyor. Oluşturulan regresyon denklemine göre belirli analiz işlemleri yapılabilir.

Örneğin, araştırmacılar hastalara belirli bir ilacın çeşitli dozajlarını uygulayabilir ve kan basıncının nasıl tepki verdiğini gözlemleyebilir. Yordayıcı değişken olarak dozajı ve yanıt değişkeni olarak kan basıncını kullanan basit bir doğrusal regresyon modeline uyabilirler. Regresyon modeli aşağıdaki formu alacaktır:

![image](https://user-images.githubusercontent.com/73705686/198071277-0727b4ce-8ae8-445d-b808-34cc2d272c1c.png)

Bir başka örnek ise şudur:
Tarım bilimcileri, gübre ve suyun mahsul verimi üzerindeki etkisini ölçmek için genellikle doğrusal regresyon kullanırlar.

Örneğin, bilim adamları farklı alanlarda farklı miktarlarda gübre ve su kullanabilir ve bunun mahsul verimini nasıl etkilediğini görebilirler. Yordayıcı değişkenler olarak gübre ve su ve yanıt değişkeni olarak mahsul verimi kullanan çoklu doğrusal regresyon modeline uyabilirler. Regresyon modeli aşağıdaki formu alacaktır:

![image](https://user-images.githubusercontent.com/73705686/198072023-fa07a6a1-e877-4c2a-b2a4-d0d835c5a81f.png)

Verilen bu örnekler basit doğrusal regresyonun kullanıldığı bazı örneklerdir. Şimdi çoklu doğrusal regresyon örneklerini biraz inceleyelim.

Çoklu doğrusal regresyon için verebileceğimiz örneklerin başında Gayrimenkul örneği gelir.

Ev satmak için en iyi zamanı tahmin etmeye yardımcı olacak bir model oluşturmak isteyen bir emlak uzmanısınız. Evleri maksimum satış fiyatından satmak istersiniz, ancak satış fiyatını birden fazla faktör etkileyebilir. Bu değişkenler, diğer faktörlerin yanı sıra evin yaşını, mahalledeki diğer evlerin değerini, devlet okulu sisteminin öğrenci performansına ilişkin nicel ölçümlerini ve yakındaki parkların sayısını içerir.Evlerin maksimum satış fiyatını tahmin etmek için bu dört bağımsız değişkenden bir tahmin modeli oluşturabilirsiniz. Bu faktörlerden herhangi biri katsayı değerleri açısından değişirse değişkenleri ayarlayabilirsiniz.

Bir diğer örnek ise Halk Sağlığı örneğidir.

Bulaşıcı bir hastalığın yayılmasını inceleyen bir epidemiyologsunuz. Mevcut bilinen enfeksiyonlara dayanarak bu hastalığın gelecekteki yayılmasını tahmin etmek istiyorsunuz. Çok sayıda bağımsız değişken, popülasyon büyüklüğü, popülasyon yoğunluğu, hava sıcaklığı, asemptomatik taşıyıcılar ve popülasyonun sürü bağışıklığına ulaşıp ulaşmadığı dahil olmak üzere gelecekteki enfeksiyonların sayısını etkileyebilir. Yordayıcı değişkenlerin katsayı değerlerindeki olası değişiklikleri hesaba katan bir sonucu tahmin etmek için ampirik veriler üzerinde istatistiksel modelleme ve çoklu doğrusal regresyon analizi yapabilirsiniz.


>**KAYNAKÇA**
- https://en.wikipedia.org/wiki/Simple_linear_regression
- https://dergipark.org.tr/en/download/article-file/187511
- https://aws.amazon.com/tr/what-is/logistic-regression/
- https://www.ibm.com/tr-tr/analytics/learn/linear-regression
- https://www.scribbr.com/statistics/simple-linear-regression/#:~:text=What%20is%20simple%20linear%20regressio%20n,Both%20variables%20should%20be%20quantitative.
