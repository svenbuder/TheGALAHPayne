# The Payne for GALAH
Tools for interpolating spectral models with neural networks tailored for GALAH. 

The Payne was written by Yuan-Sen Ting, see [Ting et al. 2018](http://adsabs.harvard.edu/cgi-bin/bib_query?arXiv:1804.01530)

This repository adjusts The Payne v1.0/v2.0 to be used with GALAH

## Notebooks

Observed_Spectra_Xu_191030.ipynb: Select 1161 spectra from GALAH for Xu

Select_Trainingset: Exploring Thomas synthetic grid to select model training set

train_Payne_v1.ipynb: The Payne training with YST's v2.0 training
train_Payne_v2.0.ipynb: The Payne training with YST's v2.0 training

tutorial.ipynb: YST's initial tutorial

## Installation
Through pip
```
pip install The_Payne
```

or clone this repository and run code from the base directory.
```
python setup.py install
````

The [tutorial](https://github.com/tingyuansen/The_Payne/blob/master/tutorial.ipynb) shows some simple use cases. 

## Dependencies 
* The spectral model and fitting routines require only Numpy and Scipy.
* Training a new neural network requires [PyTorch](http://pytorch.org/) (GPUs required).
* All these dependencies will be automatically installed alongside with this package
* I develop this package in Python 3.7 using Anaconda.

## Citing The Payne
* Please cite [Ting et al. 2018](http://adsabs.harvard.edu/cgi-bin/bib_query?arXiv:1804.01530), when using this code. The paper describes the method and its application to APOGEE spectra.

## Authors
* [Sven Buder](http://www.mpia.de/~buder/) -- sven dot buder at anu dot edu dot au
* [Yuan-Sen Ting](http://www.sns.ias.edu/~ting/) -- ting at ias dot edu

## Licensing

Copyright 2019 by Sven Buder and Yuan-Sen Ting.

In brief, you can use, distribute, and change this package as you please. 

This software is governed by the MIT License:

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
