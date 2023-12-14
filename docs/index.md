# Doğal Dil İşleme Nedir
Doğal Dil İşleme, bilgisayarlara insan dilini anlama, yorumlama ve işleme yeteneği kazandıran bir makine öğrenimi teknolojisi olarak kabul edilir. Şirketler bugün, e-postalar, metin mesajları, sosyal medya gönderileri, videolar ve ses kayıtları gibi çeşitli iletişim kanallarından büyük miktarda metin ve ses verisi elde etmektedir. Bu elde ettiklerin boyutu oldukça büyüktür. Bu verileri otomatik olarak işleyerek, iletilerdeki niyeti veya duyguyu analiz etmek için doğal dil işleme kullanmaktadırlar [[1]](https://aws.amazon.com/tr/what-is/nlp/).

# Temel Kavramlar ve İşlemler
+ Tokenize Etme
    +	Ham metni daha küçük parçalara ayırma işlemi olarak bilinir. İki çeşit işlem tipi vardır ilki cümleleri ikincisi kelimeleri tokenize etmeye yöneliktir [[2]](https://miuul.com/not-defteri/dogal-dil-islemede-temel-kavramlara-hizli-bir-bakis).
+ Metin Temizleme
    +  Metni parçalara ayırdıktan sonra gereksiz unsurları çıkarmak için metin temizleme adımı gereklidir, örneğin noktalama işaretleri ve özel karakterlerin kaldırılması.
+	Metin Normalleştirme:	
    +	Metinde normalleştirme, yinelenen boşluklar, büyük harfler, özel karakterler, sayılar, kısaltmalar, tarih biçimleri, yazım yanlışları ve nadir kelimeler gibi unsurları düzenleyerek metnin tutarlı bir biçimde işlenmesine yarar.
+	Gövdeleme ve Kök Bulma:
    +	Kelime gövdeleme, metindeki kelimelerden ekleri çıkararak temel kökleri elde etmeyi sağlayan bir işlemdir
+	Önemi Olmayan Kelimeler:
    +	Metin ön işleme adımında, metindeki yaygın ancak içerik açısından önemsiz kelimelerin çıkarılması, analizde daha odaklı ve anlamlı bir içerik elde etmeyi sağlar.
+	Metin Öznitelik Çıkarımı:
    +	Metin ön işleme tamamlandıktan sonra öznitelik çıkarımı, metinden özellik veya değişkenler elde etme sürecini ifade eder.
+	Kelime Çantası Modeli
    +	Kelime çantası modeli, belirli bir belgedeki kelimelerin varlığını ifade eden, terim sayıları gibi özelliklerle açıklanan metnin bir temsili olarak bilinen kelimelerden oluşan bir modeldi
+	TF-IDF Yöntemi:
    +	TF-IDF, bir terimin bir belgedeki önemini ölçmek için kullanılan istatistiksel bir yaklaşımdır; Terim Frekansı, bir terimin belgedeki sıklığını gösterirken, Ters Belge Frekansı, bu terimin tüm belgeler içindeki nadirliğini ifade eder.
+	Kelime Gömme:
    +	Kelime gömme yöntemleri, kelimeleri vektör temsilleriyle ifade eden tekniklerdir; Word2Vec, Google destekli sinir ağı tabanlı kelime temsil yöntemidir, CBoW ve Skip-gram gibi iki yaklaşım içerir ve bu yöntemler, farklı anlamları olan kelimelerin çoklu anlamlarını yakalamada faydalı olabilir.

# NLP'nin Sosyal Medya Analizi ve Duygu Analizi Üzerindeki Etkileri
Büyük firmalarda kararlar alınırken, reklam verirken toplumun ne istediğini, verdikleri tepkileri bilmek isterler. Popüler sosyal medya uygulamalarında yapılan yorumlar doğal dil işleme yöntemleri ile analiz edilir. Bu analiz sonucunda toplumun genel tepkisini, beğenisini veya hoşnut olmadığı durumlar analiz edilerek şirket politikaları bu yönde iyileştirilir. Bu sayede kâr marjı arttırılmış olur [[3]](https://www.karel.com.tr/blog/dogal-dil-isleme-nlp-natural-language-processing-nedir).

+	Duygu Analizi
    +	Metinleri inceleyerek duygusal içeriği ortaya çıkarmak için doğal dil işleme kullanılır. Metinlerde bulunan olumlu veya olumsuz ifadeler tespit edilerek duygusal analiz yapılır. Bu da şirket adımlarının nasıl atılacağına fikir verir.
+	Müşteri Deneyimi
    +	Sosyal medya uygulamalarında kullanıcı yorumları doğal dil işleme yöntemleri ile analiz edilir. Bu analiz sonucunda deneyimi iyileştirmeye yönelik adımlar atılır. Uygulanan strateji üzerinde değişikliklere gidilebilir.
+	Trend Analizi
    +	Sosyal medya uygulamalarında kullanıcıların yeni trendi konuştuğu veriler doğal dil işleme yöntemleri ile analiz edilerek o an hangi trend popüler ise şirket o trende yönelik reklamları arttırma, fiyat değişikliği gibi adımlar atabilir.
+	Toplumsal Analiz
    +	Doğal dil işleme toplumun bahsettiği konular üzerinde analiz yaparak toplumun düşünce ve davranışlarını analiz edebilir. Bu sayede toplumsal sorunların çözümü, sorunların anlaşılması gibi konularda fikir verebilir.


# Sesli Asistanlar ve Konuşma Tanıma Teknolojileri
Doğal dil işleme, sesli asistanların çalışmasında temel bir rol oynar. Kullanıcının sesli komutlarını metne dönüştürme, anlama ve sonuç olarak doğru yanıtları üretme süreçlerinde doğal dil işleme teknikleri büyük önem taşır. Bu tekniklerin başarılı bir şekilde bir araya getirilmesi, etkili ve kullanışlı mobil sanal asistanlarının geliştirilmesinde kritik bir faktördür. Bunun örneklerini Siri, Alexa gibi sesli asistanlarda görebiliriz. Bu asistanlar söylediklerimizi dinler, anlar ve ona göre harekete geçerler. 

İlk adım olarak kullanıcının konuşmasını dinleyip metine dönüştürürler. Bu metin doğal dil işleme yöntemleri kullanılarak anlamlandırılır ve kullanıcının ne demek istediği anlaşılır. Bu işlem tamamlandıktan sonra ilgili isteği yerine getirebilmek için veri kaynaklarına başvurulur. Bu istek gerçekleştirildikten sonra yanıt oluşturulur ve işlem tamamlanmış olur.


# Finans Sektöründe NLP Kullanımı
Doğal dil işleme yöntemleri finans sektöründe verimliliği ve müşteri memnuniyetini artırabilir, risk yönetimini genişleterek zarar oranlarını azaltabilir ve karar alma süreçlerini iyileştirebilir. Veri yoğunluğu ve çeşitliliği yüksek olan bu alanda doğal dil işlemenin sunduğu analitik yeteneklerden önemli ölçüde faydalanılabilir. Bu nedenle, finans sektöründe doğal dil işleme teknolojilerinin kullanımı çok önemlidir.

+	Rapor Taleplerinin İşlenmesi
    +	Finans sektöründe kullanılan raporlar genellikle karmaşıktır. Doğal dil işleme yöntemleri ile rapor taleplerinin içeriğini anlamak, sınıflandırmak ve bu talepleri etkili bir şekilde işlemek için kullanılabilir. Bu, finansal kurumların talepleri hızlı ve doğru bir şekilde ele almasına yardımcı olur. Bu sayede insan gücünden ve bu nedenli oluşabilecek, gözden kaçabilecek durumlardan kaçınılmış olur [[4]](https://acikerisim.sakarya.edu.tr/handle/20.500.12619/98832).
+	Müşteri Hizmetleri ve İletişim
    +	Finansal kurumlar müşteri hizmetleri süreçlerinde doğal dil işleme tekniklerini kullanarak müşterilerle etkileşimi geliştirebilir. Buna örnek olarak web sitelerinde bulunan otomatik çalışan mesajlaşma botları veya otomatik yanıtlama sistemleri verilebilir. Bu otomatik çalışan uygulamalar sayesinde müşteri taleplerini anlama ve yanıtlama konusunda doğal dil işleme teknolojilerini kullanır. Yine aynı şekilde insan gücüne olan ihtiyaç azalır, işlemler hızlanır.
+	Risk Yönetimi
    +	Finans sektörü riskleri değerlendirme ve yönetme konusunda doğal dil işleme tekniklerinden faydalanabilir. Özellikle büyük veri setleri üzerinde duygu analizi gibi doğal dil işleme yöntemleri uygulanarak müşteri duygu, düşünceleri ve piyasa trendlerini anlama konusunda önemli ipuçları sağlayabilir. Bu gelen geri bildirimler sayesinde risk oranı düşürülebilir.
+	Piyasa Analizi
    +	 Finans kuruluşları haber metinlerinden, sosyal medya paylaşımlarından veya diğer metin kaynaklarından elde edilen bilgileri analiz etmek için doğal dil işleme yöntemlerini kullanabilir. Bu analizler sayesinde piyasa trendlerini, hisse senedi performans değerlendirmesi veya yatırım fırsatlarını değerlendirmede yardımcı olabilir. Bu sayede açıp tek tek grafik okumaktan, sürekli gündemi takip etmekten sıyrılmış oluruz.


# Doğal Dil İşleme Alanındaki Gelecekteki Trendler
Doğal Dil İşlemenin geleceği yeni teknolojik zorluklarla karşılaşması ve daha kullanıcı dostu sistemler oluşturma talebiyle yeniden şekillenmeye doğru gidiyor. Mevcut doğal dil işleme tabanlı şirketler arasında her geçen gün rekabet artıyor. Bunun nedeni yazılım dünyasında her geçen günün önemi ve aklınızdaki fikrin belki de ertesi gün piyasa sürülme ihtimali. Bunun yanı sıra doğal dil işlemenin açık kaynaklı geliştirilme durumu ortaya çıktığından dolayı geleceği yönünden hızlı bir ivme kazanması da muhtemel durumlar arasındadır. Çünkü bu iş ile ilgilenen kalabalık bir topluluğu arkasına alıp geliştirme süreçlerine böyle devam etme karar alan bir şirket olursa sektörde dev haline gelebilir [[5]](https://ieeexplore.ieee.org/abstract/document/6678407).

Gelecekteki potansiyeli belki de kullanıcıdan metin, ses gibi girdi almadan ne düşündüğünü sinyaller ile alarak aklından sormak istediği soruyu anlayıp, cevap üretip bunu kullanıcıya bir ekrandan vermek yerine direkt olarak beynine sinyal olarak gönderilip anlamasını sağlamak gibi olaylar olabilir. 

![](https://blog.tryamigo.com/wp-content/uploads/2023/03/factual-accuracy.jpg)
> Şekil 1.1 [[6]](https://blog.tryamigo.com/gpt-4-vs-gpt-3-how-much-better-is-gpt-4/)

GPT-V2, GPT-V3 ve GPT-4, büyük dil modelleri alanındaki önemli gelişmelerdir. Bu modeller arasında çıkış tarihi olarak ortalama 2 sene bulunmaktadır ve GPT ilk 2018 tarihinde duyuruldu ve bu zamana kadar geçen sürede bu denli gelişmesi doğal dil işlemenin tarihsel açıdan ne kadar hızlı geliştiğini açıklamaktadır. Bu modeller ilk zamanlarında çıkmasına oranla şu andan itibaren gelişmesi daha kolay olacaktır çünkü ilk çıktığı tarihte bu alanda bilinin bilgi az, doğal dil işleme alanında yapılmış çalışmalar az bu sebeplerden dolayı şu an elde edilen bilgiler ışığında önümüzdeki 5 yıl içerisinde ne kadar gelişebileceği pekte tahmin edilebilir bir şey değildir.

# NLP Uygulamalarının Karşılaştığı Teknik Zorluklar
Doğal dil işleme uygulamalarının karşılaşabileceği teknik zorluklarla genellikle verinin kalitesi, dilin karmaşıklığı, işlem gücü gereksinimleri, dilin anlaşılması gibi alanlarda ortaya çıkabilir. Bu zorluklar doğal dil işleme adımlarını yavaşlatan adımlardır. Bu nedenle veri olarak makale, teknik anlamda imla kurallarına uyulmuş yazılar almak sosyal medya platformlarından veri almaya göre daha mantıklı olacaktır. Sosyal medyada kullanılan günlük konuşma dili, kullanılan lakaplar, kısaltmalar temiz veri sınıfına girmediği için anlaşılması zordur.

+	Veri Kalitesi ve Miktarı 
    +	Veri doğal dil işleme modellerinin eğitilmesi için hayati öneme sahiptir. Veri setlerinin kalitesi ve miktarı genellikle bir zorluk olabilir. Özellikle spesifik alanlarda (tıp) uzmanlaşmış veri setleri bulmak zor olabilir. Ayrıca çok az veya dengesiz veri setleri model performansını olumsuz etkileyebilir. Bunun dışında bulunan veri setinin temiz veri olması, kalabalık veri olması halinde veri ön işleme adımında bize zorluk yaratmaması gereklidir.
+	Anlambilim Zorlukları
    +	Doğal dilin karmaşıklığı, metinlerdeki çift anlamlılıklar, ironi, argo, dilin özellikleri gibi faktörler, doğal dil işleme modelleri için anlamı çözme ve dilin yapısını anlama konusunda zorluklar yaratabilir. Bu da işlem süresini uzatabilir, doğruluk oranını düşürebilir.
+	Etik ve Önyargılar
    +	Doğal dil işleme modelleri eğitim veri setlerindeki önyargıları ve ayrımcılığı öğrenebilir ve yansıtabilir. Bu durum, metinleri olumsuz bir şekilde etkileyebilir ve modelin objektifliğini veya tarafsızlığını sorgulatabilir. Bu nedenle eğiteceğimiz modelin veri setini ezberlememesi önemlidir. Tek bir futbol takımını tutacak veri setiyle öğrettiğimiz model test aşamasında başka bir takım için taraflı bir şekilde konuşabilir.
+	Sınırlı Anlama Yeteneği
    +	Doğal dil işleme modelleri gerçek dünyadaki karmaşık konuları anlamakta bazen yetersiz kalabilir. Özellikle aşırı spesifik veya görece nadir olan konular hakkında bilgi eksikliği yaşayabilirler. Buna sadece bir yöreye özgü olan bir kelimenin anlamını sorduğumuzda anlamsız cevap vermesi örnek olarak verilebilir.
+	Metinlerdeki Düzensizlik
    +	Doğal dildeki metinlerde yazım hataları, dilin konuşma sürdürülürken kullanılan hali gibi düzensizlikler, modellerin anlama yeteneklerini zorlayabilir. Buna ses verisi için eğiteceğimiz modele ses verisi olarak sadece Karadeniz bölgesinden toplanan ses verisi kullandığında, başka bölgedeki konuşmaları anlamaması örnek olarak verilebilir. Veriler tutarlı olmalıdır.

# Kaynakça
+ [1] [https://aws.amazon.com/tr/what-is/nlp/](https://aws.amazon.com/tr/what-is/nlp/)
+ [2] [https://miuul.com/not-defteri/dogal-dil-islemede-temel-kavramlara-hizli-bir-bakis](https://miuul.com/not-defteri/dogal-dil-islemede-temel-kavramlara-hizli-bir-bakis)
+ [3] [https://www.karel.com.tr/blog/dogal-dil-isleme-nlp-natural-language-processing-nedir](https://www.karel.com.tr/blog/dogal-dil-isleme-nlp-natural-language-processing-nedir)
+ [4] [https://acikerisim.sakarya.edu.tr/handle/20.500.12619/98832](https://acikerisim.sakarya.edu.tr/handle/20.500.12619/98832)
+ [5] [https://ieeexplore.ieee.org/abstract/document/6678407](https://ieeexplore.ieee.org/abstract/document/6678407)
+ [6] [https://blog.tryamigo.com/gpt-4-vs-gpt-3-how-much-better-is-gpt-4/](https://blog.tryamigo.com/gpt-4-vs-gpt-3-how-much-better-is-gpt-4/)

