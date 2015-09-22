Class MailCore
=====================





* Class name: MailCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Mail.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L32)


Contents
--------

### Constants

* [TYPE_BOTH](#constant-TYPE_BOTH)
* [TYPE_HTML](#constant-TYPE_HTML)
* [TYPE_TEXT](#constant-TYPE_TEXT)

### Properties

* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$recipient](#property-$recipient)
* [$subject](#property-$subject)
* [$template](#property-$template)

### Methods

* [Send](#method-Send)
* [eraseAllLogs](#method-eraseAllLogs)
* [eraseLog](#method-eraseLog)
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





* Source: [classes/Mail.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L68).


### <a name="constant-TYPE_HTML"></a>TYPE_HTML

```php
const TYPE_HTML = 1
```





* Source: [classes/Mail.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L66).


### <a name="constant-TYPE_TEXT"></a>TYPE_TEXT

```php
const TYPE_TEXT = 2
```





* Source: [classes/Mail.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L67).


Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public integer $date_add
```





* Visibility: **public**
* Source: [classes/Mail.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L49).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'mail', 'primary' => 'id_mail', 'fields' => array('recipient' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'copy_post' => false, 'required' => true, 'size' => 126), 'template' => array('type' => self::TYPE_STRING, 'validate' => 'isTplName', 'copy_post' => false, 'required' => true, 'size' => 62), 'subject' => array('type' => self::TYPE_STRING, 'validate' => 'isMailSubject', 'copy_post' => false, 'required' => true, 'size' => 254), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false, 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false, 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Mail.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L54).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Mail.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L34).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/Mail.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L46).


### <a name="property-$recipient"></a>$recipient

```php
public string $recipient
```





* Visibility: **public**
* Source: [classes/Mail.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L37).


### <a name="property-$subject"></a>$subject

```php
public string $subject
```





* Visibility: **public**
* Source: [classes/Mail.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L43).


### <a name="property-$template"></a>$template

```php
public string $template
```





* Visibility: **public**
* Source: [classes/Mail.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L40).


Methods
-------


### <a name="method-Send"></a>Send

```php
mixed MailCore::Send(integer $id_lang, string $template, string $subject, string $template_vars, string $to, string $to_name, string $from, string $from_name, array $file_attachment, $mode_smtp, string $template_path, boolean $die, $id_shop, string $bcc, $reply_to)
```

Send Email



* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L87)


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
* $reply_to **mixed**



### <a name="method-eraseAllLogs"></a>eraseAllLogs

```php
mixed MailCore::eraseAllLogs()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L403)




### <a name="method-eraseLog"></a>eraseLog

```php
mixed MailCore::eraseLog($id_mail)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L398)


#### Arguments
* $id_mail **mixed**



### <a name="method-generateId"></a>generateId

```php
mixed MailCore::generateId($idstring)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Mail.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L472)


#### Arguments
* $idstring **mixed**



### <a name="method-isMultibyte"></a>isMultibyte

```php
mixed MailCore::isMultibyte($data)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Mail.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L483)


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
* Source: [classes/Mail.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L446)


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
* Source: [classes/Mail.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L492)


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
* Source: [classes/Mail.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Mail.php#L408)


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


