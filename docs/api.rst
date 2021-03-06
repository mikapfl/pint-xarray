API reference
=============
This page contains a auto-generated summary of ``pint-xarray``'s API.

.. autosummary::
   :toctree: generated/

   pint_xarray.unit_registry

Dataset
-------
.. autosummary::
   :toctree: generated/
   :template: autosummary/accessor_method.rst

   xarray.Dataset.pint.quantify
   xarray.Dataset.pint.dequantify
   xarray.Dataset.pint.to

DataArray
---------
.. autosummary::
   :toctree: generated/
   :template: autosummary/accessor_attribute.rst

   xarray.DataArray.pint.magnitude
   xarray.DataArray.pint.units
   xarray.DataArray.pint.dimensionality
   xarray.DataArray.pint.registry

.. autosummary::
   :toctree: generated/
   :template: autosummary/accessor_method.rst

   xarray.DataArray.pint.quantify
   xarray.DataArray.pint.dequantify
   xarray.DataArray.pint.to

Testing
-------

.. autosummary::
   :toctree: generated/

   pint_xarray.testing.assert_units_equal
