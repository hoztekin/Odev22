1. Ana Program yapısı

- Uygulama console projesidir ve Static Void Main içerisinde çalışmaktadır. Hata yönetimi try-catch blokları içerisinde çalışmaktadır.

2. Alfabe Girişi

- Kullanıcıdan alfabe girişi isteniyor ve giriş bilgilerindeki boşluklar vs. validasyona tabii tutularak her karakter virgülle ayrılarak bir listede tutuluyor.

3. Alfabe kontrolu

- Alfabenin "a" ve "b" karakterlerini içerik içermediği kontrol ediliyor.

4. Düzenli ifade kontrolü (IsValidRegex Method)

- girilen düzenli ifadenin geçerli olup olmadığı kontrol ediliyor ve her harfin alfabede tanımlı olup olmadığına bakılıyor.

5. Kelime Üretimi (GenerateWords Method)

- Verilen düzenli ifadeye göre belirli sayıda kelime üretiyor ve Hashset kullanılarak tekrar eden kelimeler engelleniyor.

6. Rastgele Kelime Üretimi (GenerateRandomWord Method)

- Pattern'e göre rastgele kelimeler üretiliyor (Burada istenen 3 sayısı ve oradan L={a,aa,ba} cevabının alınması, pattern genişletilebilir)

7. Kelime Kontrolü (CheckWord Method)

- Verilen bir kelimenin düzenli ifadeye uyup uymadığını kontrol ediyor, Basit kural kontrolleri içeriyor.

Uygulamın Temel Özelliği

1. Bir alfabe tanımı alıyor.
2. Düzenli ifade alıyor
3. Bu düzenli ifadeye göre kelimeler üretiyor
4. Üretilen kelimeleri gösteriyor
5. İsteğe bağlı olarak kelime kontrolü yapıyor
