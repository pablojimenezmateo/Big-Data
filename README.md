Tutorials for numba and blz
============================

Do you think python is slow? Or that it cannot work with big data? 

Well, not anymore! With this tutorials I want to show how it is possible to have an astonishingly fast code while you work with big data.

Seems boring you say? 

Well, we are working with an adorable racoon, a chicken, Mandelbrot's fractal and The Garden Of The Earthly Delights, this is as fun as it gets.

If you are looking for something more serious, we also have a tutorial working with real world data, in this case a dataset of the stock movements of Microsoft in one day.

Currently available tutorials
--------------------------

Previews are available in two formats, [nbviewer](http://nbviewer.ipython.org) a static HTML option or [Wakari](https://www.wakari.io/) an online data analysis enviroment.

* Speeding code with numba [[nbviewer]](http://nbviewer.ipython.org/github/pjimenezmateo/numba-blz-tutorials/blob/master/Numba.ipynb) [[Wakari]](https://www.wakari.io/sharing/bundle/pjimenezmateo/Numba)
* Working with huge images in python, the painless way [[nbviewer]](http://nbviewer.ipython.org/github/pjimenezmateo/numba-blz-tutorials/blob/master/Numba%20and%20blz.ipynb) [[Wakari]](https://www.wakari.io/sharing/bundle/pjimenezmateo/Numba_and_blz)
* Generating huge Mandelbrot fractals with Python, the quick and memory-safe way [[nbviewer]](http://nbviewer.ipython.org/github/pjimenezmateo/numba-blz-tutorials/blob/master/Generating%20huge%20Mandelbrot's%20fractals.ipynb) [[Wakari]](https://www.wakari.io/sharing/bundle/pjimenezmateo/Generating_huge_Mandelbrots_fractals)
* Comparing speedups when using compression with blz barrays [[nbviewer]](http://nbviewer.ipython.org/github/pjimenezmateo/numba-blz-tutorials/blob/master/Barray%20benchmarks.ipynb) [[Wakari]](https://www.wakari.io/sharing/bundle/pjimenezmateo/Barray_benchmarks)
* Querying big datasets, the good way [[nbviewer]](http://nbviewer.ipython.org/github/pjimenezmateo/numba-blz-tutorials/blob/master/Bid%20Data.ipynb) [[Wakari]](https://www.wakari.io/sharing/bundle/pjimenezmateo/Bid_Data)
* Comparing speedups when using compression with blz btables [[nbviewer]](http://nbviewer.ipython.org/github/pjimenezmateo/numba-blz-tutorials/blob/master/Btable%20benchmarks.ipynb) [[Wakari]](https://www.wakari.io/sharing/bundle/pjimenezmateo/Btable_benchmarks)
* Comparing performance of btables in memory and disk [[nbviewer]](http://nbviewer.ipython.org/github/pjimenezmateo/numba-blz-tutorials/blob/master/Disk%20vs%20Memory,%20btable.ipynb) [[Wakari]](https://www.wakari.io/sharing/bundle/pjimenezmateo/Disk_vs_Memory_btable)

Requirements
----------
* [Numba](https://github.com/numba/numba)
* [blz](https://github.com/ContinuumIO/blz)
* Matplotlib
* IPython
* numpy
* scipy
* pandas

If you have [Anaconda](https://store.continuum.io/cshop/anaconda/) installed simply do:
```conda install numba blz matplotlib numpy scipy ipython pandas```

How to run
-----------
Just go to the tutorials folder and execute: ```ipython notebook```
