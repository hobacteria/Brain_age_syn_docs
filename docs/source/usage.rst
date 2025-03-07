Usage
=====

.. _installation:

1.Installation
------------

To use *** , directely clone repository to your local enviroment.

.. code-block:: console

   git clone https://github.com/hobacteria/Brain_age_syn.git



.. _dependency:

2.Dependency & Python pakages
------------

There are several packages required to run the project pipeline.
We use Python 3.10 in our pipeline and strongly recommend running *** in a anaconda virtual environment to ensure clear dependency management.

.. code-block:: console

   pip install monai==1.4.0
   pip install nibabel
   pip install scikit-image
   pip install numpy==1.26.4
   pip install pandas==2.2.3
   
fastsurfer in docker hub in https://github.com/Deep-MI/FastSurfer

.. code-block:: console

   docker pull deepmi/fastsurfer:latest

pytorch with GPU in https://pytorch.org/get-started/locally/
