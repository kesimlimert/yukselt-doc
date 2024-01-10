# Rezervasyonu bulunan kullanicinin test edilmesi

Oncelikle uygulamaya giris yapan musteri hesabinin telefon veya eposta adresinin yaratilan musteri hesabi ile eslesmesi gerekir. Eslesmesi durumunda giris yapalan musteri hesabi rezervasyonunu ve sunulan firsatin cep telefonuna mesaj ile bilgisini alir.

1. Kullanici mesajda gonderilen URL ile uygulamayi acar
2. URL icerisindeki bilgi ile kendine ait firsatlari ve rezervasyonunu goruntuler
3. Secimini yaptiktan sonra satin alima gitmeden once tekrar telefon dogrulamasi alir, dogrulamasiyla ayni zamanda kalici olarak Yukselt uygulamasinda hesabi olusturulur
4. Satin alimi gerceklestirir

Test sonrasinda satin alim Saleor dashboard uzerinden goruntulunebilir veya otomatik eposta alinabilir.