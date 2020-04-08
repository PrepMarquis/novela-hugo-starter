+++
authors = []
date = 2020-04-08T10:18:35Z
excerpt = "İnternetin %30'unu çalıştırdığını her fırsatta vurgulayan Wordpress günümüzde bir blog sitesi açmaya kalkışıldığında ilk başvurulan araç konumunda. Peki Wordpress gerçekten bu blogging için biçilmiş kaftan mıdır?"
hero = "/images/kaitlyn-baker-vZJdYl5JVXY-unsplash.jpg"
timeToRead = 0
title = "Wordpress'e Veda - Merhaba Git, Hugo ve JAMstack 💻️"

+++
## Blog Yazmak!

İçerik akışının neredeyse tamamının veri devleri tarafından kontrol edildiği günümüzde gerçekleştirilebilecek en rafine ve soylu etkinliklerden biri. Internetin büyük resme oranla çok küçük de olsa bir parçasına sahip olup kendi estetik ve ifade anlayışlarınıza göre kurgulayabileceğiniz bir alan edinmek, veri devlerinin paylaşım ve etkileşim maksimizasyonu odaklı yapılarından uzaklaşım derin bir nefes almak... Üstelik Twitter vb mikroblog platformları veya sıklıkla tercih edilen görsel sosyal medyalardan kendini kalıcı olması ile ayırıyor. Platform kapanmayı veya hoşunuza gitmeyen özellikler getirmeyi tercih etse de içeriğiniz size ve sadece size ait. Aidiyet demişken blog tutmanın kişisel markanıza ve gelişiminize faydaları iddia edildiğine göre saymakla bitmiyor. Mantar gibi biten her startupın veya büyük şirketlerin web sayfalarında bloglara yer veriyor olmalarına saşmamalı blog yazıları kişisel markanıza katabileceği değeri hiç kuşkusuz bu firmalara da katıyor, hizmet sunan kişi veya kuruluşların kitleleri ile marka haricinde iletişim kurmalarına yarayan ayrı bir **narrative** katmanı oluşturuyor. [örneğin](https://retool.com/blog/) retool blog verebileceğim en güzel örneklerden.

Gelelim asıl konumuza, 2020 yılında internet günlüğü tutmak isteyen herhangi bir kişi eğer Medium veya write.as gibi neredeyse tamamen blogging için özel olarak dizayn edilmiş ücretli/ücretsiz SaaS modelli uygulamalara geçiş yapmak istemiyorsa karşısına çıkacak seçenekler yine ücretli veya ücretsiz Wix, Squarespace, Webflow vb SaaS platformu ve envai çeşit internet sitesi oluşturuculardır. Örneğin yazılım alternatifleri önerileri konusunda öncü web sitesi alternativeto.net üzerinde yapılan bir "_Wordpress alternatifleri_" araması [şu sonuçları](https://alternativeto.net/software/wordpress/) vermekte.

SaaS platformlarının neredeyse hepsinin landing sayfaları üzerinde kısa bir inceleme, sundukları hizmetler konusunda yaklaşık bir fikir edinmemize yetecektir. Aynı zamanda diğer çözümlere göre artılarını ve eksilerini karşılaştırabiliriz. Kişisel düşüncem SaaS modelinin en büyük problemi: **aidiyet problemidir.** içeriklerinizin bütünlüğü ve nasıl sunulduğu, ne kadar süre ne şartlarda sunulacağı ve yine ne durumda sunulmasının sonlandırılacağı SaaS sunucusunun kararına bağlıdır. Bu argüman sadece potansiyel hassas konularda içerik geliştirenleri ilgilendiren bir problem değildir, aksine içeriği üretmenizden dağıtmanıza ve revize etmenize içerikte ve platformda yapacağınız sınırlı değşikliklere kadar SaaS modelinin çektiği sınırlar içinde olacaksınız. Problemleri bir kenara bırakırsak SaaS'ın sunduğu en büyük yarar altyapıyı dert etmek zorunda olmamanızdır.(çoğu zaman) Medium gibi platformlar içerik oluşturmanızı sağlarken aynı zamanda kitle kazanmanıza ve etkileşim toplamanıza yardımcı olur. Webflow diğerlerine oranla daha üstün kullanıcı deneyimine sahip site yapıcısı ile sizi web tasarımın temelleri hakkında bilgi sahibi bile yapabilir. Wix ise... eee... [çoğunlukla başınızı ağrıtır](https://www.trustpilot.com/review/www.wix.com).

SaaS modelini eleyenlerin elinde genellikle (Standart bir Google araştırması sonunda) bir avuç denenmiş ve sık kullanılan çözüm ve binlerce eski, artık güncelleme almayan ve az özellikli CMS kalacaktır. Bunların blog amaçlı kullanılanlarının başını Wordpress çekmektedir. PHP özellikli paylaşımlı hosting servislerine tek tıkla kurulabilmesi, neredeyse her alanda ve özellikle [eklentilerinin](https://tr.wordpress.org/plugins/) bulunması Wordpress'in yaygın kullanılmasını fazla söze gerek bırakmadan açıklamaktadır. Ancak kendisinden beklenen her şeyi gerçekleştirmeye çalışması neredeyse hiçbir şeyi "_çok iyi_" gerçekleştirememesine neden olmuştur. Wordpress tabiri yerindeyse **kendi başarısının kurbanıdır**.

Zevkler tartışmaya açık olmakla birlikte kişisel görüşüm Wordpress'in 2020'nin tasarım anlayışını out-of-the-box veremediği yönündedir. Wordpress kurduğunuzda onu sorunsuz, akıcı ve parlak arayüzlere alışmış normal bir okuyucuya kabul ettirmek için temalar üzerinde kafa yormanız, çeşitli eklentiler yüklemeniz, sitenin güvenliğini onlarca tehdide karşı aktif olarak sağlamanız ve bunların hepsini performanstan ödün vermeyerek yapmanız gerekmektedir. Bu yolculukta para harcamamak ise gerçekten zordur. Bütün bunları bir MYSQL hatası üzerine kaybetmek ve baştan başlamak az karşılaşılan bir durum değil. Normal bir paylaşımlı hosting servisinde çalıştırabileceğiniz diğer çözümler de Wordpress'in düştüğü hatalara benzer şekilde düşerek basit bir blog yönetimi işini büyük bir probleme dönüştürebiliyorlar. Ghost ve Kirby gibi modern çözümler yukarıda saydığım sorunlara daha somut çözümler getirseler de sizi tamamen içerikle baş başa bırakma konusunda yeterince iyi sayılmazlar. Ayrıca Ghost kullanabilmek için platformu bir **Virtual Private Server** üzerinde barındırmanız gerekir.

Pekala, amacımız modern tasarım prensipleri etrafında oluşturulmuş ve oluşturmak istediğiniz içerik ile aranıza güncellemeler, süresi biten deneme sürümleri uyarıları, temalarda **Black Friday 2020** indirimleri gibi saçmalıklarla girmeyen bir çözüm bulmak.

Daha önce **Markdown** ile çalıştıysanız veya herhangi bir metin editöründe yolunuzu bulabiliyorsanız, basit **git** komutlarına aşinalığınız ve aktif bir **github**, **gitlab** veya **bitbucket** hesabınız varsa hazırlanın başlıyoruz.

Karşımıza çıkacak ilk konsept [static site generators](staticgen.com) bu araçların her biri kendi ortamlarına uyumlu olarak hazırlanmış herhangi bir site temasını barındıkları git repolarından webde sunulabilir sitelere dönüştürmek için programlanmış aracılardır. En çok kullanılanları Hugo ve Gatsby'dir.

İkinci konsept ise [continuous deployment](https://docs.netlify.com/configure-builds/get-started/) Hugo, Gatsby veya herhangi bir static generator üzerinde yapılmış temaları sizin git sunucunuzu bağlamanız dışında güvenlik, güncelleme vb konularda araya girmenize gerek kalmadan internete sunan araçlardır. En çok kullanılan çözüm bu alanda [netlify.com](https://netlify.com)'dur.

Bu konseptleri test etmek için netlify ve hugo kullanan bir deneme yapalım. Bu yazıyı takip edenlerin JAMstack üzerinde ilk denemesini gerçekleştirdiğini varsayarak sistemi mümkün olan net sade hali ile anlatacağım.

[https://jamstackthemes.dev](https://jamstackthemes.dev/ "https://jamstackthemes.dev/") ve [https://themes.gohugo.io](https://themes.gohugo.io/ "https://themes.gohugo.io/") adreslerini inceleyerek bir tema seçebilir veya alternatif olarak tema seçiminizi [forestry.io](https://forestry.io/starters/) üzerinden yapabilirsiniz. Tema seçiminizi nereden yaptığınızdan bağımsız olarak indirdiğiniz tema klasörünü ayrı bir git reposu açarak commit etmeniz gerekmektedir. Sürece forestry üzerinden devam ettiğimizi farz edersek karşımıza forestry.io tarafından açılmış içinde tema ayarları be yazılar bulunan bir klasör dizisi çıkacaktır.

**Forestry.io** üzerinden Wordpress üzerinde yaptığınız gibi siteniz hakkında meta içerikleri değiştirebilir görsel ayarlamaları yapabilir yazar ekleyebilir ve çıkartabilirsiniz.

Bir sonraki adım siteyi **netlify.com**'a deploy etmek

Hesabınızda yeni bir proje başlatıp git hesabınızı bağladıktan sonra sizden **build** komutu ve **path** girmeniz istenecektir buraya Hugo kullananlar hugo ve public yazmalılar ayrıca indirdiğiniz temanın bulundurulduğu git hesabını kontrol ederek (çoğunlukla readme belgesinin içinde bulunur.) hangi Hugo versiyonu kullanmanız gerektiğini öğrenin ve **add another variable** diyerek **HUGO_VERSION** / **X.XX.X** bilgilerini netlify üzerinden doldurun.

> Netlify sitenizi yayına aldıktan sonra **.netlify.com** ile biten bir subdomain atayacaktır.
>
> Kendi domaininizi ücretsiz olarak bağlayabilirsiniz **domains** sekmesini inceleyin.

Siteniz yayına girdikten sonra **forestry.io** veya git hesabınızda yapılacak her türlü değişiklik ve güncelleme netlify tarafından otomatik olarak yayınlanacaktır.

Bu yazıyı okuduğunuz web sitesi **forestry.io CMS** üzerinde [**Novela**](https://github.com/forestryio/hugo-theme-novela) teması kullanılarak yapılmıştır ve **netlify** tarafından sunulmaktadır.

Kolay Gelsin!