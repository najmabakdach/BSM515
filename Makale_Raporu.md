Software Metric Based Impact Analysis of Code Smells – A Large Scale Empirical Study

Ders: BSM515 – Nesneye Dayalı Programlama Dilleri
Makale Yazarları: Md. Masudur Rahman, Abdus Satter, Md. Mahbubul Alam Joarder, Kazi Sakib
Dergi: Software: Practice and Experience
Yayın Yılı: 2025
DOI: 10.1002/spe.3405

1. Makalenin Konusu, Amacı ve Araştırma Soruları

1.1. Makalenin Konusu

Bu raporda, Rahman ve arkadaşları tarafından 2025 yılında yayımlanan “Software Metric Based Impact Analysis of Code Smells – A Large Scale Empirical Study” başlıklı akademik makale incelenmektedir.

Makale, nesneye dayalı yazılım sistemlerinde ortaya çıkan kod kokuları (Code Smells) ile yazılımın iç kalite metrikleri (Internal Software Metrics) arasındaki ilişkileri ele almaktadır.

Kod kokuları, yazılımın tasarımında veya kod yapısında bulunabilecek sorunlara işaret eden belirtilerdir. Bu belirtiler her zaman doğrudan bir yazılım hatası anlamına gelmemekle birlikte, kodun anlaşılmasını, değiştirilmesini ve bakımını zorlaştırabilecek yapısal problemlerin göstergesi olabilir.

Kod kokularının tespit edilmesi, yazılım kalitesinin değerlendirilmesi açısından önemlidir. Ancak bütün kod kokuları yazılım metrikleriyle aynı düzeyde ilişkili değildir. Bu nedenle yalnızca kod kokularının varlığını belirlemek yeterli olmayabilir.

İncelenen çalışma, farklı kod kokularının yazılımın iç kalite metrikleriyle ilişkilerini analiz ederek bakım süreçlerinde hangi kod kokularına öncelik verilmesi gerektiğini araştırmaktadır.

1.2. Makalenin Amacı

Araştırmanın temel amacı, kod kokuları ile yazılımın iç kalite metrikleri arasındaki ilişkileri incelemek ve bu ilişkilerden hareketle bakım süreçlerinde öncelikli olarak ele alınabilecek kod kokularını belirlemektir.

Bu amaç doğrultusunda araştırmacılar, Java programlama diliyle geliştirilmiş 35 açık kaynaklı yazılım sistemini incelemişlerdir. Çalışmada 13 farklı kod kokusu türü ve 25 iç yazılım metriği kullanılmıştır.

Araştırmada bir kod kokusunun etki düzeyi, yazılım metrikleriyle gösterdiği istatistiksel korelasyon üzerinden değerlendirilmektedir. Bu nedenle çalışmada kullanılan etki kavramı, doğrudan bir neden-sonuç ilişkisini ifade etmemektedir.

Çalışma ayrıca kod kokularının görülme sıklıklarını da dikkate almaktadır. Böylece hem yazılım metrikleriyle güçlü ilişkiler gösteren hem de sistemlerde sık karşılaşılan kod kokularının belirlenmesi amaçlanmaktadır.

1.3. Araştırma Soruları

Araştırma, üç temel araştırma sorusu (Research Questions – RQ) üzerine kurulmuştur.

RQ1: Kod kokuları ile yazılım metrikleri arasındaki ilişki nedir?

Bu araştırma sorusu, farklı kod kokularının hangi yazılım metrikleriyle daha güçlü ilişkiler gösterdiğini belirlemeyi amaçlamaktadır.

Araştırmacılar, kod kokuları ile yazılım metrikleri arasındaki korelasyonları inceleyerek her kod kokusuyla ilişkili metrik gruplarını belirlemeyi hedeflemektedir.

Bu analiz, belirli kod kokularının hangi iç kalite özellikleriyle daha yakından ilişkili olduğunu anlamaya yardımcı olmaktadır.

RQ2: Etki düzeyi yüksek kod kokuları hangileridir?

İkinci araştırma sorusu, kod kokularının yazılım metrikleriyle olan ilişkilerine göre etki düzeylerinin belirlenmesini amaçlamaktadır.

Bu kapsamda kod kokuları üç grupta değerlendirilmektedir:

* Yüksek etki düzeyi (High Impact)
* Orta etki düzeyi (Moderate Impact)
* Düşük etki düzeyi (Low Impact)

Bu sınıflandırma, yazılım bakım ve yeniden düzenleme (Refactoring) süreçlerinde kod kokularının önceliklendirilmesine yardımcı olmayı hedeflemektedir.

RQ3: Sık karşılaşılan ve etki düzeyi yüksek kod kokuları hangileridir?

Üçüncü araştırma sorusu, kod kokularının etki düzeyleri ile görülme sıklıklarını birlikte değerlendirmektedir.

Bir kod kokusunun yazılım metrikleriyle güçlü bir ilişki göstermesi, tek başına bakım sürecinde en yüksek önceliğe sahip olması gerektiği anlamına gelmeyebilir. Çünkü bazı kod kokuları yüksek etki düzeyine sahip olmasına rağmen sistemlerde nadiren görülebilir.

Bu nedenle araştırmacılar, hem yüksek etki düzeyine sahip hem de sık karşılaşılan kod kokularını belirlemeyi amaçlamaktadır.

Böylece yazılım bakım faaliyetlerinde önceliklendirme kararlarının daha sistematik biçimde verilmesi hedeflenmektedir.

1.4. Araştırmanın Genel Yaklaşımı

Araştırmada öncelikle kod kokuları ile yazılım metrikleri arasındaki ilişkiler incelenmektedir. Daha sonra bu ilişkiler kullanılarak kod kokularının etki düzeyleri belirlenmektedir.


2. Araştırma Yöntemi ve Kullanılan Teknolojiler

2.1. Araştırma Yöntemi

İncelenen makalede, kod kokuları ile yazılımın iç kalite metrikleri arasındaki ilişkileri değerlendirmek amacıyla geniş ölçekli ampirik (deneysel) bir araştırma yöntemi kullanılmıştır. Araştırma, açık kaynaklı yazılım sistemlerinden elde edilen verilerin analiz edilmesine dayanmaktadır.

Çalışma kapsamında Java programlama diliyle geliştirilmiş 35 açık kaynaklı yazılım sistemi incelenmiştir. Bu sistemlerde 13 farklı kod kokusu türü tespit edilmiş ve 25 iç yazılım metriği kullanılarak kod kokuları ile yazılımın yapısal özellikleri arasındaki ilişkiler araştırılmıştır.

Araştırma süreci temel olarak kod kokularının tespit edilmesi, ilgili dosyaların düzenlenerek bir veri kümesi oluşturulması, yazılım metriklerinin hesaplanması ve elde edilen verilerin istatistiksel yöntemlerle analiz edilmesi aşamalarından oluşmaktadır.

2.2. İncelenen Yazılım Sistemleri

Araştırmada Apache ve Eclipse ekosistemlerinden seçilen 35 açık kaynaklı Java yazılım sistemi kullanılmıştır.

Bu sistemler, farklı büyüklüklere ve uygulama alanlarına sahip olmaları nedeniyle tercih edilmiştir. İncelenen projeler arasında yazılım geliştirme ortamları, arama sistemleri, veri işleme araçları ve çeşitli yazılım altyapıları bulunmaktadır.

Örneğin ArgoUML, UML tabanlı sistem modelleme amacıyla kullanılan bir araçtır. Eclipse bir entegre geliştirme ortamı (IDE), Lucene bir arama altyapısı ve Xerces ise bir XML ayrıştırıcısıdır.

Çalışmada kullanılan sistemler toplam 172.379 sınıf, 1.345.784 metot ve 16.118.289 kod satırı içermektedir. Projelerin ortalama geçmişi ise 12,5 yıldır.

Farklı büyüklüklerde ve alanlarda geliştirilen sistemlerin incelenmesi, kod kokuları ile yazılım metrikleri arasındaki ilişkilerin daha geniş bir veri kümesi üzerinde değerlendirilmesine olanak sağlamıştır.

2.3. İncelenen Kod Kokuları

Araştırmada nesneye dayalı yazılım tasarımında karşılaşılabilen 13 farklı kod kokusu türü ele alınmıştır.

Bu kod kokuları; sınıfların büyüklüğü, metotların karmaşıklığı, veri gizleme, kalıtım ve çok biçimlilik gibi nesneye dayalı programlama kavramlarıyla ilişkili çeşitli tasarım sorunlarını temsil etmektedir.

Çalışmada incelenen kod kokuları şunlardır:

1. Anti Singleton
2. Base Class Should Be Abstract
3. Blob
4. Class Data Should Be Private
5. Complex Class
6. Large Class
7. Lazy Class
8. Long Method
9. Long Parameter List
10. Many Field Attributes But Not Complex
11. Refused Parent Bequest
12. Spaghetti Code
13. Speculative Generality

Örneğin Long Method, uzun ve karmaşık metotları; Large Class, kod satırı bakımından büyük sınıfları; Class Data Should Be Private ise veri gizleme ilkesini ihlal eden sınıfları ifade etmektedir.

Bu kod kokularının tespit edilmesi için DÉCOR adlı otomatik kod kokusu tespit aracı kullanılmıştır.

Araştırmacılar, DÉCOR aracını önceki akademik çalışmalarda kullanılmış olması ve kod kokularını tespit etmede iyi doğruluk sonuçları göstermesi nedeniyle tercih etmişlerdir.

2.4. Yazılım Kalite Metrikleri

Araştırmada kod kokularının yazılımın iç kalite özellikleriyle ilişkilerini değerlendirmek amacıyla 25 farklı yazılım metriği kullanılmıştır.

İç kalite metrikleri, yazılımın kaynak kodu üzerinden doğrudan ölçülebilen özellikleri ifade etmektedir. Çalışmada dış kalite özellikleri araştırma kapsamı dışında bırakılmıştır.

Seçilen metrikler; karmaşıklık (Complexity), bağımlılık (Coupling), uyum veya bütünlük (Cohesion), soyutlama (Abstraction), kapsülleme (Encapsulation) ve dokümantasyon (Documentation) gibi yazılım tasarımının farklı boyutlarını kapsamaktadır.

Araştırmada kullanılan bazı önemli metrikler aşağıda açıklanmıştır:

Metrik	Açıklama
LOC (Lines of Code)	Kaynak kod satırlarının sayısını ölçer.
NOM (Number of Methods)	Sınıfta tanımlanan metotların sayısını ifade eder.
CBO (Coupling Between Objects)	Bir sınıfın ilişkili olduğu diğer sınıfların sayısını ölçer.
LCOM (Lack of Cohesion in Methods)	Sınıfın metotları arasındaki uyum eksikliğini değerlendirir.
DIT (Depth of Inheritance Tree)	Bir sınıfın kalıtım ağacındaki derinliğini ölçer.
WMC (Weighted Methods per Class)	Bir sınıftaki metotların karmaşıklık değerlerinin toplamını ifade eder.
RCTC (Ratio of Comment to Code)	Yorum satırlarının kod satırlarına oranını gösterir.

Yazılım metriklerinin hesaplanmasında Understand adlı statik kod analiz aracı kullanılmıştır.

Araştırmacılar, sınıf veya dosya düzeyinde elde edilen metrik değerlerini birleştirerek analizlerini sistem düzeyinde gerçekleştirmişlerdir.

2.5. Veri Kümesinin Oluşturulması

Araştırmacılar, kod kokularının yazılım metrikleriyle ilişkilerini analiz edebilmek amacıyla özel olarak düzenlenmiş bir veri kümesi (Synthesized Dataset) oluşturmuşlardır.

Veri kümesi, 35 yazılım sisteminin her biri için 13 farklı kod kokusuna ait dosyaların ayrı klasörlerde düzenlenmesiyle hazırlanmıştır.

Bu yapı sonucunda toplam:

35 × 13 = 455 kod kokusu klasörü

oluşturulmuştur.

Veri kümesinin hazırlanması iki temel aşamada gerçekleştirilmiştir.

Birinci aşama: Kod kokularının tespit edilmesi

DÉCOR aracı kullanılarak her sistemdeki kod kokuları belirlenmiştir. Araçtan elde edilen çıktılar, ilgili dosya adlarını içeren yapılandırılmış listelere dönüştürülmüştür.

Bu işlemde, dosya adlarının otomatik olarak ayıklanması için Python betiği kullanılmıştır.

İkinci aşama: Kod kokusu dosyalarının düzenlenmesi

Araştırmacılar, belirlenen Java dosyalarını ilgili kod kokusu klasörlerine otomatik olarak kopyalamak için Bash betiği geliştirmişlerdir.

Oluşturulan klasörler ve dosya adları manuel olarak da kontrol edilmiş; eksik dosyalar ve aynı ada sahip dosyalardan kaynaklanan sorunlar giderilmiştir.

Sonuç olarak, oluşturulan veri kümesinde toplam 74.253 kod kokusu dosyası kaydı bulunmaktadır. Veri kümesinin boyutu yaklaşık 1,35 GB olarak belirtilmiştir.

Bir Java dosyası birden fazla kod kokusu içerebildiğinden, aynı dosya farklı kod kokusu klasörlerinde tekrar bulunabilmektedir. Bu nedenle veri kümesindeki toplam dosya sayısı, benzersiz Java dosyalarının sayısını ifade etmemektedir.

2.6. Veri Analizi ve İstatistiksel Yöntemler

Araştırmada kod kokuları ile yazılım metrikleri arasındaki ilişkileri belirlemek amacıyla Spearman sıra korelasyon katsayısı (Spearman’s Rank Correlation Coefficient) kullanılmıştır.

Bu yöntem, değişkenler arasındaki ilişkinin yönünü ve gücünü değerlendirmek için tercih edilmiştir. Araştırmacılar, verilerin normal dağılım göstermesinin zorunlu olmaması nedeniyle parametrik olmayan bu yöntemi kullanmışlardır.

Analiz kapsamında her kod kokusunun 35 sistemdeki görülme sıklığı hesaplanmış, ardından ilgili kod kokusunu içeren dosyalardan elde edilen yazılım metriği değerleri sistem düzeyinde birleştirilmiştir.

Böylece 13 kod kokusu ile 25 yazılım metriği arasında toplam 325 korelasyon katsayısı hesaplanmıştır.

Araştırmacılar, korelasyon katsayılarının karelerini kullanarak her kod kokusu ve yazılım metriği için ortalama ilişki gücünü temsil eden etki puanları (Impact Scores) oluşturmuşlardır.

Bu puanlara göre kod kokuları ve yazılım metrikleri yüksek (High), orta (Moderate) ve düşük (Low) etki düzeylerinde sınıflandırılmıştır.

Sınıflandırma işleminde istatistiksel çeyreklikler (Quartiles) kullanılmıştır. Ayrıca etki düzeyleri arasındaki farkları değerlendirmek amacıyla tek yönlü T-testi (One-tailed T-test) uygulanmıştır.

Araştırmanın son aşamasında ise kod kokularının 35 sistemdeki ortalama görülme sıklıkları hesaplanmış ve etki düzeyleriyle karşılaştırılmıştır.

Bu karşılaştırma sayesinde, hem yüksek ilişki gücüne sahip hem de sistemlerde sık karşılaşılan kod kokularının belirlenmesi amaçlanmıştır.

2.7. Araştırma Yönteminin Genel Değerlendirmesi

Araştırmanın yöntemsel açıdan dikkat çeken yönü, kod kokularının yalnızca tespit edilmesiyle sınırlı kalmaması ve bu kokuların yazılımın iç kalite metrikleriyle ilişkilerinin istatistiksel olarak değerlendirilmesidir.

DÉCOR ve Understand gibi mevcut analiz araçlarının kullanılması, veri toplama sürecinin sistematik biçimde yürütülmesini sağlamıştır. Python ve Bash betikleri ise büyük miktardaki dosyanın düzenlenmesini ve veri kümesinin oluşturulmasını kolaylaştırmıştır.

Bununla birlikte, kullanılan korelasyon analizi değişkenler arasındaki istatistiksel ilişkileri ortaya koymaktadır. Bu nedenle elde edilen sonuçlar, kod kokularının yazılım kalitesindeki değişimlerin doğrudan nedeni olduğunu kanıtlamamaktadır.

Ayrıca araştırmanın yalnızca Java ile geliştirilmiş açık kaynaklı sistemlere ve iç kalite metriklerine odaklanması, sonuçların farklı programlama dillerine ve yazılım kalitesinin diğer boyutlarına genellenmesi açısından dikkate alınması gereken bir sınırlılıktır.

Son aşamada ise kod kokularının görülme sıklıkları değerlendirmeye dahil edilerek bakım süreçlerinde öncelikli olabilecek kod kokuları araştırılmaktadır.

Bu yönüyle makale, yalnızca kod kokularının tespit edilmesine değil, bu kokuların yazılımın iç kalite özellikleriyle ilişkilerinin değerlendirilmesine de odaklanmaktadır.

3. Bulguların ve Sonuçların Değerlendirilmesi

Bu bölümde, Rahman ve arkadaşlarının (2025) gerçekleştirdiği araştırmanın bulguları, çalışmada belirlenen üç araştırma sorusu doğrultusunda değerlendirilmektedir. Araştırmada kod kokuları ile yazılım metrikleri arasındaki ilişkiler incelenmiş, kod kokuları etki düzeylerine göre sınıflandırılmış ve görülme sıklıklarıyla birlikte analiz edilmiştir.

3.1. RQ1 – Kod Kokuları ile Yazılım Metrikleri Arasındaki İlişkiler

Birinci araştırma sorusu kapsamında, 13 farklı kod kokusu ile 25 iç yazılım metriği arasındaki istatistiksel ilişkiler incelenmiştir.

Araştırmacılar, Spearman sıra korelasyon katsayısını kullanarak toplam 325 korelasyon değeri hesaplamışlardır. Elde edilen sonuçlar, kod kokularının yazılım metrikleriyle aynı düzeyde ilişkili olmadığını göstermiştir.

Özellikle Anti Singleton, Blob, Complex Class, Large Class, Long Method ve Long Parameter List gibi kod kokularının birçok yazılım metriğiyle güçlü ilişkiler gösterdiği belirlenmiştir.

Bu ilişkilerin özellikle yazılımın büyüklüğünü temsil eden metriklerde yoğunlaştığı görülmüştür. Number of Files (NOF), Number of Classes (NOC), Lines of Code (LOC) ve Number of Methods (NOM) gibi metrikler bu kapsamda öne çıkmaktadır.

Araştırmada 25 yazılım metriğinin 11’i yüksek, 6’sı orta ve 8’i düşük etki düzeyinde sınıflandırılmıştır.

En yüksek ortalama ilişki puanına sahip metrik, 0,093 değeriyle Number of Files (NOF) olmuştur. Buna karşılık Ratio of Comment to Code (RCTC) metriği en düşük etki düzeyine sahip metrik olarak belirlenmiştir.

Bu sonuçlar, kod kokularının özellikle yazılımın büyüklüğü ve yapısal özellikleriyle ilişkili olduğunu göstermektedir.

Bununla birlikte, korelasyon katsayılarının kod kokuları ile yazılım metrikleri arasındaki istatistiksel ilişkileri ifade ettiği unutulmamalıdır. Dolayısıyla bu sonuçlar, belirli bir metriğin artmasının doğrudan kod kokusuna neden olduğunu kanıtlamamaktadır.

3.2. RQ2 – Etki Düzeyi Yüksek Kod Kokuları

İkinci araştırma sorusu kapsamında, kod kokularının yazılım metrikleriyle olan ilişkileri kullanılarak etki puanları hesaplanmış ve kod kokuları yüksek, orta ve düşük olmak üzere üç grupta sınıflandırılmıştır.

Araştırmanın sonuçlarına göre yüksek etki düzeyine sahip beş kod kokusu belirlenmiştir:

Kod Kokusu	Etki Puanı	Etki Düzeyi
Long Method	0,86	High
Anti Singleton	0,85	High
Complex Class	0,85	High
Large Class	0,83	High
Long Parameter List	0,83	High

Bu sonuçlara göre Long Method, 0,86 etki puanıyla ilk sırada yer almaktadır.

Özellikle Long Method, Complex Class ve Large Class gibi kod kokularının yüksek etki düzeyine sahip olması, metot ve sınıf büyüklüğüyle ilişkili tasarım sorunlarının yazılım metrikleri açısından önemli olduğunu göstermektedir.

Orta etki düzeyinde Refused Parent Bequest, Spaghetti Code, Speculative Generality ve Blob kod kokuları bulunmaktadır.

Düşük etki düzeyinde ise Class Data Should Be Private, Many Field Attributes But Not Complex, Base Class Should Be Abstract ve Lazy Class yer almaktadır.

Araştırmacılar, elde edilen sınıflandırmayı dört deneyimli yazılım geliştiricisinin değerlendirmeleriyle de karşılaştırmışlardır.

Karşılaştırma sonucunda, özellikle yüksek ve düşük etki düzeyindeki kod kokularında araştırma bulguları ile uzman görüşleri arasında belirli düzeyde benzerlikler bulunduğu görülmüştür. Buna karşılık orta etki düzeyindeki kod kokularının değerlendirilmesinde daha fazla farklılık ortaya çıkmıştır.

Bu durum, geliştiricilerin kod kokularının önemini yalnızca kişisel deneyimlerine dayanarak değerlendirmelerinin her zaman yeterli olmayabileceğini göstermektedir.

Araştırmanın bu bölümündeki temel katkısı, kod kokularının önceliklendirilmesi için yazılım metriklerine dayalı sayısal bir değerlendirme yaklaşımı sunmasıdır.

3.3. RQ3 – Kod Kokularının Etki ve Görülme Sıklığı

Üçüncü araştırma sorusunda, kod kokularının etki düzeyleri ile yazılım sistemlerinde görülme sıklıkları birlikte değerlendirilmiştir.

Araştırmacılar, 35 yazılım sisteminde her kod kokusunun ortalama görülme sıklığını hesaplamışlardır.

Elde edilen sonuçlara göre en sık karşılaşılan dört kod kokusu şunlardır:

Kod Kokusu	Proje Başına Ortalama Görülme Sıklığı
Long Method	733,06
Complex Class	565,06
Long Parameter List	245,77
Large Class	231,60

Bu dört kod kokusunun hem yüksek etki düzeyine sahip olduğu hem de yazılım sistemlerinde sık görüldüğü belirlenmiştir.

Özellikle Long Method, araştırmada hem en yüksek etki puanına hem de en yüksek ortalama görülme sıklığına sahip kod kokusu olarak öne çıkmaktadır.

Buna karşılık Anti Singleton, yüksek etki düzeyine sahip olmasına rağmen orta görülme sıklığı grubunda yer almaktadır.

Benzer şekilde Refused Parent Bequest, Spaghetti Code ve Speculative Generality gibi kod kokuları orta etki düzeyine sahip olmalarına rağmen düşük görülme sıklığı göstermektedir.

Bu bulgular, kod kokularının etki düzeyleri ile görülme sıklıkları arasında her zaman doğrudan bir paralellik bulunmadığını göstermektedir.

Araştırmacılar, bakım süreçlerinde yalnızca bir kod kokusunun ne kadar sık görüldüğüne değil, yazılım metrikleriyle ne düzeyde ilişkili olduğuna da dikkat edilmesi gerektiğini vurgulamaktadır.

Bu nedenle Long Method, Complex Class, Large Class ve Long Parameter List kod kokuları, hem yüksek etki düzeyleri hem de yüksek görülme sıklıkları nedeniyle yeniden yapılandırma (Refactoring) çalışmalarında öncelikli olarak değerlendirilebilecek kod kokuları arasında yer almaktadır.

3.4. Araştırmanın Genel Sonuçları

Araştırma sonucunda, kod kokularının yazılımın iç kalite metrikleriyle farklı düzeylerde ilişkili olduğu ortaya konulmuştur.

Özellikle yazılımın büyüklüğüyle ilişkili metriklerin ve metot veya sınıf büyüklüğünü temsil eden kod kokularının araştırma bulgularında öne çıktığı görülmüştür.

Çalışmanın önemli sonuçlarından biri, bütün kod kokularının aynı öncelikle ele alınmasının gerekli olmadığını göstermesidir.

Kod kokularının etki düzeyleri ve görülme sıklıkları birlikte değerlendirildiğinde, bakım süreçlerinde daha sistematik önceliklendirme kararları verilebileceği anlaşılmaktadır.

Araştırma ayrıca geliştiricilerin kod kokularına ilişkin değerlendirmelerinin kişisel deneyimlere göre değişebildiğini göstermiştir. Bu nedenle yazılım metriklerine dayalı değerlendirmelerin, geliştiricilerin kararlarını destekleyebilecek nesnel veriler sağlayabileceği belirtilmektedir.

Bununla birlikte, çalışmada kullanılan etki puanları korelasyon analizine dayanmaktadır. Dolayısıyla araştırma sonuçları, kod kokularının yazılım kalitesindeki değişimlere doğrudan neden olduğunu veya belirli bir kod kokusunun giderilmesinin yazılım kalitesini kesin olarak artıracağını kanıtlamamaktadır.

Ayrıca araştırmanın Java ile geliştirilmiş açık kaynaklı sistemlerle ve iç yazılım metrikleriyle sınırlı olması, sonuçların farklı yazılım ortamlarına genellenmesinde dikkate alınmalıdır.

Genel olarak çalışma, kod kokularının yalnızca tespit edilmesine odaklanmak yerine, yazılım metrikleriyle ilişkilerinin analiz edilerek önceliklendirilmesine yönelik bir yaklaşım sunmaktadır.

Bu yaklaşımın, yazılım bakım faaliyetlerinin planlanmasına ve gelecekte etki düzeyine dayalı otomatik Refactoring araçlarının geliştirilmesine katkı sağlayabileceği değerlendirilmektedir.


4. Makalenin Eleştirel Değerlendirilmesi

Bu bölümde, Rahman ve arkadaşlarının (2025) gerçekleştirdiği araştırma; güçlü yönleri, yöntemsel sınırlılıkları, önceki çalışmalarla ilişkisi ve yazılım mühendisliği alanına sağladığı katkılar açısından eleştirel olarak değerlendirilmektedir.

4.1. Araştırmanın Güçlü Yönleri

Araştırmanın en önemli güçlü yönlerinden biri, geniş kapsamlı bir veri kümesi üzerinde gerçekleştirilmiş olmasıdır. Çalışmada Apache ve Eclipse ekosistemlerinden seçilen 35 açık kaynaklı Java yazılım sistemi incelenmiştir. Bu sistemlerde 13 farklı kod kokusu ile 25 iç yazılım metriği arasındaki ilişkilerin analiz edilmesi, araştırmanın kapsamını genişletmiştir.

Çalışmanın diğer bir güçlü yönü, kod kokularının yalnızca tespit edilmesine odaklanmamasıdır. Araştırmacılar, kod kokularının yazılım metrikleriyle ilişkilerini inceleyerek bakım süreçlerinde hangi kod kokularının öncelikli olarak ele alınabileceğini belirlemeye çalışmışlardır.

Araştırmada Spearman sıra korelasyon katsayısının kullanılması, değişkenler arasındaki ilişkilerin istatistiksel olarak değerlendirilmesini sağlamıştır. Ayrıca etki puanlarına dayalı bir sınıflandırma yaklaşımının benimsenmesi, kod kokularının karşılaştırılmasını kolaylaştırmıştır.

Çalışmanın dikkat çeken bir diğer yönü, istatistiksel sonuçların dört deneyimli yazılım geliştiricisinin görüşleriyle karşılaştırılmasıdır. Bu karşılaştırma, yazılım metriklerine dayalı değerlendirmeler ile geliştiricilerin deneyimlerine dayanan değerlendirmeler arasındaki benzerliklerin ve farklılıkların ortaya konulmasına katkı sağlamıştır.

Son olarak, kod kokularının etki düzeyleri ile görülme sıklıklarının birlikte değerlendirilmesi, araştırmanın uygulamaya yönelik önemini artırmaktadır. Bu yaklaşım, yazılım bakım faaliyetlerinde önceliklendirme kararlarının daha sistematik biçimde verilmesine yardımcı olabilecek bir temel sunmaktadır.

4.2. Araştırmanın Sınırlılıkları

Araştırmanın önemli sınırlılıklarından biri, yalnızca Java programlama diliyle geliştirilmiş açık kaynaklı yazılım sistemlerinin incelenmiş olmasıdır.

Java’nın nesneye dayalı programlama özellikleri, çalışmanın konusu açısından uygun bir araştırma ortamı sağlamaktadır. Ancak farklı programlama dillerinin yapısal özellikleri ve yazılım geliştirme yaklaşımları değişebileceğinden, elde edilen sonuçların diğer dillere doğrudan genellenmesi mümkün olmayabilir.

Bir diğer sınırlılık, araştırmanın yalnızca iç yazılım kalite metriklerine odaklanmasıdır. Yazılımın bakım kolaylığı, hata eğilimi ve değiştirilebilirliği gibi dış kalite özellikleri doğrudan değerlendirilmemiştir.

Bu nedenle araştırmada yüksek etki düzeyine sahip olduğu belirlenen bir kod kokusunun, gerçek yazılım bakım faaliyetlerinde aynı düzeyde olumsuz sonuçlar oluşturacağı kesin olarak söylenemez.

Araştırmanın yöntemsel açıdan dikkat edilmesi gereken bir başka yönü, etki puanlarının korelasyon analizine dayanmasıdır.

Korelasyon, iki değişken arasındaki istatistiksel ilişkinin yönünü ve gücünü gösterir. Ancak bu ilişkinin varlığı, değişkenlerden birinin diğerine neden olduğunu kanıtlamaz.

Dolayısıyla araştırmada kullanılan etki kavramı, kod kokularının yazılım kalitesine doğrudan neden olduğu değişimleri değil, yazılım metrikleriyle gösterdikleri istatistiksel ilişkileri ifade etmektedir.

Ayrıca kod kokularının tespit edilmesinde otomatik analiz araçlarının kullanılması, sonuçların kullanılan araçların tespit doğruluğundan etkilenebileceği anlamına gelmektedir.

Bu sınırlılıklar, araştırmanın sonuçlarını geçersiz kılmamakla birlikte, bulguların yorumlanmasında ve farklı yazılım ortamlarına uygulanmasında dikkate alınmalıdır.

4.3. Bulguların Önceki Çalışmalarla Karşılaştırılması

Rahman ve arkadaşlarının (2025) çalışması, kod kokularının yazılım kalitesi üzerindeki etkilerini inceleyen önceki araştırmalarla ilişkili olarak değerlendirilebilir.

Bu kapsamda Palomba ve arkadaşlarının (2018) gerçekleştirdiği geniş ölçekli ampirik araştırma önemli bir karşılaştırma noktası oluşturmaktadır.

Palomba ve arkadaşları, kod kokularının yazılımın bakım kolaylığı ve değişime veya hataya yatkınlığı gibi dış kalite özellikleriyle ilişkilerini incelemişlerdir.

Rahman ve arkadaşlarının çalışması ise kod kokuları ile iç yazılım metrikleri arasındaki ilişkilere odaklanmaktadır.

Her iki araştırmada da özellikle yazılımın büyüklüğü ve karmaşıklığıyla ilişkili bazı kod kokularının önemli olduğu görülmektedir.

Örneğin Long Method, Complex Class ve Large Class gibi kod kokuları, Rahman ve arkadaşlarının araştırmasında yüksek etki düzeyinde sınıflandırılmıştır. Bu sonuç, Palomba ve arkadaşlarının büyüklük ve karmaşıklıkla ilişkili kod kokularına yönelik bazı bulgularıyla benzerlik göstermektedir.

Bununla birlikte, iki araştırmanın sonuçları tamamen aynı değildir.

Özellikle Long Parameter List kod kokusu, Rahman ve arkadaşlarının çalışmasında yüksek etki düzeyinde değerlendirilirken, Palomba ve arkadaşlarının araştırmasında daha sınırlı bir etkiyle ilişkilendirilmiştir.

Bu farklılık, araştırmalarda kullanılan kalite göstergelerinin ve değerlendirme yöntemlerinin sonuçlar üzerinde etkili olabileceğini düşündürmektedir.

Dolayısıyla kod kokularının önemini değerlendirirken yalnızca tek bir araştırmanın sonuçlarına dayanmak yerine, farklı kalite boyutlarını inceleyen çalışmaların birlikte ele alınması yararlı olacaktır.

4.4. Kişisel Akademik Değerlendirme

Bu çalışmanın yazılım mühendisliği açısından önemli katkısı, kod kokularının değerlendirilmesinde yalnızca varlıklarının veya görülme sıklıklarının dikkate alınmasının yeterli olmayabileceğini göstermesidir.

Yazılım geliştirme süreçlerinde zaman ve kaynaklar sınırlı olduğundan, bütün kod kokularının aynı anda giderilmesi her zaman mümkün değildir. Bu nedenle bakım faaliyetlerinin belirli ölçütlere göre önceliklendirilmesi önem taşımaktadır.

Araştırmada önerilen yaklaşım, kod kokularının yazılım metrikleriyle ilişkilerini kullanarak bu önceliklendirme sürecine katkı sağlayabilecek sayısal veriler sunmaktadır.

Bununla birlikte, yalnızca korelasyon temelli etki puanlarının kullanılması, gerçek bakım maliyetlerinin ve yeniden yapılandırma işlemlerinin sonuçlarının değerlendirilmesi açısından yeterli değildir.

Bu nedenle gelecekte yapılacak araştırmalarda, kod kokularının giderilmesinden önce ve sonra yazılım metriklerinin karşılaştırılması yararlı olabilir.

Ayrıca bakım süresi, hata sayısı ve geliştiricilerin kodu anlama süresi gibi göstergelerin değerlendirmeye dahil edilmesi, elde edilen sonuçların uygulamadaki karşılığını daha açık biçimde ortaya koyabilir.

Farklı programlama dillerinde ve ticari yazılım projelerinde gerçekleştirilecek benzer çalışmalar da araştırma bulgularının genellenebilirliğini değerlendirmek açısından önemlidir.

Sonuç olarak Rahman ve arkadaşlarının (2025) çalışması, kod kokularının yazılım metrikleriyle ilişkilerinin sistematik biçimde analiz edilmesi ve bakım faaliyetlerinde önceliklendirme yapılması açısından değerli bir akademik katkı sunmaktadır.

Ancak bu yaklaşımın doğrudan yazılım kalitesini iyileştirdiğini göstermek için, yeniden yapılandırma süreçlerinin gerçek sonuçlarını inceleyen ek ampirik araştırmalara ihtiyaç bulunmaktadır.

5. Literatür Taraması ve Önceki Çalışmalar

5.1. Fowler (1999) – Refactoring: Improving the Design of Existing Code

Martin Fowler (1999), Refactoring: Improving the Design of Existing Code adlı kitabının üçüncü bölümünde, yazılım tasarımındaki olası sorunlara işaret eden 22 farklı kod kokusunu (Code Smell) ele almıştır.

Bu kod kokuları arasında Duplicated Code, Long Method, Large Class, Long Parameter List, Feature Envy, Lazy Class ve Refused Bequest gibi örnekler bulunmaktadır. Bu yapılar, kodun anlaşılabilirliğini ve bakımını zorlaştırabilecek tasarım sorunları olarak değerlendirilmiştir.

Fowler, kod kokularının doğrudan bir yazılım hatası olmadığını ve her durumda yeniden düzenleme gerektirmediğini vurgulamıştır. Bununla birlikte, uygun durumlarda Extract Method, Extract Class ve Move Method gibi yeniden düzenleme (Refactoring) teknikleriyle kod yapısının iyileştirilebileceğini açıklamıştır.

Bu çalışma, kod kokularının tanımlanması ve değerlendirilmesi açısından önemli bir kavramsal temel sunmaktadır. Ancak kod kokularının yazılım metrikleri üzerindeki etkilerini istatistiksel yöntemlerle ölçmemektedir.

Fowler’ın yaklaşımı kod kokularının tespit edilmesine ve giderilmesine yönelik tasarım ilkelerine odaklanırken, Rahman ve arkadaşlarının (2025) çalışması kod kokuları ile yazılım metrikleri arasındaki ilişkileri deneysel ve istatistiksel yöntemlerle incelemektedir. Bu nedenle Fowler’ın kitabı, incelenen makalenin teorik arka planını oluşturan temel kaynaklardan biridir.

5.2. Palomba ve Arkadaşları (2018) – Kod Kokularının Bakım Yapılabilirliğine Etkisi

Palomba ve arkadaşları (2018), On the Diffuseness and the Impact on Maintainability of Code Smells: A Large Scale Empirical Investigation adlı çalışmalarında, kod kokularının yazılım sistemlerindeki yaygınlığını ve bakım yapılabilirliği ile ilişkisini araştırmıştır.

Çalışmada, 30 açık kaynaklı Java projesinin 395 sürümü incelenmiş ve 13 farklı kod kokusuna ait, manuel olarak doğrulanmış 17.350 örnek analiz edilmiştir. Araştırmada kod kokularının değişime yatkınlık (Change-Proneness) ve hata eğilimi (Fault-Proneness) ile ilişkileri değerlendirilmiştir.

Elde edilen sonuçlar, Long Method ve Spaghetti Code gibi kod kokularının yaygın olduğunu göstermiştir. Ayrıca kod kokusu içeren sınıfların, kod kokusu içermeyen sınıflara kıyasla istatistiksel olarak anlamlı düzeyde daha yüksek değişime yatkınlık ve hata eğilimi gösterdiği belirlenmiştir.

Bununla birlikte, kod kokularının kaldırılmasının değişime yatkınlık açısından olumlu sonuçlarla ilişkili olabildiği, ancak hata eğiliminde her zaman belirgin bir azalma sağlamadığı görülmüştür. Bu nedenle araştırmacılar, kod kokularının varlığı ile yazılım hataları arasında doğrudan bir neden-sonuç ilişkisi kurulamayacağını vurgulamıştır.

Palomba ve arkadaşları (2018), kod kokularının yazılım bakım süreçleriyle ilişkisini değişiklikler ve hatalar üzerinden incelerken, Rahman ve arkadaşları (2025) kod kokuları ile iç yazılım metrikleri arasındaki istatistiksel ilişkileri analiz etmiştir. Dolayısıyla bu iki çalışma, kod kokularının yazılım kalitesi üzerindeki etkilerini farklı ölçütlerle ele alarak birbirini tamamlamaktadır.


5.3. Kaur (2020) – Kod Kokularının Yazılım Kalitesi Üzerindeki Etkilerine Yönelik Sistematik Literatür İncelemesi

Kaur (2020), kod kokuları (Code Smells) ile yazılım kalite özellikleri arasındaki ilişkiyi inceleyen deneysel araştırmaları sistematik bir literatür taraması (Systematic Literature Review – SLR) yöntemiyle değerlendirmiştir. Çalışmada, Mart 2018’e kadar yayımlanan araştırmalar altı dijital veri tabanında taranmış ve başlangıçta belirlenen 4.363 çalışma arasından seçim kriterlerini karşılayan 74 birincil çalışma ayrıntılı olarak incelenmiştir.

Araştırma kapsamında 93 farklı kod kokusu türü, 22 yazılım kalite özelliği ve 223 kalite metriği belirlenmiştir. İncelenen çalışmaların özellikle güvenilirlik (Reliability), değiştirilebilirlik (Changeability) ve bakım yapılabilirlik (Maintainability) özelliklerine odaklandığı görülmüştür. Bununla birlikte, kullanılan veri kümelerinin büyük ölçüde Java tabanlı ve açık kaynaklı projelerden oluşması, elde edilen sonuçların farklı programlama dillerine ve endüstriyel sistemlere genellenmesini sınırlandırabilecek bir unsur olarak değerlendirilmiştir.

Araştırmanın bulguları, kod kokularının yazılım kalitesi üzerindeki etkilerinin her durumda aynı olmadığını göstermektedir. God Class ve Duplicate Code türlerinin bazı kalite özellikleri üzerinde ağırlıklı olarak olumsuz etkilerle ilişkilendirildiği, Long Method ve Long Parameter List türlerine ilişkin sonuçların ise çoğunlukla tutarsız olduğu belirtilmiştir. Ayrıca bazı çalışmalarda Data Class için olumlu sonuçlar raporlanmıştır. Bu farklılıklar, kod kokularının etkilerinin yalnızca türlerine göre değil, incelenen kalite özelliğine ve kullanılan veri kümelerine göre de değerlendirilmesi gerektiğini ortaya koymaktadır.

Kaur (2020), çalışmanın geçerliliğini dört başlık altında değerlendirmiştir: yapı geçerliliği (Construct Validity), iç geçerlilik (Internal Validity), dış geçerlilik (External Validity) ve güvenilirlik (Reliability). Yapı geçerliliği kapsamında araştırmanın yazılım mühendisliği alanıyla sınırlandırıldığı ve ilgili çalışmaların altı dijital kütüphaneden toplandığı belirtilmiştir. İç geçerlilik açısından otomatik ve manuel arama yöntemleri birlikte kullanılmış; ancak manuel tarama ve tam metin yerine yayınların üst verileri üzerinden yapılan aramalar nedeniyle bazı ilgili çalışmaların gözden kaçmış olabileceği kabul edilmiştir.

Dış geçerlilik kapsamında, araştırma sonuçlarının incelenen çalışmalarla ve taramanın gerçekleştirildiği dönemle sınırlı olduğu vurgulanmıştır. Ayrıca belirlenen 22 kalite özelliğinin kapsamlı olmakla birlikte eksiksiz olmayabileceği ifade edilmiştir. Güvenilirliği artırmak amacıyla ise üç araştırmacının katkısıyla çalışma seçimi ve veri çıkarma süreçlerinde bağımsız kontroller gerçekleştirilmiş, araştırmacılar arasındaki görüş ayrılıkları ortak değerlendirmeler yoluyla giderilmiştir.

Sonuç olarak Kaur (2020), kod kokuları ile yazılım kalitesi arasındaki ilişkinin karmaşık olduğunu ve mevcut deneysel bulguların her zaman tutarlı sonuçlar üretmediğini ortaya koymuştur. Bu çalışma, Rahman ve arkadaşlarının (2025) kod kokuları ile iç yazılım metrikleri arasındaki ilişkileri geniş ölçekli deneysel veriler üzerinden inceleyen araştırmasına önemli bir literatür temeli sağlamaktadır. Özellikle kod kokularının farklı kalite metrikleri üzerindeki etkilerinin ayrı ayrı değerlendirilmesi gerektiği yönündeki bulgular, Rahman ve arkadaşlarının araştırma yaklaşımıyla ilişkilendirilebilir.

5.4. Verma ve Arkadaşları (2023)

Verma ve arkadaşları (2023), “Code Smell Prioritization in Object-Oriented Software Systems: A Systematic Literature Review” başlıklı çalışmalarında, nesne yönelimli yazılım sistemlerinde kod kokularının (code smells) önceliklendirilmesine yönelik yöntemleri sistematik olarak incelemiştir. Araştırmada, 2011–2022 yılları arasında yayımlanan 39 birincil çalışma değerlendirilmiş; kullanılan önceliklendirme teknikleri, kod kokusu türleri, değerlendirme faktörleri, sıralama formülleri, veri kümeleri ve tespit araçları karşılaştırılmıştır.

Çalışmada kod kokularını önceliklendirme yaklaşımları manuel, yarı otomatik ve tam otomatik olmak üzere üç grupta ele alınmıştır. Manuel yaklaşımların geliştirici deneyimine ve uzman değerlendirmesine dayanması nedeniyle öznel sonuçlar üretebildiği belirtilmiştir. Ayrıca incelenen çalışmalarda God Class ve Feature Envy kod kokularının sıklıkla ele alındığı, önceliklendirme sürecinde ise bileşenlerin kararlılığı ve sınıflar arasındaki bağımlılık (coupling) gibi faktörlerin önemli bir yer tuttuğu görülmüştür.

Araştırmanın bulguları, kod kokularının önceliklendirilmesinde kullanılan sıralama formüllerinin sınırlı olduğunu, değerlendirme süreçlerinin büyük ölçüde manuel yöntemlere dayandığını ve çalışmaların çoğunlukla Java tabanlı projeler üzerinde gerçekleştirildiğini ortaya koymuştur. Bu doğrultuda araştırmacılar, daha kapsamlı yazılım metriklerinin kullanılması, otomatik değerlendirme yöntemlerinin geliştirilmesi ve farklı programlama dilleri üzerinde deneysel çalışmaların artırılması gerektiğini vurgulamıştır.

Verma ve arkadaşlarının çalışması, kod kokularının yalnızca tespit edilmesinin yeterli olmadığını, bakım ve yeniden yapılandırma (refactoring) süreçlerinde hangi kod kokularının öncelikli olarak ele alınacağının da belirlenmesi gerektiğini göstermektedir. Bu yönüyle çalışma, kod kokuları ile yazılım metrikleri arasındaki ilişkilerin analiz edilmesinin, yazılım bakım kararlarını desteklemek açısından taşıdığı önemi ortaya koyan tamamlayıcı bir literatür kaynağı niteliğindedir.

6. Genel Değerlendirme ve Sonuç

Bu raporda, Rahman ve arkadaşları (2025) tarafından gerçekleştirilen “Software Metric Based Impact Analysis of Code Smells – A Large Scale Empirical Study” başlıklı araştırma incelenmiştir. Çalışmanın temel amacı, nesne yönelimli yazılım sistemlerinde kod kokuları (Code Smells) ile iç yazılım metrikleri arasındaki ilişkileri analiz ederek yazılım bakım süreçlerinde önceliklendirme kararlarına katkı sağlamaktır.

Araştırmada, 35 açık kaynaklı Java yazılım sistemi üzerinde 13 farklı kod kokusu ve 25 iç yazılım metriği değerlendirilmiştir. Kod kokularının tespit edilmesinde DÉCOR, yazılım metriklerinin hesaplanmasında ise Understand aracı kullanılmıştır. Elde edilen veriler, Spearman sıra korelasyon katsayısı yardımıyla analiz edilmiştir.

Araştırma bulguları, kod kokularının yazılım metrikleriyle farklı düzeylerde ilişkili olduğunu göstermiştir. Özellikle Long Method, Anti Singleton, Complex Class, Large Class ve Long Parameter List yüksek etki düzeyine sahip kod kokuları olarak belirlenmiştir. Bununla birlikte Long Method, Complex Class, Long Parameter List ve Large Class türlerinin incelenen sistemlerde yüksek görülme sıklığına sahip olduğu tespit edilmiştir.

Bu sonuçlar, kod kokularının yalnızca tespit edilmesinin yeterli olmadığını, bakım süreçlerinde etki düzeylerinin ve görülme sıklıklarının birlikte değerlendirilmesinin yararlı olabileceğini göstermektedir. Böylece geliştiriciler, sınırlı zaman ve kaynaklarını hangi kod kokularına öncelik vereceklerini belirlerken metrik temelli değerlendirmelerden yararlanabilirler.

Bununla birlikte, araştırmada kullanılan etki puanları istatistiksel korelasyonlara dayanmaktadır. Bu nedenle sonuçlar, kod kokularının yazılım kalitesindeki değişimlere doğrudan neden olduğunu veya belirli bir kod kokusunun giderilmesinin yazılım kalitesini kesin olarak artıracağını kanıtlamamaktadır. Ayrıca araştırmanın yalnızca Java tabanlı açık kaynaklı sistemleri ve iç yazılım metriklerini kapsaması, bulguların farklı yazılım ortamlarına genellenmesini sınırlandırmaktadır.

Gelecekte gerçekleştirilecek çalışmalarda, farklı programlama dilleri ve endüstriyel yazılım projelerinin incelenmesi, yeniden yapılandırma (Refactoring) öncesi ve sonrası kalite göstergelerinin karşılaştırılması ve bakım maliyetlerinin değerlendirmeye dahil edilmesi yararlı olabilir.

Sonuç olarak Rahman ve arkadaşlarının (2025) araştırması, kod kokuları ile yazılım metrikleri arasındaki ilişkilerin geniş ölçekli ampirik veriler üzerinden değerlendirilmesine katkı sağlamaktadır. Çalışma, nesne yönelimli yazılım sistemlerinde kod kalitesinin analiz edilmesi ve bakım faaliyetlerinin daha sistematik biçimde planlanması açısından önemli bir yaklaşım sunmaktadır.
