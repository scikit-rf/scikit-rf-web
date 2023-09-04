
.. raw:: html

   <style type="text/css">
     h1 {
         display: none;
         margin: 0;
         padding: 0;
     }
   </style>


----------
Install
----------

.. |pypi| image:: https://img.shields.io/pypi/pyversions/scikit-rf
    :alt: PyPI - Python Version

.. |version| image:: https://img.shields.io/pypi/v/scikit-rf
    :alt: PyPI - Version

**scikit-rf** is supported and tested on |pypi|.

Current version of **scikit-rf** is |version|. There are several ways to install **scikit-rf**, listed below. 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
anaconda (recommended)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The easiest way to install scikit-rf is to first install 
`anaconda <http://continuum.io/downloads>`_. Once anaconda is installe,  you can 
install scikit-rf from the `conda-forge <https://conda-forge.github.io/>`_ channel by entering the following into a terminal::

    conda install -c conda-forge  scikit-rf
    

~~~~~~~~~~~~~~~~
pip
~~~~~~~~~~~~~~~~

If you dont want to install anaconda, you can use  `pip`::

    pip install scikit-rf

**scikit-rf** does not install all optional dependencies by default, but if you need some of them just do ::
    
    pip install scikit-rf[plot,visa,xlsx,netw]

or just a subset of them. 


~~~~~~~~~~~
git
~~~~~~~~~~~

The bleeding-edge development version of **scikit-rf** may be installed using::
    
    
    git clone https://github.com/scikit-rf/scikit-rf.git
    cd scikit-rf
    pip install .


