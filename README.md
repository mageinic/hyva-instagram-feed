# Hyvä Instagram Feed

**Hyvä Instagram Feed is a part of MageINIC Instagram Feed extension that adds Hyvä features.** This extension extends Instagram Feed definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-instagram-feed

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Instagram Feed requires installing [MageINIC Instagram Feed](https://github.com/mageinic/instagram-feed) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/instagram-feed
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
