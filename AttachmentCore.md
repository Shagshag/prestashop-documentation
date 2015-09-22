AttachmentCore
===============






* Class name: AttachmentCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Attachment.php line 27





Properties
----------


### $file

    public mixed $file





* Visibility: **public**
* This property is defined in classes\Attachment.php line 29


### $file_name

    public mixed $file_name





* Visibility: **public**
* This property is defined in classes\Attachment.php line 30


### $file_size

    public mixed $file_size





* Visibility: **public**
* This property is defined in classes\Attachment.php line 31


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in classes\Attachment.php line 32


### $mime

    public mixed $mime





* Visibility: **public**
* This property is defined in classes\Attachment.php line 33


### $description

    public mixed $description





* Visibility: **public**
* This property is defined in classes\Attachment.php line 34


### $position

    public integer $position





* Visibility: **public**
* This property is defined in classes\Attachment.php line 37


### $definition

    public mixed $definition = array('table' => 'attachment', 'primary' => 'id_attachment', 'multilang' => true, 'fields' => array('file' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 40), 'mime' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 128), 'file_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 128), 'file_size' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Attachment.php line 42


Methods
-------


### add

    mixed AttachmentCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\Attachment.php line 58


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed AttachmentCore::update($null_values)





* Visibility: **public**
* This method is defined in classes\Attachment.php line 64


#### Arguments
* $null_values **mixed**



### delete

    mixed AttachmentCore::delete()





* Visibility: **public**
* This method is defined in classes\Attachment.php line 70




### deleteSelection

    mixed AttachmentCore::deleteSelection($attachments)





* Visibility: **public**
* This method is defined in classes\Attachment.php line 88


#### Arguments
* $attachments **mixed**



### getAttachments

    mixed AttachmentCore::getAttachments($id_lang, $id_product, $include)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attachment.php line 98


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**
* $include **mixed**



### deleteProductAttachments

    boolean AttachmentCore::deleteProductAttachments($id_product)

Unassociate $id_product from the current object



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attachment.php line 119


#### Arguments
* $id_product **mixed** - &lt;p&gt;int&lt;/p&gt;



### attachProduct

    boolean AttachmentCore::attachProduct(integer $id_product)

associate $id_product to the current object.



* Visibility: **public**
* This method is defined in classes\Attachment.php line 136


#### Arguments
* $id_product **integer** - &lt;p&gt;id of the product to associate&lt;/p&gt;



### attachToProduct

    boolean AttachmentCore::attachToProduct($id_product, $array)

Associate an array of id_attachment $array to the product $id_product
and remove eventual previous association



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attachment.php line 156


#### Arguments
* $id_product **mixed**
* $array **mixed**



### getProductAttached

    mixed AttachmentCore::getProductAttached($id_lang, $list)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Attachment.php line 181


#### Arguments
* $id_lang **mixed**
* $list **mixed**


