lookfor
=======

Search magic extension for IPython interpreter

Updated for IPython 1.0 from the original lookfor magic from 0.13.X branch:
https://github.com/ipython/ipython/blob/0.13.x/IPython/quarantine/ipy_lookfor.py

Usage:
```
%load_ext lookfor
%lookfor transpose scipy
```

```
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
```
