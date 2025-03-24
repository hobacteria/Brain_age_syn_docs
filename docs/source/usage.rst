Usage
=====

.. _installation:

1.Installation
------------

To use LS-MAT, directely clone repository to your local enviroment.

.. code-block:: console

   git clone https://github.com/hobacteria/Brain_age_syn.git



.. _dependency:

2.Dependency & Python pakages
------------

There are several main packages required to run the project pipeline.   

We use Python 3.10 in our pipeline and strongly recommend running LS-MAT in a anaconda virtual environment to ensure clear dependency management.   

For detialed package requirments, please check [here](https://github.com/hobacteria/Brain_age_syn/blob/master/requirements.txt)   

.. code-block:: console

   pip install monai==1.4.0
   pip install nibabel
   pip install scikit-image
   pip install numpy==1.26.4
   pip install pandas==2.2.3

Additinally, you need to install some software. 

Freesurfer 7.X in https://surfer.nmr.mgh.harvard.edu/fswiki/rel7downloads 

Fastsurfer in docker hub from https://github.com/Deep-MI/FastSurfer 

Docker 20.10.X in https://docs.docker.com/engine/release-notes/20.10/ 

pytorch with GPU in https://pytorch.org/get-started/locally/ 


.. code-block:: console

   docker pull deepmi/fastsurfer:latest

