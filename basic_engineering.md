# Machine Learning Engineering Fundamentals <!-- omit in toc -->

## Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Python distribution and package managers](#python-distribution-and-package-managers)
  - [Anaconda](#anaconda)
  - [Pip](#pip)
  - [Conda](#conda)
- [Python](#python)
  - [Standard Python Library](#standard-python-library)
  - [Numpy](#numpy)
  - [Pandas](#pandas)
  - [Code Style](#code-style)
- [Jupyter Notebook](#jupyter-notebook)
  - [Google Colab](#google-colab)
- [Exercises](#exercises)
- [Overview](#overview)

---

## Introduction

In this module, we cover data science toolset and basics needed to complete the course. We start with Python distribution and installation of one. Then briefly go through the language and frequently used packages. After that learn what is and how to use Jupyter Notebook and one of its variations - the Google Colab. You can skip any part, if you feel confident about it, or return to some pages when you need to later in the course.

---

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

---

## Python

Depending on the task people use other languages like R, Java, or C++ for Data Science. However, the best one in terms of available packages, simplicity, and power is **Python**. This course is written and intended to be taken in Python.

### Standard Python Library

There are many packages in the Python standard library and it's good to know what exists. [This][tour-link] is a brief tour through Python stdlib. [Here][builtins-link] you can find some handy and frequently used built-in functions.

> (_optional_) When working with text it is very useful to use **re** module for regular expressions. You can look at it now or come back during the module related to text classification.

### Numpy

[**Numpy**][numpy-link] is a basis for many data science packages. It's important to understand the core basis of the library and how to use it.

### Pandas

**Pandas** is a well-developed and the most popular tool for data wrangling in Python. It shares many principles with Numpy. A short introduction to Pandas can be found [here][pandas-link], but don't stop on that. Pandas will be used in every module of this course.

If you prefer video tutorials, there is a great series on Pandas [here][pandas-video-tutorial-link] which covers all base operations and common use cases.

### Code Style

Luckily, there are written guidelines for Python. You can find them [here][codestyle-link]. Clear code is as important as other results of data scientist's work.

---

## Jupyter Notebook

Instead of developing in IDE data scientists prefer interactive environment for visualization and quick prototyping. One such environment is a **Jupyter Notebook**. The official documentation has a good starting [tutorial][jupyter-tutorial-link].

You can find a video tutorial on the installation and usage of the notebooks [here][jupyter-video-tutorial-link]

Most notable pages of Jupyter Notebook [documentation][jupyter-docs-link]:

- The Jupyter Notebook
- User interface components
- Notebook Examples
- What to do when things go wrong

Jupyter Notebook is a powerful tool and has many extensions and capabilities except for running Python scripts. You can learn some advanced tricks [here][jypyter-advanced-tips-link]. They surely make your work more efficient and easy. Some notables are:

- shortcuts
- magic commands
- shell commands
- extensions

### Google Colab

**Google Colab** provides the same functionality as Jupyter notebook and extends it. Most popular data science tools are pre-installed on Colab and can be used right away. It's good for prototyping and training of simple neural networks since Google provides **free GPU instances** on Colab. See the Colab [introduction notebook][colab-link] to learn more.

---

## Exercises

A preferable way to manage dependencies on a project is to use **environment.yml** conda file. This way everyone will have the same version of dependencies and version conflicts will be avoided. However, this is not a project, so you can install all libraries manually. Pick either way and do the following:

- Create a new conda environment with Python 3.7 via conda prompt and name it "course".
- Install Numpy via pip and Pandas via conda in your new environment.
- Run Jupyter Notebook and create new notebooks.
- Import the installed libraries and check that they are working.

You might want to look at the interface or try code something inside the notebook to get used to the Notebook or Python.

---

## Overview

At this point you must have learned the next things:

- how to install Python to get started with Data Science
- Python package managers and how to install packages
- capabilities of Python stdlib and built-in functions
- Python code styling
- vectorization principles of NumPy
- main data wrangling tool
- what is a Jupyter notebook
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
[pandas-video-tutorial-link]: https://www.youtube.com/playlist?list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS

[jupyter-tutorial-link]: https://jupyter-notebook.readthedocs.io/en/stable/notebook.html
[jupyter-docs-link]: https://jupyter-notebook.readthedocs.io/en/stable/index.html
[jypyter-advanced-tips-link]: https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/
[jupyter-video-tutorial-link]:  https://www.youtube.com/watch?v=HW29067qVWk

[colab-link]: https://colab.research.google.com/notebooks/intro.ipynb
