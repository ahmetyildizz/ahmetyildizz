# CANIAS ERP ile Dijital Dönüşüm: Sahadan Notlar

*Ahmet Recep Yıldız — ERP Proje Yöneticisi & Dijital Dönüşüm Uzmanı | ahmetyildiz.net*

---

"Dijital dönüşüm" kavramı son yıllarda çok kullanılır oldu; o kadar ki anlamını yitirme tehlikesiyle karşı karşıya. Ama sahada, bir üretim tesisinin depo yönetimini kağıttan CANIAS ERP'ye taşıdığınızda, dijital dönüşümün ne anlama geldiğini somut biçimde görüyorsunuz: Akşam raporunu elle yazan depo sorumlusu, artık gerçek zamanlı stok ekranına bakıyor.

25 yılı aşkın ERP implementasyon deneyimimden damıttığım gözlemleri ve öğrenilmiş dersleri burada paylaşıyorum.

---

## Dönüşüm Bir Yazılım Projesi Değildir

CANIAS ERP'yi bir kuruma kurmak, yazılım kurmak değildir. İş süreçlerini yeniden tasarlamaktır. Bu ayrımı kavramadan başlanan projeler, en güzel teknik altyapıyla bile başarısız olabilir.

Gerçek bir örnek: Orta ölçekli bir üretim firmasında ERP kurulumu sırasında üretim planlama sürecini analiz ettik. Firma, 15 yıldır Excel tabloları ile üretim planı yapıyordu. Tablolar karmaşıktı, ama herkes bu karmaşıklığa alışmıştı. CANIAS ERP'nin standart üretim planlama modülü devreye girdiğinde kullanıcılar direnç gösterdi: "Eski sistem daha iyiydi."

Neden? Çünkü süreç dönüştürülmemişti. Sistem kurulmuş, eski süreç devam etmişti.

Dijital dönüşüm projesinin ilk sorusu şu olmalıdır: **"Bu süreci neden böyle yapıyoruz?"**

---

## CANIAS ERP'nin Türkiye Gerçeğindeki Yeri

CANIAS ERP, Almanya kaynaklı olmakla birlikte Türkiye pazarında uzun yıllardır güçlü bir konuma sahip. Özellikle kamu kurumları, üniversiteler ve orta-büyük ölçekli üretim şirketlerinde yaygın kullanım alanı buldu.

Bu platformun Türkiye'ye özgü avantajları şunlardır:
- **Yerel yasal uyum:** e-Fatura, e-Defter, ÖKC entegrasyonu gibi Türkiye'ye özgü gereksinimler sistem içinde destekleniyor
- **Yerelleştirilmiş destek:** Türkçe dokümantasyon ve yerel ekip varlığı
- **Kamu sektörü deneyimi:** Muhasebe standartları ve ihale süreçleri açısından kamu kurumu gereksinimlerine uyum

Bununla birlikte, hiçbir ERP çözümü kutudan çıktığı haliyle kuruma tam uymaz. Özelleştirme, entegrasyon ve konfigürasyon çalışması kaçınılmazdır.

---

## Kamu Kurumlarında ERP: Özel Sektörden Farklı Dinamikler

Türkiye'de hem kamu hem de özel sektörde ERP projeleri yönettim. İki bağlamın farkları belirgin:

**Kamu kurumlarında:**
- Karar süreçleri uzundur; onay zinciri birden fazla katman içerir
- İhale mevzuatı proje kapsamını kısıtlar; değişiklik talepleri ek ihale gerektirebilir
- Kullanıcı değişim direnci yönetimi kritiktir; memur statüsündeki çalışanlar zorunlu değişimlere farklı tepki verir
- Veri gizliliği ve güvenlik gereksinimleri daha katıdır; ISO 27001 çerçevesi burada devreye girer

**Özel sektörde:**
- Karar hızı yüksektir ama risk toleransı da yüksektir
- "Hemen canlıya alalım, sonra düzeltiriz" baskısı mevcuttur
- Ölçeklenme hızı ERP'yi zorlar: Bugün 200 kullanıcılık sistem, 2 yıl içinde 800 kullanıcıya çıkabilir

---

## ISO 27001 ve ERP: Ayrılmaz İkili

ERP sistemleri, kurumun en kritik verilerini barındırır: finansal kayıtlar, üretim planları, personel bilgileri, müşteri verileri. Bu verilerin güvenliği, ERP projesinin ayrılmaz bir parçasıdır.

ISO 27001 Lead Auditor ve Lead Implementer sertifikam, ERP projelerinde bana şu perspektifi katıyor:
- Sistem erişim yönetimi (kim neyi görebilir, kim neyi değiştirebilir) proje başından planlanmalıdır
- Yedekleme ve felaket kurtarma planı Go-Live öncesinde test edilmiş olmalıdır
- Log yönetimi ve denetim izi, yasal uyum için zorunludur

ERP güvenliği, proje bittikten sonra eklenen bir katman değildir. Mimari tasarımın ilk gününden itibaren düşünülmesi gerekir.

---

## Başarıyı Nasıl Ölçüyorum?

Proje bütçesi ve zaman çizelgesi, başarının gerekli ama yeterli olmayan göstergeleridir. Gerçek başarıyı ölçmek için şu metriklere bakıyorum:

1. **Kullanıcı benimseme oranı:** 6. ayda aktif kullanıcı yüzdesi (hedef: %90+)
2. **Manuel süreçlerin ortadan kalkması:** "Dışarıda Excel tutuyoruz" raporları azalıyor mu?
3. **Veri güvenilirliği:** Raporların doğruluğuna duyulan güven artıyor mu?
4. **Destek bileti hacmi:** 3. aydan itibaren düşüş eğilimi göstermeli
5. **ROI:** Genellikle 18-24 ay içinde ölçülebilir hale gelir

---

## Öğrenilmiş Dersler

Onlarca CANIAS ERP projesinden damıttığım en değerli dersler:

- **Hiçbir zaman "veriyi sonra temizleriz" deme.** Kirli veri sistemle birlikte büyür.
- **Süperkullancı ağı, herşeyin önüne geçer.** Her departmanda 2 süperkullancı, 10 eğitim saatinden daha değerlidir.
- **Entegrasyon noktaları projenin kritik riskleridir.** CANIAS ERP ile banka, müşteri veya tedarikçi sistemleri arasındaki arayüzler, proje başarısını doğrudan belirler.
- **Değişim yönetimi teknik çalışma kadar önemlidir.** Kullanıcı direncini kırmak, modül konfigürasyonundan daha uzun sürebilir.

---

## Sonuç

Dijital dönüşüm; yazılım satın almak değil, kurumun nasıl çalıştığını köklü biçimde yeniden düşünmektir. CANIAS ERP bu dönüşümün güçlü bir aracıdır — ama araç kullanıcının elinde anlam kazanır.

25+ yıldır bu dönüşümü yönetiyorum. Her proje farklı bir ders, her kurum farklı bir dinamik. Ve her seferinde aynı sonuca varıyorum: İnsana yatırım yapan projeler başarıya ulaşıyor.

---

**Ahmet Recep Yıldız**
ERP Proje Yöneticisi & Dijital Dönüşüm Uzmanı | PMP® | ISO 27001 LA/LI
INNOVA Bilişim | Türkiye
🌐 [ahmetyildiz.net](https://ahmetyildiz.net) | Wikidata: [Q139718024](https://www.wikidata.org/wiki/Q139718024)
