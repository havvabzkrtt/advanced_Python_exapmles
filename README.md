# İleri Python Terimleri

## Args

- Fonksiyonun parametresi *args olarak tanımladığında : Input olarak list/tuple gibi yapılar vermeden de değişken sayılı input'u sıralı olarak fonksiyona verebilebilmesini sağlar.

## Kwargs

- Fonksiyonun parametresi **kwargs olarak verildiğinde : Değişken sayıda keyword argument verebilebilmesini sağlar.

## Closure

- İç içe fonksiyonlarda outer(dış) fonksiyonu çağırdıktan sonra bile inner(iç) fonksiyonun, outer fonksiyon scope'una erişebilmesidir.

## Decorator

- Bir fonksiyon gibi düşünülebilir. Decorator'lar başka fonksiyonları input (parametre) olarak kabul edip yeni bir fonksiyonalite ile yeni bir fonksiyon döndüren yapılardır. Orjinal olarak verdiğimiz input fonksiyonu değiştirmeyecek.

## Class

- Class mantığı hem fonksiyonalite hem de veriyi bir arada tutma yoludur.

- Attribute: Class içerisinde tanımlanan variable'lar.

- Method: Class içerisinde tanımlanan fonksiyonlar.

Araba taralamak istiyoruz: 

    class     : arabanın planı class olur (özellikleri, yapacağı şeyler) 
    
    obje      : plandan oluşturulan arabalar objeler olur 
    
    instance  : o an hali hazırda incelenen araba objesi olur 
    
 
## Class Variable

- Class Variable'lar class'tan yaratılan tüm objelerde aynı olarak paylaşılan variable'lardır, Instance Variable'lar instance'a özeldir.


## Class & Static Method

- Class Method

İlk input'u, oyomatik olarak class referansı aktarılan methodlardır.

- Static Method

Class'ların içerisinde otomatik olarak hiçbir input almayan methodlar'dır.


## Inheritance

- Inheritance belirtilen başka classlardaki method veya attribute'lara erişilmesini sağlar.

- Inheritance veren classa "super class" veya "parent class", inheritance alan classa "subclass" veya "child" denir.

- Subclass, superclas'tan dallandıpı için onun tüm attribute'larına ve methodlarına erişebilir.

- Building Functions: isinstance(obje, class), issubclass(subclass, superclas)


## Magic Method

- Magic Method'ları kullanırken bazı built-in davranışları değiştirebiliriz. 

- Magic Method'lar "__" ile çevrilidir. (__MagicMethod__) 

- Bunlara "dunder method" da denir.

- Magic Method'lardan bazıları: __init__(), __str__(), __add__(), __len__()