# javanotes
* Polimorfizm: Farklı sınıflar arası aynı methodu çağırmak.
* Inheritance: Kalıtım yoluyla miras alma.
* Interface: Can-do yapabilir ilişkisi. Interface içerisindeki methodlar boş bırakılır.
* Abstract: Is-a ilişkisi. Abstract içerisindeki methodlar dolu yazılabilir.
Class 1 tane abstract 1'den fazla ınterface e sahip olabilir
* Overriding: Kalıtım yoluyla miras alınan methodu ezmek.
* Overloading: Mevcudu aynı isimle oluşturup parametrelerini değiştirmek. 
* Final Keyword: Final variables-> Değiştirilmez değişkenler constant olarak kullanılır. Final class -> Extend edilemez. Final methods = override edilemez.
* Static Keyword: Static variables-> Class'a aittir her nesne için bir defa oluşturulamaz. Memoryde bir defa oluşturulur. Static method -> Class'a aittir. Her nesne için oluşturulmaz
* Encapsulation: Bir sınıfın içeriğinin bilinmesine gerek kalmadan kullanılması. (getter/setter) 
* OOP prensipleri:Encapsulation, Abstraction, Inheritance, Polymorphism
* SOLID:
S- Single Responsibility Principle
O- Open Closed Principle
L- Liskov Substitution Principle
I- Interface Segregation Principle
D- Dependency Inversion Principle
* Cohesion: Bir sınıfın oluşturulma amacına ne kadar bağlı kaldığıdır. Örneğin Customer classının customer ile ilgili bilgi/işlem vs vs tutması.
* Integer vs Int: int primitive değişken tipidir. Integer bir sınıftır.
* JVM, JRE, JDK: JVM->Bir java dosyası derlendiğinde(compile) .class uzantılı java byte kodları oluşur. JVM ile makina kodlarına çevrilir. <Write Once, Run Everywhere> özelliğinin temelidir. JRE-> Java kütüphaneleri + JVM (Run Time Edition). JDK -> JRE + Derleyici + Compiler tool. Development kitidir.
* Instance: Test b = new Test(); b burada instancedır.
* Constructor:Class çağırıldığında ilk çalışan methoddur. Parametre alabilir. Değer döndüremez. Overload edilir. Override edilemez.
* Final: keyword
* Finally: block
* Finalize(): method
* == ve equals: == bellekteki yerleri equals ise değerleri karşılaştırır. Primitive değişkenlerde == kullanılabilir.
* Annatations: Notasyonlar genellikle bir bileşene özellik katmak için veya konfigürasyon için kullanılır.
* XML ve JSON: XML'in okuma zorluğu ve veri alışverişindeki büyük ve yavaş olması json ı ortaya çıkarmıştır.
* varchar ve nvarchar: nvarchar uniqcode tutar. varchar latin alfableri
* Hibernate Anatasyonları: @NotNull boş gelçilmez, @Min minimum değer, @Max max değer, @Pattern email kontrol @size(min,max) ....
* Argüman ve parametre:Argüman bir methodu çağırırken içindeki değişken, parametre tanımlarken kullanılan değer.
* Composition: Bir classı oluşturduktan sonra başka bir class içerisinde kullanmamıza yarar. Sahiplik ilişkisi
* Stored Procedure(SP): Belirli bir işlemi görevi yerine getirebilmek için yapılandırılmış kod parçaları. Veri tabanında saklanan SQL ifadeleridir. SP içinde sp çağırılabilir. ilk çalışmada derlenir daha sonra derlenmediği için performansı yüksektir.
* Autoboxing-unboxing:Primitive tipinin referansa dönüşmesi autoboxing referans tipinin primitive tipe dönüşmesi unboxing
* Throw-throws:Throw istisna fırlatmak için, throws fırlatılabilecek istisnaları methoda tanımlamak içindir. Fırlatılabilir nesne throwable olmak zorunda.
* Mutable-immutable: Immutable değişmez, mutable değişebilir nesnelerdir. Immutable(String, Integer, Long, Double) mutable(Date, StringBuilder)
* Nesned Class(iç içe sınıflar):Sınıf içi sınıf tanımlamak. Kod okunabilirliği ve daha iyi kapsülleme sağlar.
* Coparator vs Comparable: Listelerde list.sort() yapmamız gibi nesnelerle de sıralama yapmamız için kullanılan interfacelerdir compare() compareTo()
* Error vs Exception: yaşanan bir hata dolayısıyla işlem devam edemiyorsa ve burada kalması gerekiyorsa error fırlatır. Exception'da hataya rağmen uygulama devam eder
* Checked exceptions:javada kod geliştirirken try-catch bloğu içerisinde yakalanan ve daha sonra işlem yapılabilen, istenildiğinde bypass edilerek programın çalışmasına ve kullanıcının hiç haberi olmmasını sağlayan exceptiondur.
* Unchecked exceptions:Geliştirme sırasında idenin yazılımcıyı uyardığı hatalar. Örnek olarak error türü verilebilir. JVM'de hata verir.
* coupling: Nesneler arası bağlılıkların minimum düzeyde tutulmasıdır.
* Persistance: Bilgilerin kayıt edilebilmesi, bir yere kayır etme işlemi
* ORM: Object to relation mapping. Bir sınıfını veritabanı üzerinde bir tabloyu temsil etmesine denir.
* JPA: Java Persistance Api. Standart olarak belirtilen ORM yönetiminde kullanılan kütüphanedir.
* Hibernate: ORM ve JPa işlemlerini yapan kütüphane.
* super(): extend edilen üst sınıfın constructorını çağırır
* this(): classda tanımlı değişkeni temsil eder.
* Serialization: değişkenlere ait değerleri ve veri tiplerinin nesnelerimizin içinde bulunuyorsa birlikte saklayabiliyoruz.
* Upcasting: Alt sınıftan oluşmuş bir nesneyi üst sınıftan oluşmuş bir nesneye çevirmek.
* Downcasting: Üst sınıftan oluşmuş bir nesneyi alt sınıftan oluşmuş bir nesneye çevirmek.
* Garbage Collection: Otomatik bellek yönetim mekanizmasıdır.
