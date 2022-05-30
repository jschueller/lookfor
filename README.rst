=======
lookfor
=======

.. image:: https://badge.fury.io/py/lookfor.svg
        :target: https://badge.fury.io/py/lookfor

Search magic extension for IPython interpreter

Updated from the original lookfor magic from 0.13.X branch:

https://github.com/ipython/ipython/blob/0.13.x/IPython/quarantine/ipy_lookfor.py

Install
-------

You can install or upgrade via pip::

    $ pip install -U lookfor

or directly from the repository using the `%install_ext` magic command::

.. code-block:: python

    %install_ext https://raw.github.com/jschueller/lookfor/master/lookformagic.py


Usage
-----

.. code-block:: python

    %load_ext lookfor
    %lookfor transpose scipy

    Search results for 'transpose'
    ------------------------------
    scipy.ma.transpose
        Permute the dimensions of an array.
    scipy.chararray.transpose
        a.transpose(*axes)
    scipy.cov
        Estimate a covariance matrix, given data.
    scipy.transpose
        Permute the dimensions of an array.
    scipy.einsum
        Evaluates the Einstein summation convention on the operands.
    scipy.loadtxt
        Load data from a text file.
    scipy.matrix.getT
        Returns the transpose of the matrix.

