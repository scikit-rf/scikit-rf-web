
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
 **scikit-rf** (aka ``skrf``) is an Object Oriented approach to RF/Microwave engineering implemented in the Python programming language. See some of the `features`_ below and check out the   
 `introduction <http://www.scikit-rf.org/doc/dev/tutorials/introduction.html>`_ for a quick look at using **scikit-rf**. 

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

examples, see the :doc:`documentation`

.. raw:: html

   </div>

   <div class="gallery_image" style="margin-top: 0; margin-bottom: 1em;">
   <img src="_static/smith_chart.png"/>
   </div>

   <div style="clear: left;"/>


--------------------------
Help/Feedback/BUGs
--------------------------

* For questions about usage, suggestions, general feedback please see the `Mailing List <http://groups.google.com/group/scikit-rf>`_


* If you find a problem in scikit-rf, please post an issue to the `Issue Tracker <https://github.com/scikit-rf/scikit-rf/issues>`_

* Still need help? Contact me at **arsenovic at virginia.edu**



-------------
Features
-------------

* Read/Write touchstone (.s2p, s?p) files
* Basic algebraic operations on networks' scattering parameters
* Cascade/De-embed 2-port networks
* Connect n-port networks
* Plot network parameter data [s, y, z] in ( dB, Phase, Smith chart, ...)
* Save plots in vector format for publication (a feature of matplotlib)
* 1-port calibration, given any number of standards (least squares)
* 2-port calibration with support for switch-terms.
* Instrument control of some VNA's ( partial support for HP8510, HP8720, and R&S ZVA40 )
* Circuit synthesis
* Transmission line models



