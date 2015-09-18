AdminOutstandingControllerCore
===============






* Class name: AdminOutstandingControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \OrderInvoice $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminOutstandingControllerCore::__construct()





* Visibility: **public**




### initToolbar

    boolean AdminOutstandingControllerCore::initToolbar()

Toolbar initialisation



* Visibility: **public**




### printPDFIcons

    string AdminOutstandingControllerCore::printPDFIcons($id_invoice, $tr)

Column callback for print PDF incon



* Visibility: **public**


#### Arguments
* $id_invoice **mixed** - &lt;p&gt;integer Invoice ID&lt;/p&gt;
* $tr **mixed** - &lt;p&gt;array Row data&lt;/p&gt;



### printOutstandingCalculation

    mixed AdminOutstandingControllerCore::printOutstandingCalculation($id_invoice, $tr)





* Visibility: **public**


#### Arguments
* $id_invoice **mixed**
* $tr **mixed**



### renderView

    mixed AdminOutstandingControllerCore::renderView()

View render



* Visibility: **public**



