.. GraphST documentation master file, created by
   sphinx-quickstart on Thu Sep 16 19:43:51 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Installation
============

The GraphST package is developed based on the pytorch framework and can be implemented on both GPU and CPU. 
We recommend running the package on GPU. Please ensure that pytorch and CUDNN are installed correctly. To run GraphST, all dependencies included in the file 'requirement.txt' need to be installed. We provide two ways to install the package of GraphST.

Please note that the current GraphST version offers full support of Linux operating system. Further version for other operating systems would be released soon.

1. Python
---------------------

Dowloading the package from https://github.com/JinmiaoChenLab/GraphST/

.. code-block:: python

   pip install GraphST
   
   or

   git clone https://github.com/JinmiaoChenLab/GraphST.git
   
   cd GraphST
   
   python setup.py build
   
   python setup.py install --user

2. Anaconda
------------
For convenience, we suggest using a separate conda environment for running GraphST. Please ensure annaconda3 is installed.

Create conda environment and install GraphST package.

.. code-block:: python

   #create an environment called GraphST
   conda create -n GraphST python=3.8
   
   #activate your environment
   conda activate GraphST
   
   #install package
   
   pip install GraphST
   
   or 
   
   git clone https://github.com/JinmiaoChenLab/GraphST.git
   
   cd GraphST
   
   python setup.py build
   
   python setup.py install --user
   
   #To use the environment in jupyter notebook, add python kernel for this environment.

   pip install ipykernel

   python -m ipykernel install --user --name=GraphST
   
