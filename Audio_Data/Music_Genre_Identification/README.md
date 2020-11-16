# Music Genre Identification

 Identifying the genre of audio files for songs using Spectrogram based end-to-end Image classification using a CNN(InceptionV3).
    
    
## Requirements
* Python
* TensorFlow
* Keras
* Librosa - For audio feature extraction
* Numpy, Pandas, Matplotlib

## Dataset
We use GTZAN genre collection dataset for classification.

The dataset consists of 10 genres i.e
* Blues
* Classical
* Country
* Disco
* Hiphop
* Jazz
* Metal
* Pop
* Reggae
* Rock

Each genre contains 100 songs. Total dataset: 1000 songs

## Overview
For Music Genre Identification using pretrained InceptionV3 Model:
* Converting all the Audio Files(.au) into Spectograms using Librosa python package and saving those spectograms in respective genres folders.
* Shuffling the images of the spectograms and splitting the data into Train,Validation and Test Sets.
* Since the size of the entire dataset is quite low(1000 images) before passing the data to model for training we would be artificially expand the size of a training dataset by   creating modified versions of images in the dataset using Image Data Augmentation Technique.
* Using pretrained CNN(InceptionV3) Model we are training the model and checking its performance on Validation and Test Dataset respectively.

Note:
Spectograms - A spectrogram is a visual representation of the spectrum of frequencies of sound or other signal as they vary with time. Spectograms allow looking at the whole song once and get the information about the tones present right away!



## Usage
```
Music_Genre_Identification.ipynb
```


  
  

## Tested On
* [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)

## Acknowledgments
1. [Music Genre Classification with Python](https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8)
2. [Using CNNs and RNNs for Music Genre Recognition](https://towardsdatascience.com/using-cnns-and-rnns-for-music-genre-recognition-2435fb2ed6af)
3. [Convolutional Neural Networks in TensorFlow](https://www.coursera.org/learn/convolutional-neural-networks-tensorflow)


