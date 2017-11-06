# lesson 1

#### kaggle

www.kaggle.com
data science competitions, data sets, etc.

#### imagenet

image-net.org
images with categories and metadata
image recognition competitions
datasets for testing

#### data science basics

- data dir structure is important
- enforce test/training data split

- training set
files are labeled and identify the subject
further split into valid and invalid sets

- test set
files are unlabeled
best to not be involved in test set creation

- work on a sample
runs quickly
try changes on a small data set to test changes

- minibatch
grabs a few images at a time, computes on all at once
a single image at a time is not enough to keep the gpu busy


#### jupyter notebook

lines with a * means that the line is being run

#### library information

vgg16 sits on top of 
keras - main DL library, written in python, can create tensorflow code, sits on top of 
theano - takes python code and turns it into compiled gpu code sits on top of
cuda - nvidia programming environment, has cuda deep neural network library (cudnn)
