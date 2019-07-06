# drupal-console-fa
کنسول دروپال به زبان فارسی

## کاربرد

پروژه کنسول دروپال به صورت پیشفرض برای هر وبسایت دروپال ۸ به زبان انگلیسی نصب شده است.

برای نصب بسته کنسول دروپال به زبان فارسی دستورات زیر را اجرا کنید

```
$ composer require drupal/console-fa
```

### نصب کنسول دروپال

برای نصب نسخه مناسب از پروژه کنسول دروپال، دستور composer زیر را اجرا کنید

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### نصب راه‌انداز کنسول دروپال

راه‌انداز کنسول دروپال به منظور پیشگیری از اختلاف بین نسخه‌های ماژور و مینور در دروپال، همچنین بارگیری دستورات کنسول دروپال برای هر وبسایت دروپال ۸ ایجاد شده است.

با پیروی از دستورات زیر می‌توانید یک نسخه سراسری از راه‌انداز کنسول دروپال برای وبسایت‌های خود داشته باشید.

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# یا 
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### مشارکت

اگر قصد مشارکت در این ترجمه را دارید، باید گام‌های زیر را دنبال کنید

- فورک کردن این مخزن با استفاده از پیوند [https://github.com/hechoendrupal/drupal-console-fa#fork-destination-box](https://github.com/hechoendrupal/drupal-console-fa#fork-destination-box)
- شبیه‌سازی از مخزن فورک شده در رایانه شخصی خود
- برپایی upstream

به منظور بروزسانی با سایر مشارکت‌کنندگان باید مخزن خود را با استفاده از دستورات زیر برپا کنید

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-fa.git
```

برای دریافت آخرین مشارکت‌ها باید دستورات زیر را اجرا کنید

```
$ git fetch upstream
$ git merge upstream/master
```

پ.ن: به منظور پیشگیری از هرگونه اختلاف با سایر مشارکت‌کنندگان، ابتدا مخزن فورک شده خود را برای درخواست PR در ابتدای هر روز push کنید.
