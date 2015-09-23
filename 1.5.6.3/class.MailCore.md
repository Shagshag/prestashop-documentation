Class MailCore
=====================





* Class name: MailCore
* Source: [classes/Mail.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L32)


Contents
--------

### Constants

* [TYPE_BOTH](#constant-TYPE_BOTH)
* [TYPE_HTML](#constant-TYPE_HTML)
* [TYPE_TEXT](#constant-TYPE_TEXT)


### Methods

* [Send](#method-Send)
* [generateId](#method-generateId)
* [isMultibyte](#method-isMultibyte)
* [l](#method-l)
* [mimeEncode](#method-mimeEncode)
* [sendMailTest](#method-sendMailTest)


Constants
----------


### <a name="constant-TYPE_BOTH"></a>TYPE_BOTH

```php
const TYPE_BOTH = 3
```





* Source: [classes/Mail.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L36).


### <a name="constant-TYPE_HTML"></a>TYPE_HTML

```php
const TYPE_HTML = 1
```





* Source: [classes/Mail.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L34).


### <a name="constant-TYPE_TEXT"></a>TYPE_TEXT

```php
const TYPE_TEXT = 2
```





* Source: [classes/Mail.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L35).




Methods
-------


### <a name="method-Send"></a>Send

```php
mixed MailCore::Send(integer $id_lang, string $template, string $subject, string $template_vars, string $to, string $to_name, string $from, string $from_name, array $file_attachment, $mode_smtp, string $template_path, boolean $die, $id_shop, string $bcc)
```

Send Email



* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L55)


#### Arguments
* $id_lang **integer** - Language of the email (to translate the template)
* $template **string** - Template: the name of template not be a var but a string !
* $subject **string**
* $template_vars **string**
* $to **string**
* $to_name **string**
* $from **string**
* $from_name **string**
* $file_attachment **array** - Array with three parameters (content, mime and name). You can use an array of array to attach multiple files
* $mode_smtp **mixed**
* $template_path **string**
* $die **boolean**
* $id_shop **mixed**
* $bcc **string** - Bcc recipient



### <a name="method-generateId"></a>generateId

```php
mixed MailCore::generateId($idstring)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Mail.php line 392](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L392)


#### Arguments
* $idstring **mixed**



### <a name="method-isMultibyte"></a>isMultibyte

```php
mixed MailCore::isMultibyte($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L403)


#### Arguments
* $data **mixed**



### <a name="method-l"></a>l

```php
mixed MailCore::l(string $string, $id_lang, \Context $context)
```

This method is used to get the translation for email Object.

For an object is forbidden to use htmlentities,
we have to return a sentence with accents.

* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L361)


#### Arguments
* $string **string** - raw sentence (write directly in file)
* $id_lang **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-mimeEncode"></a>mimeEncode

```php
mixed MailCore::mimeEncode($string, $charset, $newline)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L420)


#### Arguments
* $string **mixed**
* $charset **mixed**
* $newline **mixed**



### <a name="method-sendMailTest"></a>sendMailTest

```php
mixed MailCore::sendMailTest($smtpChecked, $smtpServer, $content, $subject, $type, $to, $from, $smtpLogin, $smtpPassword, $smtpPort, $smtpEncryption)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.3/classes/Mail.php#L317)


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


