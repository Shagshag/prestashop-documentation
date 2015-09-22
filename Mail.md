Mail
===============

DISCLAIMER

Do not edit or add to this file if you wish to upgrade this module to newer
versions in the future. If you wish to customize this module for your
needs please refer to http://doc.prestashop.com/display/PS15/Overriding+default+behaviors
#Overridingdefaultbehaviors-Overridingamodule%27sbehavior for more information.


* Class name: Mail
* Parent class: [MailCore](MailCore)
* This class is defined in [override/classes/Mail.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L14)



Constants
----------

* [TYPE_HTML](#constant-TYPE_HTML)
* [TYPE_TEXT](#constant-TYPE_TEXT)
* [TYPE_BOTH](#constant-TYPE_BOTH)

Properties
----------

* [$id](#property-$id)
* [$recipient](#property-$recipient)
* [$template](#property-$template)
* [$subject](#property-$subject)
* [$id_lang](#property-$id_lang)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)

Methods
-------
* [send](#method-send)
* [Send](#method-Send)
* [eraseLog](#method-eraseLog)
* [eraseAllLogs](#method-eraseAllLogs)
* [sendMailTest](#method-sendMailTest)
* [l](#method-l)
* [generateId](#method-generateId)
* [isMultibyte](#method-isMultibyte)
* [mimeEncode](#method-mimeEncode)


Constants
----------


### <a name="constant-TYPE_HTML"></a>TYPE_HTML

    const TYPE_HTML = 1



* This constant is defined in [override/classes/Mail.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L66)


### <a name="constant-TYPE_TEXT"></a>TYPE_TEXT

    const TYPE_TEXT = 2



* This constant is defined in [override/classes/Mail.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L67)


### <a name="constant-TYPE_BOTH"></a>TYPE_BOTH

    const TYPE_BOTH = 3



* This constant is defined in [override/classes/Mail.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L68)


Properties
----------


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* This property is defined in [override/classes/Mail.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L34)


### <a name="property-$recipient"></a>$recipient

    public string $recipient





* Visibility: **public**
* This property is defined in [override/classes/Mail.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L37)


### <a name="property-$template"></a>$template

    public string $template





* Visibility: **public**
* This property is defined in [override/classes/Mail.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L40)


### <a name="property-$subject"></a>$subject

    public string $subject





* Visibility: **public**
* This property is defined in [override/classes/Mail.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L43)


### <a name="property-$id_lang"></a>$id_lang

    public integer $id_lang





* Visibility: **public**
* This property is defined in [override/classes/Mail.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L46)


### <a name="property-$date_add"></a>$date_add

    public integer $date_add





* Visibility: **public**
* This property is defined in [override/classes/Mail.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L49)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'mail', 'primary' => 'id_mail', 'fields' => array('recipient' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'copy_post' => false, 'required' => true, 'size' => 126), 'template' => array('type' => self::TYPE_STRING, 'validate' => 'isTplName', 'copy_post' => false, 'required' => true, 'size' => 62), 'subject' => array('type' => self::TYPE_STRING, 'validate' => 'isMailSubject', 'copy_post' => false, 'required' => true, 'size' => 254), 'id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'copy_post' => false, 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false, 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [override/classes/Mail.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L54)


Methods
-------


### <a name="method-send"></a>send

    mixed Mail::send($id_lang, $template, $subject, $template_vars, $to, $to_name, $from, $from_name, $file_attachment, $mode_smtp, $template_path, $die, $id_shop, $bcc, $reply_to)





* Visibility: **public**
* This method is **static**.
* This method is defined in [override/classes/Mail.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L39)


#### Arguments
* $id_lang **mixed**
* $template **mixed**
* $subject **mixed**
* $template_vars **mixed**
* $to **mixed**
* $to_name **mixed**
* $from **mixed**
* $from_name **mixed**
* $file_attachment **mixed**
* $mode_smtp **mixed**
* $template_path **mixed**
* $die **mixed**
* $id_shop **mixed**
* $bcc **mixed**
* $reply_to **mixed**



### <a name="method-Send"></a>Send

    mixed MailCore::Send(integer $id_lang, string $template, string $subject, string $template_vars, string $to, string $to_name, string $from, string $from_name, array $file_attachment, $mode_smtp, string $template_path, boolean $die, $id_shop, string $bcc, $reply_to)

Send Email



* Visibility: **public**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L87)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language of the email (to translate the template)&lt;/p&gt;
* $template **string** - &lt;p&gt;Template: the name of template not be a var but a string !&lt;/p&gt;
* $subject **string**
* $template_vars **string**
* $to **string**
* $to_name **string**
* $from **string**
* $from_name **string**
* $file_attachment **array** - &lt;p&gt;Array with three parameters (content, mime and name). You can use an array of array to attach multiple files&lt;/p&gt;
* $mode_smtp **mixed**
* $template_path **string**
* $die **boolean**
* $id_shop **mixed**
* $bcc **string** - &lt;p&gt;Bcc recipient&lt;/p&gt;
* $reply_to **mixed**



### <a name="method-eraseLog"></a>eraseLog

    mixed MailCore::eraseLog($id_mail)





* Visibility: **public**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L402)


#### Arguments
* $id_mail **mixed**



### <a name="method-eraseAllLogs"></a>eraseAllLogs

    mixed MailCore::eraseAllLogs()





* Visibility: **public**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L407)




### <a name="method-sendMailTest"></a>sendMailTest

    mixed MailCore::sendMailTest($smtpChecked, $smtpServer, $content, $subject, $type, $to, $from, $smtpLogin, $smtpPassword, $smtpPort, $smtpEncryption)





* Visibility: **public**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L412)


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



### <a name="method-l"></a>l

    mixed MailCore::l(string $string, $id_lang, \Context $context)

This method is used to get the translation for email Object.

For an object is forbidden to use htmlentities,
we have to return a sentence with accents.

* Visibility: **public**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L450)


#### Arguments
* $string **string** - &lt;p&gt;raw sentence (write directly in file)&lt;/p&gt;
* $id_lang **mixed**
* $context **[Context](ContextCore)**



### <a name="method-generateId"></a>generateId

    mixed MailCore::generateId($idstring)





* Visibility: **protected**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L481)


#### Arguments
* $idstring **mixed**



### <a name="method-isMultibyte"></a>isMultibyte

    mixed MailCore::isMultibyte($data)





* Visibility: **public**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 492](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L492)


#### Arguments
* $data **mixed**



### <a name="method-mimeEncode"></a>mimeEncode

    mixed MailCore::mimeEncode($string, $charset, $newline)





* Visibility: **public**
* This method is **static**.
* This method is defined by [MailCore](MailCore)
* This method is defined in [override/classes/Mail.php line 503](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/override/classes/Mail.php#L503)


#### Arguments
* $string **mixed**
* $charset **mixed**
* $newline **mixed**


