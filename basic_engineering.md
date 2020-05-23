# Basic Engineering for Data Science

## Contents

1. [Python distribution and package managers](#python-distribution-and-package-managers)
    1. [Anaconda](#anaconda)
    2. [Pip](#pip)
    3. [Conda](#conda)
2. [Python](#Python)
    1. [Standard Python Library](#standard-python-library)
    2. [Numpy](#numpy)
    3. [Pandas](#pandas)
    4. [Code style](#code-style)
3. [Jupyter Notebook](#jupyter-notebook)
    1. [Google Colab](#google-colab)

## Introduction

In this module we cover data science toolset and basics needed to complete the course. We start with Python distribution and installation of one. Then briefly go through the language and frequently used packages. After that learn what is and how to use Jupyter Notebook and one of its variations - the Google Colab. You can skip any part, if you feel confident about it, or return to some pages when you need to later in the course.

## Python distribution and package managers
### Anaconda

There are multiple ways to install Python. The suggested one is to install **Anaconda** distribution, which comes with a set of pre-installed libraries for data science. Although it's a good go-to option for newcomers, one can prefer to install miniconda distribution and all needed packages themselves.

> To learn more and install Anaconda distribution go through [this page][anaconda-link] (recommended). To install more light-weighted Miniconda distribution you need [this page][miniconda-link]

### Pip
Data Science comes with many packages. The most popular way to install everything is via **pip**. Basic usage of it can be found [here][pip-link].

### Conda
Most data science packages can be installed via pip. However, some of them can have external  Java, C, or other dependencies. While pip is a Python package manager, **conda** is a package manager for everything and so can be used to install all needed dependencies. 

If there is a possibility to install a package via conda instead of pip, you should go for it. Chances are it will work right out of the box. To learn more about conda and how to use it look at [this][conda-link] official tutorial or [this][conda-more-link] which is a bit more comprehensive.

> (_optional_) There are more about pip and conda differences. If you want to learn more, look at this [page][conda-pip-diff-link] on the topic.

## Python

Depending on the task people use other languages like R, Java, or C++ for Data Science. However, the best one in terms of available packages, simplicity, and power is **Python**. This course is written and intended to be taken in Python.

### Standard Python Library
There are many packages in the Python standard library and it's good to know what exists. [This][tour-link] is a brief tour through Python stdlib. [Here][builtins-link] you can find some handy and frequently used built-in functions.

> (_optional_) When working with text it is very useful to use **re** module for regular expressions. You can look at it now or come back during the module related to text classification.

### Numpy

[**Numpy**][numpy-link] is a basis for many data science packages. It's important to understand the core basis of the library and how to use it.

### Pandas

**Pandas** is a well-developed and the most popular tool for data wrangling in Python. It shares many principles with Numpy. A short introduction to Pandas can be found [here][pandas-link], but don't stop on that. Pandas will be used in every module of this course.

### Code Style

Luckily, there are written guidelines for Python. You can find them [here][codestyle-link]. Clear code is as important as other results of data scientist's work.

## Jupyter Notebook

Instead of developing in IDE data scientists prefer interactive environment for visualization and quick prototyping. One such environment is a **Jupyter Notebook**. The official documentation has a good starting [tutorial][jupyter-tutorial-link].

Most notable pages of Jupyter Notebook [documentation][jupyter-docs-link]:
- The Jupyter Notebook
- User interface components
- Notebook Examples
- What to do when things go wrong

### Google Colab

**Google Colab** provides the same functionality as Jupyter notebook and extends it. Most popular data science tools are pre-installed on Colab and can be used right away. It's good for prototyping and training of simple neural networks since Google provides **free GPU instances** on Colab. See the Colab [introduction notebook][colab-link] to learn more.

#### Access data from Google Drive
One convenient way to get data on Colab is to access it directly from Drive. You may want to read ___Mounting Google Drive locally___ section of this [notebook][colab-drive-link] to learn how. After mounting all files can be accessed as on a regular filesystem.

## Overview

At this point you must have learned the next things: 
- how to install Python to get started with Data Science
- Python package managers and how to install packages
- capabilities of Python stdlib and built-in functions
- Python code styling 
- vectorization principles of NumPy 
- main data wrangling tool
- usage of Jupyter notebook 
- capabilities of Google Colab

Check yourself and continue to the next module.


[anaconda-link]: https://www.anaconda.com/products/individual
[miniconda-link]: https://docs.conda.io/en/latest/miniconda.html
[pip-link]: https://pip.pypa.io/en/stable/quickstart/
[conda-link]: https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html
[conda-more-link]: https://geohackweek.github.io/Introductory/01-conda-tutorial/
[conda-pip-diff-link]: https://www.anaconda.com/blog/understanding-conda-and-pip
[stlib-link]: https://docs.python.org/3/library/index.html

[tour-link]: https://docs.python.org/3/tutorial/stdlib.html
[builtins-link]: https://docs.python.org/3/library/functions.html#built-in-funcs
[regex-link]: https://docs.python.org/3/library/re.html

[codestyle-link]: https://www.python.org/dev/peps/pep-0008/
[numpy-link]: https://numpy.org/devdocs/user/quickstart.html
[pandas-link]: https://pandas.pydata.org/docs/getting_started/10min.html

[jupyter-tutorial-link]: https://jupyter-notebook.readthedocs.io/en/stable/notebook.html
[jupyter-docs-link]: https://jupyter-notebook.readthedocs.io/en/stable/index.html

[colab-link]: https://colab.research.google.com/notebooks/intro.ipynb
[colab-drive-link]: https://colab.research.google.com/notebooks/io.ipynb#scrollTo=u22w3BFiOveA