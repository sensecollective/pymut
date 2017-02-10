
# PyMut

PyMut is a Python 3 module that fills the gap between machine learning and
bioinformatics, providing methods that help in the prediction of pathology in
protein mutations. Using PyMut you can compute features, train predictors,
evaluate them, predict the pathology of mutations, select the best features...

## Installation

We recommend using Anaconda, a free distribution of the SciPy stack. To install
PyMut, follow these steps:

1. <a href="https://www.continuum.io/downloads" target="_blank">
Download anaconda with Python 3.5</a>
for your platform (Windows, Linux or OSX), and install (double-click in Windows), or run in Linux of OSX:

    `bash Anaconda3-4.3.0-Linux-x86_64.sh`

2. Create an anaconda Python 3 environment (we will name it pymut), and activate the
environment:

    `conda create python=3 --name pymut`

    `source activate pymut`

3. Install PyMut:

    `pip install pymut`

## Tutorial

Visit the
<a href="http://mmb.pcb.ub.es/pmut2017/PyMut-tutorial" target="_blank">
PyMut tutorial</a>
to see a full example of usage of PyMut. In the tutorial we show how to:

* Compute features that describe mutations and plot their distribution.
* Train classifiers, evaluate them using cross-validation and plot their ROC curves.
* Select the best features.
* Train a pathology predictor.
* Predict the pathology of mutations using our newly trained predictor.


<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/01.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/08.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/09.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/03.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/04.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/05.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/06.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/02.png">

<img src="http://mmb.pcb.ub.es/pmut2017/static/img/pymut/07.png">
