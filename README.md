Mehmet Pekcan ile Next.js Blog

next js ile bir blog sayfası oluşturacağız:
burada backend servisinden aldığımız blokları listeleyecğiz.bu eğitim sonrasında bir web sitesi geliştireceğiz. 

burada yapmamız gereken ilk adım:
npx create-next-app@latest --experimental-app bu kodu yazmak oldu oradan sonra proje adını oluşturmuş olduk.
sonra bize oradaki gelen komutlar vardı biz orada no seçeneğine bastık 
ve sonra kurulum yapmaya başladı ve en sonra "code ." yazarak vsc'de uygulamayı başlatmış olduk.
next-config.js:next-js'nin konfigürasyon dosyasıdır.
public olan kısım:sitenin erişilebilen bütün kaynağıdır.
uygulamanın içindeki dosyaları kontrol edip özelliklerini söyledikten sonra
yarn dev yazarak çalıştırıyoruz.
sonra app içerisindeki css-jsx uzantısındaki dosyaları silerek sıfırdan yeni bir site oluşturmaya başlıyoruz.
ve layout ile page dosyasını sadece bırakarak biçimlerini değiştiriyoruz.
sonra yeni bir css dosyası açıyoruz. "styles.module.css" olarak bunların oluşturduğumuz etiketlerde özelliklerini yazdıktan sonra layout kısmına giderek
body kısmında oluşan kısmın içine girerek body className={styles.container} giriyoruz.
import styles from "../styles/style.css"; diye böyle içine stil dosyasını aktarabiliyoruz.
şimdi sırada ise next içine font ekleyeceğiz.
içerisine yarn add @next/font yazısını gireriz.
şimdi sırada ise:head ve meta tag'ler yer alıyor.
bunun için bir tane head.js dosyası açıyoruz rfce gibi bir kısaltma ile enter basıyoruz.
sonra uygulamada component adlı dosya açıyoruz ve içine 2 tane dosya koyuyoruz:
Header ve Footer olmak üzere ve bunları layout sayfası içerisine entegre ediyoruz
Yazımı ise şöyle olacak import Header from "../components/Header";
sonra link olayı var sayfaya bu sefer de onu şöyle import edeceğiz:
import Link from "next/link";
yazımı şu şekil olacak:  <Link href="/"> BLOG </link>

Blog Card componenti yapacağız page dosyasına aktararak bunu nasıl yapacağımızı anlatacağım Components sayfası içerisinde index.js-style.module.css oluşturduktan sonra
page sayfası içerisine girerek sayfayı bağlıyoruz.Ve BlogCard sayfası içerisinde dizayn ve komutları hazırlıyoruz.

Görmek için:
https://next-js-13-blog-qlkhge7jl-tressaera.vercel.app/
