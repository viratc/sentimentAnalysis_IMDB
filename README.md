# sentimentAnalysis_IMDB
This is a simple Machine Learning & Deep Learning application built using Python that performs Sentiment Analysis on IMDB Data

## Getting Started 

### Prerequisites

This application was built using: 

    Python 3.6, jupyter notebook 4.3.1, Tensorflow 1.8

### Dataset 

Data set for this Application can be downloaded from as Gzip-compressed tarball archive [here](http://ai.stanford.edu/~amaas/data/sentiment/):

    * For MacOS or Linux: Open Terminal, cd to the download directory and execute tar -zxf aclImdb_v1.tar.gz to
                          decompress the data set
                        
    * For Windows: Extract the files from download folder, using a archiver(Like 7Zip)
    
### File Description

    * sentimentAnalysis.ipynb: This file contains all the necessary code for Data Pre-processing steps(used later) and 
                               performing Sentiment Analysis using Stochastic Gradient Descent Classifier
                               
    * sentimentAnalysis_RNN.ipynb: This file contains the code that builds on top of Data Pre-Processing
                                   and performs Sentiment Analysis using Recurrent Neural Networks
                           
