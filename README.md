# Integrative analysis of single-cell multi-omics data using deep learning

The accompanying notebooks for my blog post "Integrative analysis of single-cell multi-omics data using deep learning": https://medium.com/@yuan_tian/integrative-analysis-of-single-cell-multi-omics-data-using-deep-learning-66a61a3448c5 

The data can be downloaded at:  https://www.dropbox.com/sh/opxrude3s994lk8/AAAiWrZzFViksxKpYomlwqhEa?dl=0

To run the clustering notebook, you will need to have R and the Seurat package installed by typing:  install.packages('Seurat')
library(Seurat)

To run the autoencoder notebook, you will need to have Python 3.6 or later and install Pytorch v1 and the fastai library by typing:
conda install -c pytorch -c fastai fastai

To use Pip install, please first install Pytorch following the instructions on:
https://pytorch.org/

and then install fastai by typing:
pip install fastai
