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
