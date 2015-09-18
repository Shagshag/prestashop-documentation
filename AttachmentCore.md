AttachmentCore
===============






* Class name: AttachmentCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $file

    public mixed $file





* Visibility: **public**


### $file_name

    public mixed $file_name





* Visibility: **public**


### $file_size

    public mixed $file_size





* Visibility: **public**


### $name

    public mixed $name





* Visibility: **public**


### $mime

    public mixed $mime





* Visibility: **public**


### $description

    public mixed $description





* Visibility: **public**


### $position

    public integer $position





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'attachment', 'primary' => 'id_attachment', 'multilang' => true, 'fields' => array('file' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 40), 'mime' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 128), 'file_name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 128), 'file_size' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### add

    mixed AttachmentCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed AttachmentCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### delete

    mixed AttachmentCore::delete()





* Visibility: **public**




### deleteSelection

    mixed AttachmentCore::deleteSelection($attachments)





* Visibility: **public**


#### Arguments
* $attachments **mixed**



### getAttachments

    mixed AttachmentCore::getAttachments($id_lang, $id_product, $include)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_product **mixed**
* $include **mixed**



### deleteProductAttachments

    boolean AttachmentCore::deleteProductAttachments($id_product)

Unassociate $id_product from the current object



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed** - &lt;p&gt;int&lt;/p&gt;



### attachProduct

    boolean AttachmentCore::attachProduct(integer $id_product)

associate $id_product to the current object.



* Visibility: **public**


#### Arguments
* $id_product **integer** - &lt;p&gt;id of the product to associate&lt;/p&gt;



### attachToProduct

    boolean AttachmentCore::attachToProduct($id_product, $array)

Associate an array of id_attachment $array to the product $id_product
and remove eventual previous association



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_product **mixed**
* $array **mixed**



### getProductAttached

    mixed AttachmentCore::getProductAttached($id_lang, $list)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $list **mixed**


