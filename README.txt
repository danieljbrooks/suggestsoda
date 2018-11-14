Suggest Soda

This package provides recommendations on which brand of soda to purchase.

pip install suggestsoda

usage:
  import suggestsoda as soda

  soda.recommend()

  soda.avoid()


The source distribution was created using sdist:

python setup.py sdist


The package was uploaded to PyPI using twine:

twine upload dist/*