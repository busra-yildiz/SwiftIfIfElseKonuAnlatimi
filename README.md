# SwiftIfIfElseKonuAnlatimi
Swift programlama dilinde, koşullu ifadeler kullanarak belirli koşullara göre farklı işlemler yapabilirsiniz. Bu koşullu ifadeler if, else if ve else anahtar kelimelerini içerir. İşte Swift'te koşullu ifadelerin nasıl kullanılacağına dair temel bilgiler:

if İfadesi:
if ifadesi, bir koşulun doğru (true) olup olmadığını kontrol eder. Eğer koşul doğruysa, if bloğundaki kod çalışır. Eğer koşul yanlışsa, if bloğu atlanır ve program diğer işlemlere devam eder.
Örnek:
let sayi = 10

if sayi < 20 {
    print("Sayı 20'den küçüktür.")
}
else if İfadesi:
else if ifadesi, birinci if ifadesi yanlışsa başka bir koşulu kontrol etmenizi sağlar. Birden fazla koşul kontrolü yapmak için kullanılır.
Örnek:
let not = 75

if not >= 90 {
    print("A")
} else if not >= 80 {
    print("B")
} else if not >= 70 {
    print("C")
} else {
    print("D")
}
else İfadesi:
else ifadesi, herhangi bir if veya else if ifadesi doğru değilse çalıştırılacak kodu tanımlar. Yani, hiçbir koşul doğru değilse bu blok çalışır.
Örnek:
let sayi = 5

if sayi > 10 {
    print("Sayı 10'dan büyüktür.")
} else {
    print("Sayı 10'dan küçüktür.")
}
Bu örneklerde gördüğünüz gibi, Swift'te if, else if, ve else ifadeleri ile koşullu işlemler yapabilirsiniz. Bu, programlarınızı belirli koşullara bağlı olarak farklı yolları takip etmek için kullanmanızı sağlar.
