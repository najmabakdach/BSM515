Software Metric Based Impact Analysis of Code Smells – A Large Scale Empirical Study

Ders: BSM515 – Nesneye Dayalı Programlama Dilleri
Makale Yazarları: Md. Masudur Rahman, Abdus Satter, Md. Mahbubul Alam Joarder, Kazi Sakib
Dergi: Software: Practice and Experience
Yayın Yılı: 2025
DOI: 10.1002/spe.3405

⸻

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

Son aşamada ise kod kokularının görülme sıklıkları değerlendirmeye dahil edilerek bakım süreçlerinde öncelikli olabilecek kod kokuları araştırılmaktadır.

Bu yönüyle makale, yalnızca kod kokularının tespit edilmesine değil, bu kokuların yazılımın iç kalite özellikleriyle ilişkilerinin değerlendirilmesine de odaklanmaktadır.
