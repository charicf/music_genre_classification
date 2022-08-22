# music_genre_classification

This is a group project that aims to classify audio files into a music genre. We used the GTZAN dataset consists of 1000 audio tracks, each 30 seconds long. It includes ten genres: blues, classical, country, disco, hiphop, jazz, metal, pop, reggae, and rock.

In order to analyze the music files, we used the python librosa library to extract the features from each file. We completed it in two processes, one extracting only MFCC for the neural network and the other extracting 26 different features for kNN, Random Forests and SVM. Once we had all the features we needed, we applied them to the models for training and testing. Results were mixed depending on music genre.

Authors: Dmytro Kuzmyk, Jieun Yoo and Charic Farinango.
