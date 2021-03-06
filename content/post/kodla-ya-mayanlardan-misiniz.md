+++
authors = []
date = 2020-10-27T14:49:18Z
excerpt = "Yazılım bilmeden MVP modeline uygun uygulama prototipleri nasıl yapılır?"
hero = "/images/emile-perron-xrvdyzrgdw4-unsplash.jpg"
timeToRead = 0
title = "Kodla(ya)mayanlardan mısınız? (1)"

+++
##### Bu işler nasıl olur biliyorsun,

Aklına parlak bir fikir gelir, güvendiğin birkaç kişiyle paylaşırsın. Bu iş tutar mı sorusu seni internet araştırmaları yapmaya, geri bildirimler almaya ve sunumlar hazırlamaya iter. Kısaca çizim masasındaki ekiplerden ekip kurmaya çalışanlar veya fikir yarışmalarına katılanlar girişimin prototipsiz ilerleyemeyeceğini fark edene kadar çeşitli yollar denerler. Zira günün sonunda ürünün veya hizmetin yaşayabilmesi için destekçi olmak isteyen her aşama öyle ya da böyle çalışan bir prototip istemektedir.

Prototip yapmak, ekiplerin geçtiği önemli kırılma noktalarından biridir. Hatta yerel ekosistemimizde erken aşama girişimlerin başarısız olma nedenlerini analiz edebilme imkanımız olsaydı dağılan ekiplerin arkalarında sınırlı fon, zaman ve yetenekle çıkaramayacağı kadar kompleks fikirler bıraktıklarını veya yazılımcılara erişimleri olmadan teknik işler çıkarmak istediklerinde başarıız olduklarını kolayca gözlemleyebilirdik.

Prototiplerin MVP merceğinden ele alınması gerektiğini lise seviyesindeki proje fuarlarında bile duymaya alışmışken bile yerel ekosistemimizde en çok yapılan hatalardan biri ürünün ilk versiyonunun hatta pazar uyumunu test etmek için çıkartılması gereken deneme sürümlerinin bile pazardaki doğrulanmış ve ölçeklenmiş büyük alternatifleri kadar gelişmiş inşa etmeye çalışmaktır. Bu şekilde ilerleyenlerin envai çeşit web ve mobil geliştirici forumlarına fiyat sormak için girip hevesleri kırılmış olarak ayrılmaları çok daha olasıdır. Bu tarz girift projeler öyle noktalara gelir ki ekip üyeleri bile ne ürettiklerini ve kimin problemini çözdüklerini basitçe açıklayamaz hale gelirler. Aynı şekilde ekipte bir (1) adet yazılımcının bulunmasının projenin baştan sona tamamlanmasına yeteceğini düşünenlere daha yakından bakmalarını tavsiye ediyorum.

Yine de pazara baktığımızda çok kullanılan ürün ve servis mimarilerinde ortak noktalar bulmak mümkündür. Çoğu uygulamada/internet sitesinde bir üyelik portalı, ödeme sağlayıcısı ve kullanıcıların içerik üretmesini sağlayan CMSler bulunur. Hatta kullandığımız çoğu uygulama bu saydığım elementlerin farkı markalar, renk tonları ve deneyimler bütünü ile servis edilmiş halidir. Bu örneği daha iyi anlamak için [medium.com](https://medium.com) ve [eksisozluk.com](https://eksisozluk.com) gibi içerik odaklı iki servisi kendiniz karşılaştırmayı deneyin. Kullanıcı deneyimi boyasının altında yukarıdaki elementlerin sürekli tekrarlandığını göreceksiniz. Öyleyse her proje için sıfırdan başlama merakımızın kaynağı nedir?

Tam bu noktada yazının asıl konusu olan no-code ve low-code platformları devreye giriyor. No-code hareketi basitçe; ürünün geliştirilme aşamasındaki teknik yükün önceden hazırlanmış tasarım ve yazılım odaklı alt yapılara bırakılması şeklinde tanımlanabilir.

Low-code ise daha çok yazılımcı odaklı çözümler sunmasına rağmen normal koşullarda uzun ve hataya açık süreçleri yine yazılımcı odaklı deneyimlerle basitleştirmeye çalışan araçların genel adıdır.

Bulunduğumuz durumu erken aşama için kodlama sonrası-dünya olarak tarif etmek isterdim. Seth Godin Photoshop'un çıkışını üretim meraklılarının başına gelebilecek en iyi şey olarak tanımlamıştı. Önceleri ekiplerin çizim masalarının başında saatler harcamasına neden olan deneme sürümleri Photoshop ile saatler içinde yapılır hale gelmişti böylece girişimciler piyasada daha çok deneme yanılma hakkına sahip oldular Sen, her hafta farklı bir konsept deneme şansın olsa ne yapardın? İlk sürümün için yazılımcı aramak zorunda bile değilsin.

Halihazırda no-code ve low-code marketi sürükle-bırak ve obje manipülasyonu yoluyla özelleştirme sağlayan platformlardan oluşuyor. Bunların her birinin odağı farklı olsa da daha genel amaçlara hitap edenler ve fazla trafik alanlara yer vermeye çalışacağım. Bu aralar neredeyse her gün patlayıp yok olan bazen de pazarda yer bulan no-code ve low-code ürünler görüyorum, bunların patlamaları çoğunlukla [producthunt.com](https://producthunt.com) üzerinde oluyor ilgililerine özellikle periyodik olarak takip etmelerini öneririm.

[Adalo](https://adalo.com)

Adalo'ya no-code isviçre çakısı demek gayet yerinde olur diye düşünüyorum.

[Bubble](https://bubble.io)

Adalo'ya göre daha karmaşık bir arayüz sahip olsa da web alanında daha geniş özelleştirme imkanı sağlayan sürükle-bırak geliştirme platformudur.

[Webflow](https://webflow.com)

Kendinden önce gelen web geliştirme platformlarının üzerine güncel temalar, gelişmiş CMS özellikleri ve okunabilir/düzenlenebilir kod çıktısı getiren Webflow önceliği frontend olan no-code projelerine çok büyük katkısı olabiliyor.

[Memberstack](https://memberstack.com)

Yazılım bilgisi olmayan ekiplerin web platformlarını oluştururken karşılaştığı en büyük engellerden ikisi olan ödeme altyapısı ve üyelik platformu çözümlerini tek entegrasyonda birleştirmektedir.

[Airtable](https://airtable.com)

Bilgi yönetim bankası veya excel benzeri spreadsheet uygulaması olarak kullanılabildiği gibi no-code uygulamalarında veritabanı olarak kullanılmaktadır.

[Retool](https://retool.io)

Tek kullanımlık şirket içi araçların programlamasını kolaylaştıran bir no-code araçtır. Örneğin şube içi stok takibi hizmetini programlama bilginiz olmadan retool ile oluşturmanız mümkündür.

Google Sheets

Google Drive ofis araçları arasında bulunan Sheets no-code uygulamalar için veritabanı olarak kullanımaktadır. Bunun haricinde Zapier gibi low-code araçlarla birleştirilerek 3. parti araçlardan çekilen verilerle dinamik arayüzlere dönüştürülebilir.

[Notion](https://notion.so)

Basit bir not alma uygulaması olarak başlayıp sonradan uçtan uca bilgi yönetimi platformuna döüşen Notion şu an no-code projelerinde veritabanı olarak kullanılabilir.

[Circle](https://circle.so)

Yazılım bilginiz olmadan veya discord/slack gibi komunite platformlarını özelleştirmeye çalışmadan topluluk alanları kurmanızı sağlayan bir araçtır. Üretken Akademi'de aktif olarak kullanmaktayız [topluluk.uretkenakademi.com](https://topluluk.uretkenakademi.com) adresinden inceleyebilirsiniz.

Low-code

[Integromat](https://integromat.com)

Uygulama veya web sitenizle entegre çalışan 3. parti uygulamalardan veriler çekerek işlemler yapmanıza imkan sağlayan mantıksal operasyon platformu olarak özetlenebilir. Örneğin: internet sitesine giriş yaparak iletişim formunu dolduran kişinin e-mail adresini Google Sheets dosyasına kaydet -> önceden hazırlanan yanıt şablonunu Gsuite üzerinden e-mail adresine gönder -> kişiyi kurumsal iletişim listesine ekle vb işlemler yapılabilir 3. parti entegrasyonlarının sayısını sürekli artıran Integromat bu alanda Zapier'in gerisinde kalsa da Integromat özelleştirilmiş entegrasyonlara izin vererek kendi servislerinizi eklemenize imkan sağlamaktadır.

[Zapier](https://zapier.com)

Integromat'ın operasyon başına daha maliyetli alternatifidir.

[Zeplin](https://zeplin.io)

Arayüz tasarımı süreçlerini hızlandırmasıyla birlikte Figma, Sketch ve XD çizimlerini doğrudan frontend koduna aktarması önemli özelliklerinden biridir.

Ürün çıkarmasak? Bu işin farklı boyutları da var mı?

Elbette! no-code ve low-code = ürün bilgeliği ürünün üretildiği platforma hakimseniz şirketler veya startuplar x işini otomatize etmek için in-house iş gücüne yazılım yaptırmak yerine sizin low-code platformda üreteceğiniz otomasyona para vermeyi tercih edebilir. [Olasılıklar sınırsız]().

Kuluçka merkezileri / hızlandırıcı programları için bu ne anlama geliyor?

En kapsamlı no-code araçlarını [destekler](https://uretkenakademi.com/destekler.html) listenize ekleyin. Aktif yazılımcı arayışında olan girişimlerinize match ararken bir yandan no-code konularında eğitimler verin, sonuçlardan pişman olmayacaksınız no-code araçları bu tür ortaklıklara açık kuruluşlardır.

Olumsuz yanları nelerdir?

Kullandığınız platformlar genellikle aylık kullanım başına ücret almaktadır. Bu da verilerinizi ve prototipinizi mümkün oldukça içeride tutmak için gayret göstermelerine neden olmaktadır. İmkan ve fırsat bulduğunuzda açık web ve mobil teknolojilerine geçiş yapın ve kendi ekibiniz ile ilerlemeye başlayın.

Dipnot: Girişim Fabrikasından Yücel Faruk Şahan tarafından paylaşılan no-code hakkında kapsamlı ve birçok açıdan ilk sayılabilecek Twitter gönderisine göz atmayı unutmayın. 

Bu yazıda kısıtlı zamandan dolayı görsel örneklere yer veremememe rağmen bu ekikliği yazıya yeni eklemelerle veya bir yazı dizisine dönüşmesini sağlayarak kapatmayı planlıyorum.