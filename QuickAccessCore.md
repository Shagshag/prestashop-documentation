QuickAccessCore
===============






* Class name: QuickAccessCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\QuickAccess.php line 27





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\QuickAccess.php line 30


### $link

    public string $link





* Visibility: **public**
* This property is defined in classes\QuickAccess.php line 33


### $new_window

    public boolean $new_window





* Visibility: **public**
* This property is defined in classes\QuickAccess.php line 36


### $definition

    public mixed $definition = array('table' => 'quick_access', 'primary' => 'id_quick_access', 'multilang' => true, 'fields' => array('link' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl', 'required' => true, 'size' => 255), 'new_window' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\QuickAccess.php line 41


Methods
-------


### getQuickAccesses

    array QuickAccessCore::getQuickAccesses($id_lang)

Get all available quick_accesses



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\QuickAccess.php line 59


#### Arguments
* $id_lang **mixed**



### toggleNewWindow

    mixed QuickAccessCore::toggleNewWindow()





* Visibility: **public**
* This method is defined in classes\QuickAccess.php line 68



