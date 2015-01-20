Product
=======

Product is a central part of database. Product mean industrial products, product's family, materials and other types of productions.

Each product can have a list of :doc:`properties</property>`.

Each product should be assigned to :doc:`category</catalog>`.

Product templates and inheriting
--------------------------------

Product properties
------------------

Product measurable and enumerable properties.

Measurable parameters
^^^^^^^^^^^^^^^^^^^^^
* :doc:`Measurable property type</property>`
* Amount (numerical)
* Maximum amount (numerical)
* Engineering tolerance (numerical)
* Unit

Amount can be:

* integer value

Enumerable parameters
^^^^^^^^^^^^^^^^^^^^^

* :doc:`Enumerable property type</property>`
* Value

BOM
---

Bill of materials for this product.

* Position (optional)
* Subpoduct
* Amount
* Unit (optional)

Related
-------
Each product can have a related - as accessory, repair part etc.