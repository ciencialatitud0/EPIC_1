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
Download Anaconda from this website: https://www.anaconda.com/products/individual, choose the package version that best suits the operating system (OS) of your laptop.

### How do I test and use Anaconda?

#### On Linux and MacOSX:
For testing and customising your installation on Linux/MaxOSX laptops/PCs, follow these instructions:

##### Option A: Intstallation from a terminal (recommended)

1. Open a terminal window.

2. Type the command below:
  $ conda --version
  conda 4.10.3

3. That means you have Anaconda 4.10.3 installed.

4. Now, let us check which environment you have:
  $ conda env list
  conda environments:
  base                  *  /Users/webb/opt/anaconda3

5. Let us know create a new environment with:
  $conda create -n py37 python=3.7

  $ conda env list
  conda environments:
  base                  *  /Users/webb/opt/anaconda3
  py37                     /Users/webb/opt/anaconda3/envs/py37

6. Now, we activate the environment:
  $ conda activate py37

  $ conda env list
  conda environments:
  base                     /Users/webb/opt/anaconda3
  py37                  *  /Users/webb/opt/anaconda3/envs/py37

7. Let us check with libraries are installed by default:
  $ conda list

8. Let's install a few extra libraries:
  $ conda install jupyter numpy cython mpi4py git

Type 'yes' to accept changes.

9. Let's now open a jupyter notebook:
  $ jupyter notebook

10. Then, follow this:


##### Option B: From within jupyter (if it was installed by default):

https://github.com/wbandabarragan/EPIC_1/blob/main/Introduction/My_first_notebook.ipynb
