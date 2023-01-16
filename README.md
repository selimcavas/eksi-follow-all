eksi-follow-all
=====
Ekşi sözlükteki herkesi curl ile post request atarak takip etmeye yarayan ufak bir shell scripti.

⚠️Hesabınızın başına gelenlerden ben sorumlu değilim. Kullanmadan önce doğru cookieyi girdiğinize emin olun ve kullandığınız takdirde olası sonuçların sorumluluğunu üstlenin.⚠️

**(not: büyük ihtimal başına bir şey gelecek)**

Nasıl Kullanılır
--------------------------------------------------------------------------------

1. Repoyu clonelayın.
2. eksisozluk.com'u açın ve herkesi takip etmek istediğiniz hesabınızla giriş yapın.
3. Herhangi bir kullanıcının profiline girin.
4. ctrl+shift+j veya cmd+shift+j ile chrome dev toolsu açın.
5. Üstten network tabine girin, önce kırmızı noktanın yanındaki clear tuşuna basın sonra preserve log'u tikleyin.
6. Kullanıcıyı takip edin, sayılar?r=b şeklinde bir istek göreceksiniz ona tıklayın.
7. Headerları arasında cookie nizi bulun ve cookie: den sonrasını kopyalayın ve headers.conf dosyasındaki your_cookie_value yerine koyun.
8. followall.sh i çalıştırın. 0 çıktıları takip başarılı 4 çıktısı başarısız anlamına geliyor.
