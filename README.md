Tutorial on coherent X-ray imaging
==================================

Introduction
------------
Jupyter notebooks in Python to assist the tutorial on the basics of coherent X-ray imaging.
The present notebooks are intended for educational reasons only. They are not perfect, 
but they have been gradually improving. Apologies for possible mistakes and missing 
references. 

These three groups of notebooks divided into three folders: 
1) **FourierTransforms**: it contains notebooks to play with the Fourier transforms.
2) **Oversampling_CXDI**: it contains notebooks to understand the oversampling of the speckles and play with CDI phase retrieval.
3) **PIE**: it contains a notebook to understand ptychography and play with educational simulations.

It is important to mention that the Python codes concerning oversampling and CDI phase retrieval were
inspired by the "Tutorial in Diffraction Imaging" by Gösta Huldt and Filipe Maia
(originally in MATLAB), which was available until recently at:
http://xray.bmc.uu.se/~ekeberg/molbiofys/tutorial.pdf 

Modifications have been made to the original code for educational reasons, and 
Python compatibility. 

The Python implementation in the notebook concerning simulations of ptychography is inspired by 
the MATLAB code available in Appendix A of the Diploma thesis by 
Dr. Martin Dierolf, which is available here: 
https://www.psi.ch/sls/csaxs/PublicationsEN/thesis_dierolf.pdf

Getting started
---------------

Throughout this tutorial, we will run some Python scripts using Jupyter 
Notebook. You can either download the files from this Gitlab repository and copy them to 
a folder of your choice or, if you prefer, you can clone them by typing:

git clone  [https://github.com/jcesardasilva/coherex-ptycho-tomo](https://github.com/jcesardasilva/coherex-ptycho-tomo)

Once the files are in your computer, you can open Jupyter Notebook by:
- Windows: click on the Jupyter Notebook icon installed in the start menu.
- Linux/Mac OS: open the terminal and type jupyter notebook at the prompt.

Concerning the use of Jupyter Notebooks, the website:

https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html
 
shows how to install it and start it in the different Operational Systems (Linux/Mac OS, Windows). 
Some Python packages are also required: Numpy, IPython, Matplotlib, and scikit-image. 

Dependencies
------------
* python >= 3.6
* numpy
* matplotlib
* scikit-image
* scipy

If you do not have such packages installed, I recommend the installation via pip install:

pip3 install --user numpy, ipython, matplotlib, scikit-image, scipy

My Binder Jupyter HUB
---------------------
There is also a possibility to run the notebooks in MyBinder by clicking here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jcesardasilva/coherex-ptycho-tomo/HEAD)

