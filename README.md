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
- Download the cats and dogs classification [weights](https://github.com/raducrs/Applications-of-Deep-Learning/releases/download/0.1/cats_dogs_large_weights.h5) and place them in Models/cats_and_dogs_large/final 
- Download the cats and dogs classification small [weights](https://github.com/raducrs/Applications-of-Deep-Learning/releases/download/0.1/cats_dogs_small_weights.h5) and place them in Models/cats_and_dogs_small/final 
- Download the cats and dogs classification small augmented [weights](https://github.com/raducrs/Applications-of-Deep-Learning/releases/download/0.1/cats_dogs_small_augmented_weights.h5) and place them in Models/cats_and_dogs_small_augmented/final
- Download the abstract classification [weights](https://github.com/raducrs/Applications-of-Deep-Learning/releases/download/0.1/abstract_classification_weights.h5) and place them in Models/abstract_classification/final
### Image captioning
- Download the image captioning [weights](https://github.com/raducrs/Applications-of-Deep-Learning/releases/download/0.1/image_caption_flick8k_06.05.h5) and place them in Models/abstract_classification/final
### Pickle files
- You can also download the pickle files from the [release distribution](https://github.com/raducrs/Applications-of-Deep-Learning/releases/tag/0.1) and place them in the appropiate folder as needed or regenerate them by running the code

## Test files
### Image classification
- place some  images in the folder Test/imagenet to observ the VGG16 predictions and explore the activations with quiver
- place some  cats and dogs images in the folder Test/cats_and_dogs_large for the prediction of the retrained model on the full dataset 
- place some  cats and dogs images in the folder Test/cats_and_dogs_small for the prediction of the retrained model on the reduced dataset with and without augmentation
- place some  random images in the folder Test/abstract_classification for the prediction of the model trained to distinguish between scenery and photos of persons
### Image captioning
- place some  random images in the folder Test/image_caption for generating captions

## Misc
- The Presentation folder contains some images which may be subject to copyright and we will not distribute them. Some sections of the notebook will not rerun (usually the markdown sections of the code)

# Enjoy and have fun (deep) learning
