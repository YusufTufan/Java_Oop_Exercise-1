# Kare Sınıfı
Bu Java sınıfı, bir karenin alanını ve çevresini hesaplamak için kullanılır.

## Kurulum
1. Bu projeyi bilgisayarınıza klonlayın veya ZIP olarak indirin.
2. Java geliştirme ortamınızı (IDE) kullanarak proje dosyalarını açın.

## Nasıl Kullanılır
### Kare Nesnesi Oluşturma
```java
// Kenarı 5 olan bir kare oluşturulur
Kare kare1 = new Kare(5);

// Varsayılan olarak kenarı 1 olan bir kare oluşturulur
Kare kare2 = new Kare();
```

### Alan ve Çevre Hesaplama
```java
// Karelerin alanlarını ve çevrelerini hesaplar
int alan = kare1.alan();
int cevre = kare1.cevre();

// Kare bilgilerini yazdırır
System.out.println(kare1.toString()); // kenar=5  alan=25  çevre=20
```

## Metodlar

### Kare(int k)

Bir kenar uzunluğu belirterek yeni bir Kare nesnesi oluşturur.

### Kare()

Kenarı varsayılan (1) uzunlukta olan yeni bir Kare nesnesi oluşturur.

### alan()

Karenin alanını hesaplar ve döndürür.

### cevre()

Karenin çevresini hesaplar ve döndürür.

### toString()

Karenin özelliklerini bir dize olarak döndürür. Biçim: "kenar= [kenar uzunluğu]  alan= [alan hesaplanan değeri]  çevre= [çevre hesaplanan değeri]"
