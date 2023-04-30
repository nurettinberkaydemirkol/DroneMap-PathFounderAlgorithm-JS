# Drone-Map

Kodun Amacı: Şehrin belirli noktalarında belirli ihtiyaçlar doğrultusunda ürünleri dağıtan drone navigasyonu oluşturur.

1- Harita uygulaması kullanılarak 10 adet nokta belirlenir ve bu noktaların koordinatları kaydedilir.

2- Belirlenen noktalardan başlayarak, öncelik değerlerine ve stok miktarlarına göre bir graf oluşturulur. Bu grafın her bir düğümü, bir noktaya karşılık gelirken, her bir kenar da iki düğüm arasındaki mesafeyi ve öncelik değerlerini temsil eder.

3- Graf algoritması kullanılarak, belirlenen noktalardan başlayarak en kısa yol belirlenir. Bu işlem için örneğin Dijkstra kullanılabilir. Öncelik değerleri ve stok miktarları bu işlemde önemli birer kriter olacaktır.

4- Belirlenen en kısa yol üzerindeki noktalara malzeme sevkiyatı yapılır. Bu işlem için drone veya araç kullanılabilir. Harita uygulaması kullanılarak en hızlı ve en verimli sevkiyat rotası belirlenir.

5- Tüm noktalara malzeme sevkiyatı yapılana kadar bu işlem tekrarlanır. Sevkiyat sırasında, öncelik değerleri ve stok miktarlarına göre en kısa yolu belirlemek için graf algoritması kullanılır.

Kodu standart bir HTML şeklinde live server üzerinden çalıştırabilirsiniz.


Dijkstra

Dijktra Algoritmasının temeli Hollandalı bilgisayar bilimcisi olan Edsger Dijkstra’ya dayanmaktadır.  Edsger Dijkstra , 1959’da ağırlıklı bir grafiğe uygulanabilecek bir algoritma önerdi. Grafiğin her kenarında negatif olmayan bir değer içermesi şartıyla, grafik o yönde devam edebilir veya etmeyebilir. Bu algoritmaya “Dijkstra Algoritması” adını verdi. Dijkstra Algoritması, seçtiğiniz bir düğüm ile bir grafikteki diğer tüm düğümler arasındaki en kısa yolun hesaplanmasına olanak tanır.

Dijkstra  algoritması düğümler arası en kısa yolu bulmak için kullanılan bir algoritmadır.Günümüzde oldukça popüler olan bu algoritma ,Google Maps,OSPF(Open Shortest Path First) protokolünde ,oyun programlamada ulaşım ağlarında kullanılmaktadır.
Algoritmanın temel amacı graf üzerinde bir düğümden başka bir düğüme giderken en ucuz maliyetle nasıl gidilebileceği hesaplamaktır.
