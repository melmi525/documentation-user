=================================
Using Pricelists in Point of Sale
=================================

You probably know the concept of happy hour. During a certain period of
time, the barman gives a discount on some drinks (usually 50% off or a
buy one get one free). When the period is over, everything goes back to
normal. But what is the link with Odoo?

In Odoo, you can set up happy hours. It’s one of the many possible uses
of *Pricelists*. Those *Pricelists* will allow the creation of
multiple prices for the same product: a regular one and a special one
for happy hours. Available in the *PoS* app, those are really
convenient.

Set up Pricelists
=================

To set up a *Pricelist*, go to :menuselection:`Point of Sale --> Configuration --> Configuration` 
and enable the *Pricelist* feature. Then, go to :menuselection:`Point of Sale --> Configuration 
--> Point of Sale` and enable the *Pricelist* for the *PoS*.

.. image:: media/pricelists_01.png
   :align: center

Now, you can create *Pricelists* by clicking on the *Pricelists* link. 
Then, set it up by choosing the product category you want to include in your happy hour 
and the discount.

.. image:: media/pricelists_02.png
   :align: center

Go back to your *PoS* settings and add the Happy Hour pricelist to the
list. You can even choose a default pricelist if needed.

.. image:: media/pricelists_03.png
   :align: center

In the *PoS* interface, a new button appears, allowing you to choose
between the different *pricelists* you added before.

.. image:: media/pricelists_04.png
   :align: center

.. seealso::
   * :doc:`../../sales/products_prices/prices/pricing`