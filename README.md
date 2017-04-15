
# Introduction to scikit-learn
## Master M2: Mathématiques, Apprentissage et Sciences Humaines (MASH) 2016-2017 course 

![](http://www.di.ens.fr/~aspremon/MASH/LogoMASH.png)

Instructors: *[Fabian Pedregosa](http://fa.bianp.net)* and *[Fajwel Fogel](http://www.di.ens.fr/~fogel/)*.

- email: <f@bianp.net>

This repository contains notebooks and other files associated with the MASH course introduction to
[Scikit-learn](http://scikit-learn.org).

## Notebook Listing
You can view the teaching materials using the excellent nbviewer service.

  * [00: Introduction to Python](https://nbviewer.jupyter.org/github/fabianp/mash_2016_sklearn_intro/blob/master/00-Intoduction%20to%20the%20Python%20language.ipynb)
  * 01: Introduction to Pandas and scikit-learn
  * [02: Supervised learning I](http://nbviewer.jupyter.org/github/fabianp/mash_2016_sklearn_intro/blob/master/02-Supervised%20learning%20I.ipynb)
  * etc. (see github page)

Note, however, that you cannot modify or run the contents within nbviewer.
To modify them, first download the tutorial repository, change to the notebooks directory, and run ``ipython notebook``.
You should see the list in the ipython notebook launch page in your web browser.
For more information on the IPython notebook, see http://ipython.org/notebook.html

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible.


## Installation Notes
This tutorial requires the following packages:

- Python version 2.6-2.7 or 3.3+
- `numpy` version 1.5 or later: http://www.numpy.org/
- `scipy` version 0.10 or later: http://www.scipy.org/
- `matplotlib` version 1.3 or later: http://matplotlib.org/
- `scikit-learn` version 0.14 or later: http://scikit-learn.org
- `ipython` version 2.0 or later, with notebook support: http://ipython.org
- `plotly`
- Keras (for the last class)

The easiest way to get these is to use the [conda](https://store.continuum.io/) environment manager.
I suggest downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).

Once this is installed, the following command will install all required packages in your Python environment:
```
$ conda install numpy scipy matplotlib scikit-learn jupyter seaborn plotly
```

Alternatively, you can download and install the (very large) Anaconda software distribution, found at https://store.continuum.io/.

## Downloading the Tutorial Materials
I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

    git clone https://github.com/fabianp/mash_sklearn_intro.git

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  I may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.



## Other resources

Material from [last year's course](http://www.di.ens.fr/~slacoste/teaching/projet-MASH-2015/)

See also the excellent [scikit-learn tutorial](https://github.com/jakevdp/sklearn_tutorial) by Jake Vanderplas.
