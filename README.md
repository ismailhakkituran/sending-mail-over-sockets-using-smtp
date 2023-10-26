# sending-mail-over-sockets-using-smtp

Bu uygulama, gönderenin bir GMAIL hesabı olduğu senaryosuna göre google mail sunucularına bağlanacak şekilde tasarlanmıştır.
Google' ın SMTP sunucusuna kolay yoldan "Uygulamaya Tanımlı Şifre Yöntemi" ile bağlanmak için:

1. https://myaccount.google.com/ adresine gidin
2. Sol menüde "Güvenlik" butonuna tıklayın
3. "Google'da oturum açma" bölümünde "2 Adımlı Doğrulama" seçeneğine tıklayın.
4. Burada tekrar mail adresi ve parola istenebilir.
5. Altta "Uygulama şifreleri" bölümüne gelip tıklayın.
6. Uygulamanıza bir isim verin "Sending mails over sockets using SMTP"
7. "Oluştur" butonua tıklayın.
8. Ekrana gelen şifreyi, Java uygulamalarınız içerisinde kullanabilirsiniz. (base64 ile encode ettikten sonra)
