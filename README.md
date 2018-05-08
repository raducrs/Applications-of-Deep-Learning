# Applications of Deep Learning

## Setup
- Clone repo and make sure to keep the folder structure intact
- Follow guide to obtaining datasets
- Delete the README.md files in all the folders 
- Download to trained models weights
- Populate the Test folder with your own images according to category
- Install all the dependencies in the requirements 

## Requirements
- Tensorflow >= 1.7 (it is recommended to use the version with GPU support)
- Keras >= 2.1
- Numpy >= 1.10
- Scikit Image >= 0.13.1
- Scikit Learn >= 0.19.1
- Pillow >= 5.0
- Pickle >= 0.7.1

The conda environment file or requirements provide the full list of packages

## Datasets
### Image Classification

- Obtain a a copy of the [Kaggle Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats) dataset and split the training images keeping equal ratio of labels into the folders Dataset/cats_dogs_large/Train/dog, Dataset/cats_dogs_large/Train/cat and similar folders for validation and testing. We have set asside 2000 images fro training
- The folder Dataset/abstract_classification was populated with two categories of approximately 1200 images hand picked from the Flickr 8k dataset. We can not redistribute this, but you can select several examples that depict close-up shoots of people or scenery and place them in the respective folders of training, validation and test

### Image Captioning
- Obtain a copy of the Flickr 8k dataset from [Department of Computer Science, University of Illinois at Urbana–Champaign](https://forms.illinois.edu/sec/1713398) and place it in the folder Datasets/flickr8k
- Download the word embeddings from [GloVe](https://nlp.stanford.edu/projects/glove/) and place them in Datasets/glove

## Trained models 

### Image classification
### Image captioning
