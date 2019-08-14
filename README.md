# ASAP
Automatic Selection And Prediction tools for crystal structures

python 3

Requirements:

+ numpy scipy scikit-learn tqdm ase dscribe

Add-Ons:
+ spglib

In the directory ./asap/ you can find a selection of python tools:
* gen_soap_kmat.py: computes kernel matrix between different structures if multiple frames are provides, or the kernel matrix between atomic environments in a structure if only one frame is the input.

* kpca.py: does principle component analysis on the kernel matrix and makes plots.

* kernel_density_estimate: does principle component analysis on the kernel matrix, estimates kernel density, and makes plots

* clustering.py: does clustering tasks based on the kernel matrix, does plottingas well.

TODOs:
* add a class of methods to compute kernel matrix from basis functions
* add a dendrogram function