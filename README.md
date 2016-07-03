# Magento 2 Türkçe Dil Paketi

Magento2 için Türkçe Dil Paketi

Magento2 içinde standart olarak gelen tüm tercüme dosyaları derlenmiş ve bu paket oluşturulmuştur.
<img src="https://i.snag.gy/DUwmVy.jpg">

# Kurulum
 - Tüm dosyaları `/app/i18n/hidonet/tr_TR/` klasörüne kopyalayın

( Unix/Linux/MacOSX için ) 
Daha sonra konsoldan sitenizin root klasörüne geçerek aşağıdaki komutları çalıştırın:
```bash
rm pub/static/frontend/Magento/luma/tr_TR/js-translation.json
php bin/magento setup:static-content:deploy tr_TR
php bin/magento setup:upgrade
rm -rf var/di
php bin/magento setup:di:compile
```

# Composer ile kurulum
```bash
composer require hidonet/magento2-language-tr_tr
rm pub/static/frontend/Magento/luma/tr_TR/js-translation.json
php bin/magento setup:static-content:deploy tr_TR
```

# Hata bildirimi

Gördüğünüz tercüme hatalarını hidonet@gmail.com'a iletebilirsiniz...

-----------------------------------------------------------------

# Magento 2 Turkish Language Pack

Magento2 Turkish Translation

We've combined all English translation files and translated to Turkish
<img src="https://i.snag.gy/DUwmVy.jpg">

# Installation
 - Copy all files to `/app/i18n/hidonet/tr_TR/` directory

( For Unix/Linux/MacOSX ) 
Go to your root folder of your magento site and run these commands :
```bash
rm pub/static/frontend/Magento/luma/tr_TR/js-translation.json
php bin/magento setup:static-content:deploy tr_TR
php bin/magento setup:upgrade
rm -rf var/di
php bin/magento setup:di:compile
```

# Installation with composer
```bash
composer require hidonet/magento2-language-tr_tr
rm pub/static/frontend/Magento/luma/tr_TR/js-translation.json
php bin/magento setup:static-content:deploy tr_TR
```

# Error reporting

Please send errors to hidonet@gmail.com...
