# Music-Genre-Classification

Music Genre Classification using GTZAN Dataset.Here is the Link to Dataset [GTZAN Dataset](https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification)

## installation
download the the zip file or clone the repo.

install module specified in requirements.txt

run music-genre-recognition-app.py


## ERRORS ca be raised in issues section

The Dataset contains 10 Genres of music :
## Genres
* Blues
* Classical
* Country
* Disco
* Hip-Hop
* Jazz
* Metal
* Pop
* Reggae
* Rock
## Dataset
* Each Genre contains 100 audio files each of duration 30s.
* Divided 30s audio files into 10 files of 3s each.
* This Data Augmentation really helps model learn better and it performes better on the test set.

## Models
I have explored the problem using two approaches 
1) Using Deep Neural Network (DNN) Model which made use of features such as MFCC's,spectral centroids, extracted features are in features_3sec.csv
2) Using Convolutional Neural Network (CNN) Model which made use of Mel Spectrogram of the Audio Files.

## Results
![Training Loss Plot](https://github.com/KunalVaidya99/Music-Genre-Classification/blob/master/musicgenre.PNG)

So this the training and test accuracy obtained after 250 epochs.
A simple DNN model is also showing quite good test accuracy due to data augmentation
