Class MailCore
=====================





* Class name: MailCore
* Source: [classes/Mail.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Mail.php#L33)


Contents
--------



### Methods

* [Send](#method-Send)
* [l](#method-l)
* [sendMailTest](#method-sendMailTest)






Methods
-------


### <a name="method-Send"></a>Send

```php
mixed MailCore::Send($id_lang, $template, $subject, $templateVars, $to, $toName, $from, $fromName, $fileAttachment, $modeSMTP, $templatePath, $die)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Mail.php#L35)


#### Arguments
* $id_lang **mixed**
* $template **mixed**
* $subject **mixed**
* $templateVars **mixed**
* $to **mixed**
* $toName **mixed**
* $from **mixed**
* $fromName **mixed**
* $fileAttachment **mixed**
* $modeSMTP **mixed**
* $templatePath **mixed**
* $die **mixed**



### <a name="method-l"></a>l

```php
mixed MailCore::l(string $string, $id_lang, \Context $context)
```

This method is used to get the translation for email Object.

For an object is forbidden to use htmlentities,
we have to return a sentence with accents.

* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Mail.php#L257)


#### Arguments
* $string **string** - raw sentence (write directly in file)
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-sendMailTest"></a>sendMailTest

```php
mixed MailCore::sendMailTest($smtpChecked, $smtpServer, $content, $subject, $type, $to, $from, $smtpLogin, $smtpPassword, $smtpPort, $smtpEncryption)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/Mail.php#L213)


#### Arguments
* $smtpChecked **mixed**
* $smtpServer **mixed**
* $content **mixed**
* $subject **mixed**
* $type **mixed**
* $to **mixed**
* $from **mixed**
* $smtpLogin **mixed**
* $smtpPassword **mixed**
* $smtpPort **mixed**
* $smtpEncryption **mixed**


