Product
=======

Product is a central part of database. Product mean industrial products, product's family, materials and other types of productions.

Each product can have a list of :doc:`properties</property>`.

Each product should be assigned to :doc:`category</catalog>`.

Product code and name
---------------------

Product short name (code) are optional. Use it for common abbreviation or system identifier of product.

Name is required field and contain full name of product.

Example - look at `PVC <http://www.naiveshark.com/product/product/159/>`_ page. ``PVC`` is a short name, ``Polyvinyl chloride`` - full name.

.. Note::
   Use short name and full name for correct, regular naming and local codes for organization-specific trade-names!   
   
Product templates and inheriting
--------------------------------

Product properties
------------------

Product measurable and enumerable properties.

Measurable parameters
^^^^^^^^^^^^^^^^^^^^^
* :doc:`Measurable property type</property>`
* Amount (integer, float, fraction, proportion) with optional equality type ( = equal by default, =< great or equal, < great )
* Maximum amount (integer or float)
* Engineering tolerance (integer or float)
* Unit

Amount can be:

======================  ==========  ==========
Numerical type          Example 1   Example 2
======================  ==========  ==========
Integer                 125         -15487000
Float                   154.48      -7e8
Fraction                1/9         -4 3/4
Proportion              1:8         7:9
======================  ==========  ==========

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

Linked orgs
-----------

List of organizations, linked with product - manufacturers, sellers etc. Described in :doc:`Organization linked product</organization/Linked products>` page.
