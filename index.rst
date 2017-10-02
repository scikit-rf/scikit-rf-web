.. raw:: html

   <style type="text/css">
     h1 {
         display: none;
         margin: 0;
         padding: 0;
     }
   </style>

   
======
Index
======


------------
Description
------------

**scikit-rf** (aka ``skrf``) 
is an Open Source, BSD-licensed package for  RF/Microwave engineering implemented in the Python programming language. It provides a modern, object-oriented library  for network analysis and calibration which is both flexible and scalable.  See some of the `features`_ below and check out the  `Documentation <http://scikit-rf.readthedocs.org/>`_ or `Examples <http://nbviewer.ipython.org/github/scikit-rf/examples/blob/master/index.ipynb>`_ for a more in-depth look at  **scikit-rf**. 

--------------------------
Getting Started
--------------------------

.. raw:: html

   <div style="float: left; padding-right: 2em;">

Plot touchstone data on a smith chart, in **3 lines**. 

::

   import skrf as rf
   ntwk = rf.Network('ring slot.s2p')
   ntwk.plot_s_smith()

For more information, tutorials, and 

examples, see the `Documentation <http://scikit-rf.readthedocs.org/>`_

.. raw:: html

   </div>

   <div class="gallery_image" style="margin-top: 0; margin-bottom: 1em;">
   <img src="_static/smith_chart.png"/>
   </div>

   <div style="clear: left;"/>






--------------------------
Some Examples 
--------------------------

.. raw:: html
   :file: carousel_simple.html
   
|




-------------
Features
-------------

* Microwave Network Operations:
    * Read/Write touchstone (.s2p, s?p) files
    * Arithmetic operations on scattering parameters
    * Cascade/De-embed 2-port networks
    * Frequency and port slicing and  concatenation.
    * Connect n-port networks
    * s/z/y/abcd/t - parameter conversion
* Sets of Networks:
    * Statistical properties of NetworkSets 
    * Methods to sort and visualize set behavior
* GUI support through `qtapps`_ 
    * modular, re-useable apps
    * supports  data retrieval, plotting,  calibration and more. 
* Plotting abilities:
    * Rectangular Plots ( dB, mag, Phase, group delay)
    * Smith Chart
    * Automated Uncertainty bounds
* Offline Calibration:
   * One-Port: SOL, Least Squares, SDDL
   * Two-Port: TRL, Multiline TRL, SOLT, Unknown Thru,  8/16-Term
   * Partial : Enhanced Response, One-Port Two-Path
* Virtual Instruments (completeness varies by model)
    * VNAs: PNA, PNAX, ZVA, HP8510, HP8720
    * SA: HP8500
    * Others: ESP300
* Transmission Line Physics: 
    * Coax, CPW, Freespace, RectangularWaveguide, DistributedCircuit


--------------------------
Help/Feedback/BUGs
--------------------------

* For questions about usage, suggestions, general feedback please see the `Mailing List <http://groups.google.com/group/scikit-rf>`_


* If you find a problem in scikit-rf, please post an issue to the `Issue Tracker <https://github.com/scikit-rf/scikit-rf/issues>`_

* Still need help? Contact me at **alexanderarsenovic at gmail.com**




.. _qtapps: qtapps.html
