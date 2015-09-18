AddressCore
===============

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.


* Class name: AddressCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_customer

    public integer $id_customer = null





* Visibility: **public**


### $id_manufacturer

    public integer $id_manufacturer = null





* Visibility: **public**


### $id_supplier

    public integer $id_supplier = null





* Visibility: **public**


### $id_warehouse

    public integer $id_warehouse = null





* Visibility: **public**


### $id_country

    public integer $id_country





* Visibility: **public**


### $id_state

    public integer $id_state





* Visibility: **public**


### $country

    public string $country





* Visibility: **public**


### $alias

    public string $alias





* Visibility: **public**


### $company

    public string $company





* Visibility: **public**


### $lastname

    public string $lastname





* Visibility: **public**


### $firstname

    public string $firstname





* Visibility: **public**


### $address1

    public string $address1





* Visibility: **public**


### $address2

    public string $address2





* Visibility: **public**


### $postcode

    public string $postcode





* Visibility: **public**


### $city

    public string $city





* Visibility: **public**


### $other

    public string $other





* Visibility: **public**


### $phone

    public string $phone





* Visibility: **public**


### $phone_mobile

    public string $phone_mobile





* Visibility: **public**


### $vat_number

    public string $vat_number





* Visibility: **public**


### $dni

    public string $dni





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


### $_idZones

    protected mixed $_idZones = array()





* Visibility: **protected**
* This property is **static**.


### $_idCountries

    protected mixed $_idCountries = array()





* Visibility: **protected**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'address', 'primary' => 'id_address', 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_manufacturer' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_supplier' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_warehouse' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId', 'copy_post' => false), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId'), 'alias' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'company' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'lastname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'firstname' => array('type' => self::TYPE_STRING, 'validate' => 'isName', 'required' => true, 'size' => 32), 'vat_number' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'address1' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'required' => true, 'size' => 128), 'address2' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'size' => 128), 'postcode' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode', 'size' => 12), 'city' => array('type' => self::TYPE_STRING, 'validate' => 'isCityName', 'required' => true, 'size' => 64), 'other' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage', 'size' => 300), 'phone' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 32), 'phone_mobile' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 32), 'dni' => array('type' => self::TYPE_STRING, 'validate' => 'isDniLite', 'size' => 16), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'copy_post' => false), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'copy_post' => false)))





* Visibility: **public**
* This property is **static**.


### $_includeVars

    protected mixed $_includeVars = array('addressType' => 'table')





* Visibility: **protected**


### $_includeContainer

    protected mixed $_includeContainer = false





* Visibility: **protected**


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'addresses', 'fields' => array('id_customer' => array('xlink_resource' => 'customers'), 'id_manufacturer' => array('xlink_resource' => 'manufacturers'), 'id_supplier' => array('xlink_resource' => 'suppliers'), 'id_warehouse' => array('xlink_resource' => 'warehouse'), 'id_country' => array('xlink_resource' => 'countries'), 'id_state' => array('xlink_resource' => 'states')))





* Visibility: **protected**


Methods
-------


### __construct

    mixed AddressCore::__construct(integer $id_address, $id_lang)

Build an address



* Visibility: **public**


#### Arguments
* $id_address **integer** - &lt;p&gt;Existing address id in order to load object (optional)&lt;/p&gt;
* $id_lang **mixed**



### add

    mixed AddressCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed AddressCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### delete

    mixed AddressCore::delete()





* Visibility: **public**




### getFieldsValidate

    array AddressCore::getFieldsValidate()

Returns fields required for an address in an array hash



* Visibility: **public**
* This method is **static**.




### validateController

    mixed AddressCore::validateController($htmlentities)





* Visibility: **public**


#### Arguments
* $htmlentities **mixed**



### getZoneById

    integer AddressCore::getZoneById(integer $id_address)

Get zone id for a given address



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_address **integer** - &lt;p&gt;Address id for which we want to get zone id&lt;/p&gt;



### isCountryActiveById

    integer AddressCore::isCountryActiveById(integer $id_address)

Check if country is active for a given address



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_address **integer** - &lt;p&gt;Address id for which we want to get country status&lt;/p&gt;



### isUsed

    integer AddressCore::isUsed()

Check if address is used (at least one order placed)



* Visibility: **public**




### getCountryAndState

    mixed AddressCore::getCountryAndState($id_address)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_address **mixed**



### addressExists

    boolean AddressCore::addressExists(integer $id_address)

Specify if an address is already in base



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_address **integer** - &lt;p&gt;Address id&lt;/p&gt;



### getFirstCustomerAddressId

    mixed AddressCore::getFirstCustomerAddressId($id_customer, $active)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**
* $active **mixed**



### initialize

    \Address AddressCore::initialize(integer $id_address, boolean $with_geoloc)

Initiliaze an address corresponding to the specified id address or if empty to the
default shop configuration



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_address **integer**
* $with_geoloc **boolean**



### getAddressIdBySupplierId

    integer AddressCore::getAddressIdBySupplierId(integer $id_supplier)

Returns id_address for a given id_supplier



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supplier **integer**



### aliasExist

    mixed AddressCore::aliasExist($alias, $id_address, $id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $alias **mixed**
* $id_address **mixed**
* $id_customer **mixed**



### getFieldsRequiredDB

    mixed AddressCore::getFieldsRequiredDB()





* Visibility: **public**



