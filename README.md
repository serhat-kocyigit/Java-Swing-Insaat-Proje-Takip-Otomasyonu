🏗️ Java Swing İnşaat Proje Takip Otomasyonu
🌟 Projeye Genel Bakış
Bu proje, inşaat sektöründeki küçük ve orta ölçekli projelerin takibi, teklif süreçlerinin yönetimi ve proje bazlı dokümantasyonun düzenli bir şekilde saklanması için geliştirilmiş, masaüstü tabanlı bir otomasyon sistemidir.

Proje takibi ve belge yönetimini tek bir masaüstü uygulamasında toplayarak, kullanıcıya kolay ve yerel bir çözüm sunar.

⚙️ Teknik Özellikler
Geliştirme Dili: Java

Kullanıcı Arayüzü (GUI): Java Swing (Masaüstü uygulaması)

Derleme/Yapılandırma: build.xml 

Amaç: İnşaat Projesi Tekliflerinin, Planlarının ve Durum Takibinin Merkezi Yönetimi.

✅ Temel İşlevler (Dosya Yapısına Göre Öngörülen)
Proje klasör yapısı incelendiğinde, uygulamanın aşağıdaki işlevleri yerine getirmesi beklenmektedir:

Proje Bilgisi Kaydı: Yeni inşaat projelerinin temel bilgilerini sisteme kaydetme.

Doküman Yönetimi: Projelerle ilişkili PDF (Teklif.pdf, Proje_1.pdf vb.) ve görsel dosyaları (proje resimleri/) düzenli bir şekilde ilişkilendirme ve saklama.

Proje Takibi: Projelerin aşamalarını, durumunu ve muhtemel teslimatlarını izleme.

Masaüstü Çözümü: Özel bir web sunucusu veya karmaşık altyapı gerektirmeyen, yerel bilgisayarda çalışan, hızlı bir arayüz sunma.

🖥️ Kurulum ve Çalıştırma
Bu proje bir Java masaüstü uygulamasıdır (Java Swing). Projenin çalıştırılması için sisteminizde Java Development Kit (JDK) kurulu olmalıdır.

⚠️ Not: Projenin detaylı veritabanı ( MySQL ) bağlantısı, kullanıcı yönetimi ve ilk kurulum adımları şu anda dokümante edilmemiştir. Projeyi çalıştırmak için ana sınıfı bulup IDE (örneğin NetBeans, Eclipse) üzerinden çalıştırmanız gerekmektedir. Veritabanı gereksinimi varsa, kod içinden bu bilgiye ulaşılabilir.

Adımlar:
Depoyu Klonlayın:

Bash

IDE ile Açın: Tercih ettiğiniz bir Java IDE'sinde (NetBeans, Eclipse veya IntelliJ IDEA) projeyi açın.

Çalıştırın: Projenin ana main metodunu içeren sınıfı (src/javaapplication3/ klasöründe bulunmalıdır) bularak uygulamayı çalıştırın.

🤝 Katkıda Bulunma ve Geliştirme
Bu proje açık kaynaklıdır ve yeni özellikler, hata düzeltmeleri ve özellikle eksik olan dokümantasyonun tamamlanması için katkılara açıktır!

Projenin gerçek bir inşaat takip aracı olması için aşağıdaki geliştirmelere ihtiyaç vardır:

Gelişmiş Kullanıcı Yönetimi: Çoklu kullanıcı desteği, rol ve yetki tanımlamaları.

Detaylı Dokümantasyon: Kurulum kılavuzu, veritabanı şeması ve kullanım talimatları.

Modern Arayüz: Mevcut Swing arayüzünün güncel tasarım prensiplerine uygun olarak iyileştirilmesi.

Eğer bu alanlarda destek olmak isterseniz lütfen bir Pull Request (Çekme İsteği) gönderin.

🙋‍♂️ Kimler İçin Uygundur?
Java Swing ile Masaüstü Uygulama Geliştirme pratikleri yapmak isteyen yazılımcılar.

Küçük ölçekli inşaat projelerini yerel bir masaüstü uygulaması ile basitçe takip etmek isteyen bireysel müteahhitler veya firmalar.
