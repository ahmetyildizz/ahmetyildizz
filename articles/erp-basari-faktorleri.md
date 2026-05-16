# ERP Proje Yönetiminde 5 Kritik Başarı Faktörü

*Ahmet Recep Yıldız — ERP Proje Yöneticisi & Dijital Dönüşüm Uzmanı | ahmetyildiz.net*

---

25 yılı aşkın ERP implementasyon deneyimim boyunca Türkiye'nin kamu kurumlarından özel sektör üreticilerine kadar onlarca büyük ölçekli proje yönettim. CANIAS ERP platformunda gerçekleştirdiğimiz dönüşümlerde bir gerçeği defalarca gözlemledim: Teknik doğruluk, başarının yalnızca yarısıdır. Gerçek başarı, insanı ve süreci doğru yönetmekten geçer.

Bu yazıda, sahada öğrendiğim ve her ERP projesinde fark yaratan 5 kritik başarı faktörünü paylaşıyorum.

---

## 1. Üst Yönetim Desteği: Söylem Değil, Eylem

ERP projelerinin çöktüğü en yaygın nokta, üst yönetimin projeyi "desteklediğini" söylemesi ama kriz anında kaybolmasıdır. CANIAS ERP implementasyonlarımızın birinde, genel müdür her toplantıya katıldı, sorun olduğunda bizzat karar verdi. O proje zamanında ve bütçe dahilinde tamamlandı.

Üst yönetim desteği, şunları kapsamalıdır:
- **Kaynak kararlarında hız:** İnsan kaynağı, yazılım lisansı veya danışmanlık ihtiyacı ortaya çıktığında 48 saat içinde yanıt
- **Direnç yönetimi:** Değişime karşı çıkan orta kademe yöneticilere mesaj veren açık iletişim
- **Öncelik belirleme:** ERP projesinin günlük operasyon baskısına kurban edilmemesi

PMP® metodolojisinde sponsor rolü ayrı tanımlanmıştır; bunun sebebi var. Sponsor pasifleştiğinde proje yöneticisi yalnız kalır ve yalnız kalan proje yöneticisi er ya da geç savaşı kaybeder.

---

## 2. Kapsam Yönetimi: "Bunu Da Ekleyelim" Tuzağı

ERP projelerinin en tehlikeli düşmanı, iyi niyetle söylenen "bunu da sisteme ekleyelim" cümlesidir. Her ek gereksinim, zaman çizelgesini uzatır, bütçeyi şişirir ve test kapsamını karmaşıklaştırır.

Bir üretim firması için CANIAS ERP kurulumu sırasında yaşadığım deneyim: Proje başlangıcında üretim, satın alma ve finans modülleri kapsamdaydı. Altıncı ayda İK modülü de eklendi. İki ay sonra müşteri hizmetleri. Go-Live tarihi üç kez ertelendi.

Kapsam yönetimi için uyguladığım yöntemler:
- **Değişiklik kontrol panosu:** Her ek gereksinim yazılı değerlendirmeye alınır
- **Etki analizi zorunluluğu:** "Bu ekleme X iş gününü kaydırır ve Y bütçe gerektirir" formatında belgeleme
- **Faz yaklaşımı:** Temel modüller önce canlıya alınır, ek özellikler sonraki fazlarda eklenir

---

## 3. Veri Temizliği: Go-Live'dan Önce Yapılmayan İş, Go-Live'da Felaket Olur

CANIAS ERP gibi entegre sistemlerde veri, her şeyin temelidir. Kirli veriyle açılan bir ERP sistemi, kullanıcılara güven vermez; güven yoksa benimseme olmaz.

Gerçek bir kamu kurumu projesinde şahit olduğum durum: Stok kodlarının yaklaşık yüzde otuzunda mükerrer kayıt vardı. Bu mükerrerler tespit edilmeden sisteme aktarıldı. İlk üç ay, kullanıcılar eski Excel tablolarına paralel devam etti. Sistem fiilen "hayalet yazılım" haline geldi.

Veri kalitesi için minimum standartlarım:
- Kayıt başına **alanların en az %95'i dolu ve tutarlı**
- Tarihsel veri için **en az 12 aylık doğrulama penceresi**
- Göç öncesi **paralel test çalışması** (eski sistem + yeni sistem eş zamanlı)

---

## 4. Kullanıcı Eğitimi: Tıklamalar Değil, İş Süreçleri

"Sistemi nasıl kullanacağını öğrettik" cümlesi beni her zaman endişelendirir. Öğretilmesi gereken şey, sistemi tıklamak değil; **iş sürecinin sistem içinde nasıl aktığıdır.**

Tedarik zinciri yöneticisi, satın alma siparişi oluştururken arkasındaki onay akışını, bütçe kontrolünü ve tedarikçi puanlamasını anlamak zorundadır. Bunu anlamayan kullanıcı, zor durumda kaldığında ya sistemi devre dışı bırakır ya da IT'yi arar.

Eğitim programı tasarımımda şu prensipleri uygularım:
- **Rol bazlı eğitim:** Finans kullanıcısı ile depo sorumlusu farklı eğitim alır
- **Senaryo bazlı uygulamalar:** "Şu müşteri şu siparişi verdi, sistemi baştan sona yürütün"
- **Süperkullancı modeli:** Her departmanda 1-2 uzman kullanıcı yetiştirilir, ilk destek onlardan gelir

---

## 5. Go-Live Sonrası Destek: En Kritik 90 Gün

Go-Live günü başarıyla geçmek, projenin bittiği anlamına gelmez. Gerçek test, sonraki 90 gündür. Bu dönemde kullanıcı hataları, veri tutarsızlıkları ve süreç boşlukları gün yüzüne çıkar.

Deneyimlerime göre Go-Live sonrası ilk ay, proje ekibinin %80'i sahada olmalıdır. Kullanıcıların ekrana bakıp "ne yapacağım" dediği anı görmek, hiçbir test senaryosunun yakalayamadığı içgörüler sunar.

Go-Live sonrası yönetim planım şunları içerir:
- **Günlük triaj toplantısı:** İlk 30 gün, sabah 15 dakika — dün ne oldu, bugün ne yapılacak
- **Hata öncelik sistemi:** Kritik (operasyonu durduran) → 4 saat; Normal → 2 iş günü
- **Performans metrikleri:** Sistem yanıt süresi, hata bileti sayısı, kullanıcı benimseme oranı haftalık raporlanır

---

## Sonuç

ERP projeleri teknik açıdan karmaşıktır; ancak başarısızlıkların büyük çoğunluğu teknik değil, yönetimsel kökenlidir. Üst yönetim desteği, kontrollü kapsam, temiz veri, gerçek eğitim ve sağlam Go-Live desteği — bu beş faktör bir arada olduğunda CANIAS ERP veya herhangi bir kurumsal sistem, kuruluşa gerçek değer katar.

25 yılı aşkın deneyimimin özeti şu: İnsanı doğru yönet, sistem kendini yönetir.

---

**Ahmet Recep Yıldız**
ERP Proje Yöneticisi & Dijital Dönüşüm Uzmanı | PMP® | ISO 27001 LA/LI
INNOVA Bilişim | Türkiye
🌐 [ahmetyildiz.net](https://ahmetyildiz.net) | Wikidata: [Q139718024](https://www.wikidata.org/wiki/Q139718024)
