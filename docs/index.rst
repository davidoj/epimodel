.. COVIDNPIs documentation master file, created by
   sphinx-quickstart on Wed Sep  9 10:48:13 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to COVIDNPIs' documentation!
=====================================

This is the documentation for the `COVIDNPIs project <https://github.com/epidemics/COVIDNPIs/tree/revisions>`_, Bayesian modelling the impact of non-pharmaceutical interventions (NPIs) on the rate of transmission of COVID-19 in 41 countries around the world. See the paper `The effectiveness of eight nonpharmaceutical interventions against COVID-19 in 41 countries <https://www.medrxiv.org/content/10.1101/2020.05.28.20116129v3>`_ by Brauner et. al. for details of the model.

COVIDNPIs provides a :ref:`data_preprocessor` for converting time-series case and death data along with NPI activation indicators to :ref:`PreprocessedData<preprocessed_data>` objects, ready to use for inference in any of several :ref:`NPI models<cm_model_zoo>`. In addition, the :ref:`model_parameters` module provides utilities for computing delay distributions, which can then be provided as initialisation parameters to the NPI models.

The :ref:`examples` walk through using the PreprocessedData object, initialising and running a model with custom delay parameters. Many pre-defined :ref:`experiments` are can also be run as scripts.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   examples
   module_documentation
   experiments
   reproduction



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`