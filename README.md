eksi-follow-all
=====
Eksi sozlukteki herkesi takip etmeye yarayan ufak bir shell scripti. 
⚠️Hesabinizin basina gelenlerden ben sorumlu degilim. Kullanmadan önce doğru cookieyi girdiğinize emin olun ve kullandığınız takdirde olası sonuçların sorumluluğunu üstlenin.⚠️
**(not: buyuk ihtimal basina bir sey gelecek)**

Nasil Kullanilir
--------------------------------------------------------------------------------

1. Repoyu clonelayın.
2. eksisozuk.com'u acin ve herkesi takip etmek istediginiz hesabinizla giris yapin.
3. Herhangi bir kullanicinin profiline girin.
4. ctrl+shift+j veya cmd+shift+j ile chrome dev toolsu acin.
5. Ustten network tabine girin, once kirmizi noktanin yanindaki clear tusuna basin sonra preserve log'u tickleyin.
6. Kullaniciyi takip edin sayilar?r=b seklinde bir istek goreceksiniz ona tiklayin.
7. Headerlari arasinda cookie nizi bulun ve cookie: den sonrasini kopyalayin ve headers.conf dosyasındaki your_cookie_value yerine koyun.
8. followall.sh i calistirin. 0 ciktilari takip basarili 4 ciktisi basarisiz anlamina geliyor.
