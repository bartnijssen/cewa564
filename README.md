This directory a series of Jupyter notebooks that you can use to get familiar with running SUMMA from within Jupyter notebooks using pysumma.

Note that if you want to preserve the changes that you make in these notebooks, then you should save them somewhere other than in the `cewa564` directory tree. If not, the files may be overwritten when you download them again or when you pull down the latest changes from the github repository from where you obtained these files originally.

If you are new to python and want to practice, then extensive help exists online. For example, take a look at the software carpentry python tutorial that is discussed
on the [software carpentry web site](http://swcarpentry.github.io/python-novice-inflammation). Another place to start is [this tutorial](http://python.berkeley.edu/learn/) from Python Practice at Berkeley, but there are many others. Similarly, if you are unfamiliar with the amazing power of Jupyter notebooks, you can start here: https://jupyter.org/

The notebooks in the `cewa564` directory assume that you already have a SUMMA executable installed. They are optimized for running SUMMA in the cloud-based computing environment provided by the [Pangeo](http://pangeo.io) project at `https://hydro.pangeo.io`. You can also use them to run SUMMA locally (i.e. on your own machine) or elsewhere, but you will undoubtedly need to make some modifications (which I will leave as an exercise for the reader).

This repository has a number of subdirectories:

* / -- the top level directory contains this README as well as a notebook that shows you how to install the SUMMA configurations that are available to you (install_summa_model_configurations.ipynb).
* /demo -- contains a number of notebooks that show you some examples for running SUMMA using pysumma from within Jupyter notebooks. You can run through them in order.
* /explore -- contains a number of notebooks that take you through the SUMMA configurations that are available to you through the install_summa_model_configurations.ipynb notebook.
* /howto -- contains a number of notebooks that show a summary of how to use most of pysumma's functionality. They are not as sequential as the demos, but probably useful as a reference
