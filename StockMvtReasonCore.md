StockMvtReasonCore
===============






* Class name: StockMvtReasonCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\stock\StockMvtReason.php line 27





Properties
----------


### $id

    public integer $id





* Visibility: **public**
* This property is defined in classes\stock\StockMvtReason.php line 30


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\stock\StockMvtReason.php line 33


### $sign

    public integer $sign





* Visibility: **public**
* This property is defined in classes\stock\StockMvtReason.php line 36


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in classes\stock\StockMvtReason.php line 39


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in classes\stock\StockMvtReason.php line 42


### $deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in classes\stock\StockMvtReason.php line 45


### $definition

    public mixed $definition = array('table' => 'stock_mvt_reason', 'primary' => 'id_stock_mvt_reason', 'multilang' => true, 'fields' => array('sign' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 255)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\stock\StockMvtReason.php line 51


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'stock_movement_reasons', 'objectNodeName' => 'stock_movement_reason', 'fields' => array('sign' => array()))





* Visibility: **protected**
* This property is defined in classes\stock\StockMvtReason.php line 67


Methods
-------


### getStockMvtReasons

    array StockMvtReasonCore::getStockMvtReasons(integer $id_lang, integer $sign)

Gets Stock Mvt Reasons



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockMvtReason.php line 82


#### Arguments
* $id_lang **integer**
* $sign **integer** - &lt;p&gt;Optionnal&lt;/p&gt;



### getStockMvtReasonsWithFilter

    mixed StockMvtReasonCore::getStockMvtReasonsWithFilter(integer $id_lang, array $ids_ignore, integer $sign)

Same as StockMvtReason::getStockMvtReasons(), ignoring a specific lists of ids



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockMvtReason.php line 105


#### Arguments
* $id_lang **integer**
* $ids_ignore **array**
* $sign **integer** - &lt;p&gt;optional&lt;/p&gt;



### exists

    boolean StockMvtReasonCore::exists(integer $id_stock_mvt_reason)

For a given id_stock_mvt_reason, tells if it exists



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\stock\StockMvtReason.php line 132


#### Arguments
* $id_stock_mvt_reason **integer**


