StockMvtReasonCore
===============






* Class name: StockMvtReasonCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public integer $id





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $sign

    public integer $sign





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $deleted

    public boolean $deleted





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'stock_mvt_reason', 'primary' => 'id_stock_mvt_reason', 'multilang' => true, 'fields' => array('sign' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 255)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'stock_movement_reasons', 'objectNodeName' => 'stock_movement_reason', 'fields' => array('sign' => array()))





* Visibility: **protected**


Methods
-------


### getStockMvtReasons

    array StockMvtReasonCore::getStockMvtReasons(integer $id_lang, integer $sign)

Gets Stock Mvt Reasons



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer**
* $sign **integer** - &lt;p&gt;Optionnal&lt;/p&gt;



### getStockMvtReasonsWithFilter

    mixed StockMvtReasonCore::getStockMvtReasonsWithFilter(integer $id_lang, array $ids_ignore, integer $sign)

Same as StockMvtReason::getStockMvtReasons(), ignoring a specific lists of ids



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer**
* $ids_ignore **array**
* $sign **integer** - &lt;p&gt;optional&lt;/p&gt;



### exists

    boolean StockMvtReasonCore::exists(integer $id_stock_mvt_reason)

For a given id_stock_mvt_reason, tells if it exists



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_stock_mvt_reason **integer**


