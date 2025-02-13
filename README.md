Toplu Taşıma Planlaması

Bu proje, mahallelerin çeşitli özelliklerini değerlendirerek toplu taşıma güzergahı için en uygun mahalleyi seçmeyi amaçlayan bir Java uygulamasıdır. Program, mahallelerin nüfus yoğunluğu, ulaşım altyapısı, maliyet, çevresel etki ve sosyal fayda gibi kriterlere göre değerlendirilmesini sağlar ve Softmax fonksiyonu kullanarak bu kriterlere ağırlıklar verir. Son olarak, en uygun mahalle en yüksek maliyet-fayda oranına göre belirlenir.

Proje İçeriği

Mahalleler sınıfı: Mahallelerin adı, nüfus yoğunluğu, ulaşım altyapısı, maliyet, çevresel etki ve sosyal fayda gibi özelliklerini tutar.
Softmax Hesaplama sınıfı: Kriterlerin normalize edilmesi ve ağırlıkların hesaplanması için Softmax fonksiyonunu uygular.
TopluTasmaPlanlama sınıfı: Mahallelerin değerlendirildiği ve en uygun güzergahın seçildiği ana sınıftır.

Gereksinimler
Java 8 veya daha yeni bir sürümü.
Bir IDE veya terminal üzerinden çalıştırmak için JDK (Java Development Kit).
Kurulum ve Çalıştırma
Bu projeyi yerel makinenize klonlayın:
git clone https://github.com/kullaniciAdiniz/toplu-tasima-planlamasi.git
Proje klasörüne gidin:
cd toplu-tasima-planlamasi
Kodu çalıştırmak için şu komutu kullanın:
javac TopluTasmaPlanlama.java
java TopluTasmaPlanlama


Kullanılan Teknolojiler

Java: Programın yazıldığı dil.
Softmax Fonksiyonu: Kriterlerin ağırlıklandırılmasında kullanılan matematiksel fonksiyon.
Katkı

Bu proje açık kaynaklıdır. Katkıda bulunmak isterseniz, lütfen bir pull request gönderin ya da önerilerinizi paylaşın.


Açıklamalar:
Veriler: Bu projede mahalleler için belirli ve anlamlı veriler kullanılmıştır. Mahallelerin özellikleri arasında nüfus yoğunluğu, ulaşım altyapısı, maliyet, çevresel etki ve sosyal fayda gibi faktörler bulunmaktadır. Bu faktörler, Softmax fonksiyonu ile normalize edilip ağırlıklandırılır.
Kriterler:
Pozitif Kriterler: Nüfus yoğunluğu, ulaşım altyapısı ve sosyal fayda.
Negatif Kriterler: Maliyet ve çevresel etki. Bu kriterler ne kadar düşükse o kadar iyidir.
Hesaplama Yöntemi: Softmax fonksiyonu, mahallelerin her bir özelliğine verilen ağırlıkları normalize eder. Bu ağırlıklar kullanılarak her mahalle için maliyet-fayda oranı hesaplanır ve en uygun mahalle seçilir.
