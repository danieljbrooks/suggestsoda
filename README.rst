Suggest Soda
============

This package provides recommendations on which brand of soda to purchase.


Installing
----------

pip install suggestsoda


Example
-------

.. code-block:: text

    import suggestsoda as soda

    soda.recommend()

    soda.avoid()


Package Distribution
--------------------

The source distribution was created using sdist:

.. code-block:: text

	python setup.py sdist

The package was uploaded to PyPI using twine:

.. code-block:: text

	twine upload dist/*