Class AttachmentCore
=====================





* Class name: AttachmentCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Attachment.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$description](#property-$description)
* [$file](#property-$file)
* [$file_name](#property-$file_name)
* [$mime](#property-$mime)
* [$name](#property-$name)
* [$position](#property-$position)

### Methods

* [attachProduct](#method-attachProduct)
* [attachToProduct](#method-attachToProduct)
* [delete](#method-delete)
* [deleteProductAttachments](#method-deleteProductAttachments)
* [deleteSelection](#method-deleteSelection)
* [getAttachments](#method-getAttachments)
* [getProductAttached](#method-getProductAttached)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'attachment', 'primary' => 'id_attachment', 'multilang' => true, 'fields' => array('file' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 40), 'mime' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 128), 'file_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 128), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Attachment.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L41).


### <a name="property-$description"></a>$description

```php
public mixed $description
```





* Visibility: **public**
* Source: [classes/Attachment.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L33).


### <a name="property-$file"></a>$file

```php
public mixed $file
```





* Visibility: **public**
* Source: [classes/Attachment.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L29).


### <a name="property-$file_name"></a>$file_name

```php
public mixed $file_name
```





* Visibility: **public**
* Source: [classes/Attachment.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L30).


### <a name="property-$mime"></a>$mime

```php
public mixed $mime
```





* Visibility: **public**
* Source: [classes/Attachment.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L32).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Attachment.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L31).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Attachment.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L36).


Methods
-------


### <a name="method-attachProduct"></a>attachProduct

```php
boolean AttachmentCore::attachProduct(integer $id_product)
```

associate $id_product to the current object.



* Visibility: **public**
* Source: [classes/Attachment.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L123)


#### Arguments
* $id_product **integer** - id of the product to associate



### <a name="method-attachToProduct"></a>attachToProduct

```php
boolean AttachmentCore::attachToProduct($id_product, $array)
```

associate an array of id_attachment $array to the product $id_product
and remove eventual previous association



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L144)


#### Arguments
* $id_product **mixed**
* $array **mixed**



### <a name="method-delete"></a>delete

```php
mixed AttachmentCore::delete()
```





* Visibility: **public**
* Source: [classes/Attachment.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L56)




### <a name="method-deleteProductAttachments"></a>deleteProductAttachments

```php
boolean AttachmentCore::deleteProductAttachments($id_product)
```

deassociate $id_product from the current object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L106)


#### Arguments
* $id_product **mixed** - int



### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed AttachmentCore::deleteSelection($attachments)
```





* Visibility: **public**
* Source: [classes/Attachment.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L73)


#### Arguments
* $attachments **mixed**



### <a name="method-getAttachments"></a>getAttachments

```php
mixed AttachmentCore::getAttachments($id_lang, $id_product, $include)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L84)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**
* $include **mixed**



### <a name="method-getProductAttached"></a>getProductAttached

```php
mixed AttachmentCore::getProductAttached($id_lang, $list)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/Attachment.php#L167)


#### Arguments
* $id_lang **mixed**
* $list **mixed**


