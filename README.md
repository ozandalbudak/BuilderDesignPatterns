Builder Design Pattern 
Builder Design Pattern Creational Patterns gurubu içerisinde yer alır. Üretimi bir çok 
parçadan oluşmuş, çok parçalı karmaşık nesnelerin parçalarının adım adım bir araya getirilerek 
oluşturulmasını sağlayan bir tasarım desenidir. 
Nesne üretecek istemci, üretilecek nesnenin tipini belirleyerek nesneyi elde eder. 
Nesne üretimi ile ilgilenmez. 
Director 
Builder arayüzünü uygulayarak nesne örneklemesi yapan yapı. 
Builder
Nesne oluşturulma işlemi şablonu için abstract class veya interface. 
ConcreteBuilder: 
Nesnenin temel özelliklerini oluşturacak yapı. Ayrıca nesnenin 
dışa açılmasını sağlayan yapılar da içerir. 
Product
Nesne 
Örneğimizde Bir bilgisayar üretimi aşamalarını konumuz ile ilişkilendirmeye çalışacağız. 
