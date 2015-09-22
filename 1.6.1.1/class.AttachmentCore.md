Class AttachmentCore
=====================





* Class name: AttachmentCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Attachment.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L27)



Properties
----------

* [$definition](#property-$definition)
* [$description](#property-$description)
* [$file](#property-$file)
* [$file_name](#property-$file_name)
* [$file_size](#property-$file_size)
* [$mime](#property-$mime)
* [$name](#property-$name)
* [$position](#property-$position)

Methods
-------
* [add](#method-add)
* [attachProduct](#method-attachProduct)
* [attachToProduct](#method-attachToProduct)
* [delete](#method-delete)
* [deleteProductAttachments](#method-deleteProductAttachments)
* [deleteSelection](#method-deleteSelection)
* [getAttachments](#method-getAttachments)
* [getProductAttached](#method-getProductAttached)
* [update](#method-update)




Properties
----------


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'attachment', 'primary' => 'id_attachment', 'multilang' => true, 'fields' => array('file' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 40), 'mime' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 128), 'file_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 128), 'file_size' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Attachment.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L42)


### <a name="property-$description"></a>$description

    public mixed $description





* Visibility: **public**
* Source: [classes/Attachment.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L34)


### <a name="property-$file"></a>$file

    public mixed $file





* Visibility: **public**
* Source: [classes/Attachment.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L29)


### <a name="property-$file_name"></a>$file_name

    public mixed $file_name





* Visibility: **public**
* Source: [classes/Attachment.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L30)


### <a name="property-$file_size"></a>$file_size

    public mixed $file_size





* Visibility: **public**
* Source: [classes/Attachment.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L31)


### <a name="property-$mime"></a>$mime

    public mixed $mime





* Visibility: **public**
* Source: [classes/Attachment.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L33)


### <a name="property-$name"></a>$name

    public mixed $name





* Visibility: **public**
* Source: [classes/Attachment.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L32)


### <a name="property-$position"></a>$position

    public integer $position





* Visibility: **public**
* Source: [classes/Attachment.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L37)


Methods
-------


### <a name="method-add"></a>add

    mixed AttachmentCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/Attachment.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L58)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-attachProduct"></a>attachProduct

    boolean AttachmentCore::attachProduct(integer $id_product)

associate $id_product to the current object.



* Visibility: **public**
* Source: [classes/Attachment.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L136)


#### Arguments
* $id_product **integer** - id of the product to associate



### <a name="method-attachToProduct"></a>attachToProduct

    boolean AttachmentCore::attachToProduct($id_product, $array)

Associate an array of id_attachment $array to the product $id_product
and remove eventual previous association



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L156)


#### Arguments
* $id_product **mixed**
* $array **mixed**



### <a name="method-delete"></a>delete

    mixed AttachmentCore::delete()





* Visibility: **public**
* Source: [classes/Attachment.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L70)




### <a name="method-deleteProductAttachments"></a>deleteProductAttachments

    boolean AttachmentCore::deleteProductAttachments($id_product)

Unassociate $id_product from the current object



* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L119)


#### Arguments
* $id_product **mixed** - int



### <a name="method-deleteSelection"></a>deleteSelection

    mixed AttachmentCore::deleteSelection($attachments)





* Visibility: **public**
* Source: [classes/Attachment.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L88)


#### Arguments
* $attachments **mixed**



### <a name="method-getAttachments"></a>getAttachments

    mixed AttachmentCore::getAttachments($id_lang, $id_product, $include)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L98)


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**
* $include **mixed**



### <a name="method-getProductAttached"></a>getProductAttached

    mixed AttachmentCore::getProductAttached($id_lang, $list)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Attachment.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L181)


#### Arguments
* $id_lang **mixed**
* $list **mixed**



### <a name="method-update"></a>update

    mixed AttachmentCore::update($null_values)





* Visibility: **public**
* Source: [classes/Attachment.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Attachment.php#L64)


#### Arguments
* $null_values **mixed**


