Usage
==============

.. code-block:: python

  from libenum import EnumBase


  class Color(EnumBase):

      red = 1
      blue = 2


  assert Color.get_name(Color.red) == 'red'
  assert Color.get_value(Color.get_name(Color.red)) == Color.red
