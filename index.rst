
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
 ``scikit-rf`` (aka skrf) is an Object Oriented approach to RF/Microwave engineering implemented in the Python programming language. See the
 `introduction <http://packages.python.org/scikit-rf/tutorials/introduction.html>`_ for a quick look at some of the features of ``scikit-rf``. 

--------------------------
Getting Started
--------------------------

.. raw:: html

   <div style="float: left; padding-right: 2em;">

Plot touchstone data on a smith chart, in 3 lines. 

::

   import skrf as rf
   ntwk = rf.Network('my_networks.s2p')
   ntwk.plot_s_smith()

For more information, tutorials, and 

examples, see the `docs <http://packages.python.org/scikit-rf/index.html>`_

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

* load touchstone (.s2p, s?p) files for data processing
* provides basic algebraic operations on networks' scattering parameters
* connect n-port networks
* de-embed 2-port networks
* plot network's scattering parameter data (dB, Phase (unwrapped), Smith chart)
* save plots in vector format for publication (a feature of matplotlib)
* 1-port calibration, given any number of standards (least squares)
* 2-port calibration with support for switch-terms.
* can be used with pyvisa for instrument control of some VNA's ( partial support for HP8510, HP8720, and R&S ZVA40 )
* circuit design
* provide basic TEM transmission line models, and some non-TEM transmission lines 



