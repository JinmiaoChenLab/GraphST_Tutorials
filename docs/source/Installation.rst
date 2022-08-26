.. DeepST documentation master file, created by
   sphinx-quickstart on Thu Sep 16 19:43:51 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Installation
============

The DeepST package is developed based on the pytorch framework and can be implemented on both GPU and CPU. 
We recommend running the package on GPU first. Please ensure that pytorch and CUDNN are installed correctly. To run DeepST, all dependencies included in the file requirement.txt need to be installed. We provide two ways to install the package of DeepST.

Please note that the current DeepST version only offers support of Linux operating system. Further version for other operating systems would be released soon.

1. Python
---------------------

Dowloading the package from https://github.com/JinmiaoChenLab/DeepST/

.. code-block:: python

   git clone https://github.com/JinmiaoChenLab/DeepST
   
   cd DeepST
   
   python setup.py build
   
   python setup.py install --user

2. Anaconda
------------
For convenience, we suggest using a separate conda environment for running DeepST. Please ensure annaconda3 is installed.

Create conda environment and install DeepST package.

.. code-block:: python

   #create an environment called DeepST
   conda create -n DeepST python=3.8
   
   #activate your environment
   conda activate DeepST
   
   #install package
   git clone https://github.com/JinmiaoChenLab/DeepST
   
   cd DeepST-main 
   
   python setup.py build
   
   python setup.py install --user
   
   #To use the environment in jupyter notebook, add python kernel for this environment.

   pip install ipykernel

   python -m ipykernel install --user --name=DeepST
   
