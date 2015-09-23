Class MailCore
=====================





* Class name: MailCore
* Source: [classes/Mail.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Mail.php#L33)


Contents
--------

### Constants

* [TYPE_BOTH](#constant-TYPE_BOTH)
* [TYPE_HTML](#constant-TYPE_HTML)
* [TYPE_TEXT](#constant-TYPE_TEXT)


### Methods

* [Send](#method-Send)
* [l](#method-l)
* [sendMailTest](#method-sendMailTest)


Constants
----------


### <a name="constant-TYPE_BOTH"></a>TYPE_BOTH

```php
const TYPE_BOTH = 3
```





* Source: [classes/Mail.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Mail.php#L37).


### <a name="constant-TYPE_HTML"></a>TYPE_HTML

```php
const TYPE_HTML = 1
```





* Source: [classes/Mail.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Mail.php#L35).


### <a name="constant-TYPE_TEXT"></a>TYPE_TEXT

```php
const TYPE_TEXT = 2
```





* Source: [classes/Mail.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Mail.php#L36).




Methods
-------


### <a name="method-Send"></a>Send

```php
mixed MailCore::Send($id_lang, $template, $subject, $templateVars, $to, $toName, $from, $fromName, $fileAttachment, $modeSMTP, $templatePath, $die)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Mail.php#L39)


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
* Source: [classes/Mail.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Mail.php#L264)


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
* Source: [classes/Mail.php line 220](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Mail.php#L220)


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


