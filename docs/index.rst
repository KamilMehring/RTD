Nagłówek 1 poziom
=====================

Nagłówek 2 poziom
------------------

.. _startmydocs:

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled 

Nagłówek 3 poziom
~~~~~~~~~~~~~~~~~~

.. note::

  Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
   

Nagłówek 4 poziom 
"""""""""""""""""""

.. tip::
  Lorem Ipsum is simply dummy text of the printing and typesetting industry.


Link Zewnętrzny `Google <https://www.google.com/>`_
 .. _Python: https://www.python.org



.. code-block:: rst
   :caption: docs/author.rst

.. code:: javascript

  let x = myFunction(4, 3);
  function myFunction(a, b) {
   return a * b;
   }


.. code-block:: console

  sudo apt install python3-pip

Link Wewnętrzny 
:doc:`about.rst`

* Lista wypunktowana 
* Lista wypunktowana 
* Lista wypunktowana 

1. Lista numerowana 
#. element listy
#. element listy
#. element listy


.. image:: img/logo.png
:alt: tekst do obrazka
 


.. table:: Table
   :widths: auto

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

.. toctree::
    
    about.rst
    author.rst