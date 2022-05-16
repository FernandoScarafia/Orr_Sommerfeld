.. Orr_Sommerfeld documentation master file, created by
   sphinx-quickstart on Mon May 16 09:58:19 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Orr_Sommerfeld documentation!
==============================================

It is a python_ package developed in order to solve the Orr Sommerfeld equations. It is free for the community and allows to calculate disturbances for 4 flows of interest: Poiseuille, Couette, Boundary Layer and jet. These perturbations can be used to analyze the phenomenon of the laminar-turbulent transition.

Useful links
------------

* `View on GitHub`_;
* `Suggestions for new features and bug report`_;

Installation
------------

It is possible to install using pip::

   pip install Orr_Sommerfeld
 
Technologies
------------
*Project is created with:
	* Numpy_
	* Scipy_
	* Pypi_ to publish Python package.

Examples
--------

* Importing the package in `Jupyter Notebook`_::

   from Orr_Sommerfeld import OS

* Can compute the spectrum of temporal and spatial eigenvalues and their respective perturbations using:::

   lam,u,v,w=OS.Orr_Sommerfeld_Temporal(N,R,alp,b,n,Np)
   lam,u,v,w=OS.Orr_Sommerfeld_Espacial(N,R,w,b,n,Np)


.. _`View on GitHub`: https://github.com/FernandoScarafia/Orr_Sommerfeld
.. _`Suggestions for new features and bug report`: https://github.com/FernandoScarafia/Orr_Sommerfeld/issues


.. _`Jupyter Notebook`: https://jupyter.org/
.. _Numpy: https://numpy.org/
.. _Scipy: https://scipy.org/
.. _Pypi: https://pypi.org/ 

Table of Content
==================

.. toctree::
   :maxdepth: 4
   :glob:
	
   tutorial
   
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
