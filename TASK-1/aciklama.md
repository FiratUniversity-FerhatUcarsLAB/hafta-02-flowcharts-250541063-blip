İsim - Soy isim :FATMA TÜRKMEN 
Öğrenci No:250541063

sistemin kısa açıklaması (maks. 5-6 satır)
ATM’den Para Çekme Algoritması Raporu
1. Giriş

Bu raporda, bir kullanıcının ATM (Automatik Para Çekme Makinesi) üzerinden para çekme işlemini gerçekleştirmesini sağlayan algoritmanın işleyişi açıklanmıştır. Algoritmanın amacı, kullanıcı doğrulamasını yaparak güvenli ve hatasız bir şekilde para çekme sürecini yönetmektir.

2. Algoritmanın Amacı

ATM’den para çekme algoritmasının temel amacı, kullanıcının kimlik doğrulamasını gerçekleştirdikten sonra, çekmek istediği tutarın hem kullanıcı bakiyesi hem de ATM nakit miktarı açısından uygunluğunu kontrol ederek işlemi güvenli biçimde tamamlamaktır.

3. Algoritmanın İşleyişi

Kullanıcı ATM’ye kartını takar.

Sistem kartın geçerliliğini kontrol eder.

Kullanıcıdan PIN (şifre) girişi istenir ve doğrulama yapılır. Yanlış girişlerde en fazla üç deneme hakkı tanınır; üç başarısız deneme sonunda kart bloke edilir.

Doğrulama başarılı olursa kullanıcı çekmek istediği tutarı girer.

Sistem, girilen tutarın geçerli bir değer olup olmadığını (örneğin 10 TL’nin katı) kontrol eder.

Kullanıcının hesabında yeterli bakiye olup olmadığı ve ATM’de yeterli miktarda banknot bulunup bulunmadığı kontrol edilir.

Tüm koşullar uygun ise kullanıcı hesabından tutar düşülür, ATM’den uygun banknotlar hazırlanır ve kullanıcıya teslim edilir.

İşlem sonunda bakiye güncellenir, isteğe bağlı olarak fiş yazdırılır ve kart kullanıcıya iade edilir.

Herhangi bir hata durumunda işlem iptal edilerek kullanıcı bilgilendirilir.

4. Sonuç

Bu algoritma, para çekme işlemini güvenli, hızlı ve hatasız biçimde gerçekleştirmeyi amaçlar. Doğru kimlik doğrulaması, bakiye kontrolü ve ATM para durumu kontrolleri sayesinde kullanıcı işlemleri güvenilir bir şekilde tamamlanır. Ayrıca, hata durumlarında sistem uygun uyarılarla kullanıcıyı bilgilendirerek işlem güvenliğini sağlar.
        
