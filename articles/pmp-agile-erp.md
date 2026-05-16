# PMP ve Agile'ı ERP Projelerinde Nasıl Birleştiriyorum

*Ahmet Recep Yıldız — ERP Proje Yöneticisi & Dijital Dönüşüm Uzmanı | ahmetyildiz.net*

---

"ERP projeleri Waterfall ile mi yoksa Agile ile mi yönetilmeli?" sorusu, proje yönetimi çevrelerinde yıllardır tartışılır. Kısa cevabım şu: İkisi de yeterli değildir. Doğru yaklaşım, her iki metodolojinin güçlü yönlerini birleştiren hibrit bir modeldir.

PMP® sertifikalı bir proje yöneticisi olarak ve onlarca CANIAS ERP projesinden edindiğim deneyimle, bu hibrit modeli nasıl kurduğumu ve uyguladığımı paylaşıyorum.

---

## Neden Saf Waterfall Yetmez

Geleneksel şelale (Waterfall) yaklaşımında proje aşamaları sıralı ilerler: analiz → tasarım → geliştirme → test → canlıya alma. Bu model ERP projelerinde bazı açılardan mantıklıdır: Kurumsal sistemler büyük yatırımlar gerektirir, gereksinimler genellikle önceden belirlidir ve değişiklikler maliyetlidir.

Ancak saf Waterfall şu riskleri barındırır:
- Gereksinimler proje boyunca değişir; sabitlemeye çalışmak gerçeklikten kopuştur
- Test aşamasına gelindiğinde sorunlar görülür ama artık geri dönmek çok pahalıdır
- Kullanıcı geri bildirimi ancak son aşamada alınır; o noktada değişiklik yapmak projeyi yeniden başlatmak anlamına gelir

---

## Neden Saf Agile de Yetmez

Agile yaklaşımı, yazılım geliştirme dünyasında devrim yarattı. Ancak kurumsal ERP projeleri için bazı kısıtlamaları vardır:

- ERP implementasyonlarında sprint sonunda "çalışan yazılım" teslimi her zaman mümkün değildir; modüller birbirine bağımlıdır
- Müşteri tarafı (kurum) Agile sürecine tam katılım için yeterli bant genişliğine sahip olmayabilir
- Kamu kurumlarında Agile'ın gerektirdiği sık karar alma mekanizmaları ihale mevzuatıyla çelişebilir
- "Yeterince iyidir" kültürü, ERP'nin gerektirdiği veri doğruluğu standardıyla uyumlu değildir

---

## Hibrit Model: Çerçevede Waterfall, İçeride Agile

CANIAS ERP projelerinde uyguladığım hibrit modelin temel mantığı şudur:

**Proje çerçevesi (Waterfall):**
- Proje kapsamı, bütçesi ve zaman çizelgesi başından belirlenir
- Faz geçişleri için net kontrol noktaları (milestone) tanımlanır
- Resmi değişiklik kontrol süreci işletilir

**Süreç içi yürütme (Agile):**
- Her faz içinde 2-3 haftalık sprint döngüleri uygulanır
- Her sprint sonunda kullanıcı kabul testi yapılır
- Geribildirim hızla uygulamaya alınır

Bu yaklaşımın pratikte nasıl göründüğüne bir örnekle bakalım:

**Proje:** Orta ölçekli üretim firması için CANIAS ERP — finans, satın alma ve stok modülleri
**Toplam süre:** 18 ay (Waterfall çerçevesi)
**Sprint uzunluğu:** 2 hafta (Agile içi döngü)

Finans modülü 6 aylık bir fazda planlandı. Bu 6 ay içinde 12 sprint döngüsü çalıştırıldı. Her sprint sonunda finans departmanı gerçek verilerle sistemi test etti ve geri bildirim verdi. Sprint 7'de bir sorun tespit edildi: Bütçe kontrol ekranı kullanıcıların alışkın olduğu görünümden çok farklıydı. Bunu saf Waterfall'da test aşamasında keşfetseydik, büyük bir kriz yaşardık. Agile döngüsü sayesinde 3 günde düzelttik.

---

## PMI Standartları ve PMBOK 7

PMI'ın PMBOK 7. sürümü bu hibrit yaklaşımı artık doğrudan destekliyor. "Principle-based" (ilke bazlı) yaklaşım, proje yöneticisine metodoloji seçiminde esneklik tanıyor.

PMP® sınavında ve pratikte en değerli bulduğum ilkeler:
- **Değeri önceliklendir:** Her karar, projenin nihai amacı olan iş değerine katkı açısından değerlendirilmeli
- **Bütünsel yaklaşım:** Teknik kararlar insanı, süreci ve teknolojiyi birlikte değerlendirmeli
- **Uyum kapasitesi:** Plan değişmez değildir; değişime yanıt verme hızı bir beceridir

---

## Dirençle Başa Çıkma: Kültür Değişimi

Her iki metodolojinin de en zor bileşeni insan faktörüdür. "Biz hep böyle yaptık" ifadesi, değişim yönetiminin önündeki en büyük engeldir.

Bu dirençle başa çıkmak için kullandığım teknikler:

**1. Erken kazanımlar (Quick wins):** İlk sprintte en çok şikayet edilen küçük bir sorunu çöz. Kullanıcılar "bu sistem bizi dinliyor" diye düşünmeye başlar.

**2. Süreci sahiplenme:** Süreç tasarımına son kullanıcıları dahil et. "Sizi atlayarak tasarladık" yerine "sizinle birlikte tasarladık" mesajı.

**3. Süperkullancı programı:** Değişime açık erken benimseyenleri (early adopters) süperkullancı olarak yetiştir. Akranlar arası öğrenme, resmi eğitimden daha etkilidir.

**4. Şeffaflık:** Sprint review toplantılarını açık tut; yöneticiler ve kullanıcılar nerede olduğumuzu görsün.

---

## Ölçüm: Hibriti Nasıl İzliyorum?

Hibrit modelde iki tip metrik takip ediyorum:

**Proje düzeyinde (Waterfall metrikleri):**
- Earned Value Management (EVM): Bütçe ve takvim sapması
- Milestone tamamlanma oranı
- Risk kaydı güncelleme frekansı

**Sprint düzeyinde (Agile metrikleri):**
- Sprint velocity (sprint başına tamamlanan iş miktarı)
- Kullanıcı kabul testi başarı oranı
- Açık hata bileti sayısı

Bu iki bakış açısını birleştirmek, hem üst yönetime ("proje yolunda mı?") hem de ekibe ("bu sprint ne kadar ürettik?") anlamlı bilgi sunuyor.

---

## Sonuç

ERP proje yönetiminde metodoloji ideoloji değil araçtır. PMP® ve Agile birbirinin rakibi değil, tamamlayıcısıdır. Çerçevede Waterfall'ın disiplini, içeride Agile'ın esnekliği — bu ikisinin dengesi doğru kurulduğunda CANIAS ERP gibi karmaşık sistemler bile öngörülebilir ve yönetilebilir hale gelir.

25 yıldır öğrendiğim en önemli şey: Metodoloji değil, yargı gücü fark yaratır. Hangi aracı ne zaman kullanacağını bilen proje yöneticisi başarıya ulaşır.

---

**Ahmet Recep Yıldız**
ERP Proje Yöneticisi & Dijital Dönüşüm Uzmanı | PMP® | ISO 27001 LA/LI
INNOVA Bilişim | Türkiye
🌐 [ahmetyildiz.net](https://ahmetyildiz.net) | Wikidata: [Q139718024](https://www.wikidata.org/wiki/Q139718024)
