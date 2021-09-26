# Introduction and preliminary activities

Please read carefully all the information below and follow all the instructions BEFORE the start of the School.

These instructions are very important as you should have all the preliminary tests done in your laptop BEFORE we start the School. Since time is short, during the School we will NOT be able to help with installation or laptop performance problems. All need to be well tested beforehand, so we can focus on coding and science.

This School focuses on python, we will use python3 as python2 is not supported anymore.

Similarly, we will use jupyter notebooks (.ipynbb) for the courses taught at this School.

- Jupyter notebooks are useful tools for learning programming because they provide a visual interface.
- You can see the results of your code live, instead of waiting till your script (.py) finishes running in a terminal.

To be able to use python and jupyter notebooks in your laptop, there are several options:

## Google Colab (see https://colab.research.google.com/):
One option is to use Google Colab, for which you would need a Gmail account. The advantage of using Google Colab is that all libraries are installed in a linux server remotely, so we don't need to worry about compatibility issues, etc. The disadvantage is that Colab provides limited memory resources and disc space, so you can only use it with small datasets.

## Anaconda/Miniconda (see https://anaconda.org/):
Another option is to have python (and all the libraries you need to analyse your dataset) installed in your laptop. This can also be done in many ways, but anaconda is now very popular because it provides good portability and an interface that allows the user to include extra kernels for other programming languages. Anaconda has the advantage that you have all the code you need locally in your laptop.

### How to install Anaconda?
Download Anaconda from this website: https://www.anaconda.com/products/individual, choose the package version that best suits the OS of your laptop.

### How do I test and use Anaconda?
For testing and customising your installation in Linux/MaxOSX laptops/PCs, follow these instructions:

1. conda create -n py37 python=3.7
2. conda activate py37
3. conda install jupyter
4. conda install numpy cython mpi4py git
5. jupyter notebook
6. Then, follow this:

https://github.com/wbandabarragan/EPIC_1/blob/main/Introduction/My_first_notebook.ipynb
 
