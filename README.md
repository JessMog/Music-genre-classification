# Music-genre-classification
Music Genre detection    
## Introduction
Music genre classification is the process  where a piece of music is recognized, understood and differentiated by a conventional category as belonging to a shared traditions set of conventions.
 
In this project we are interested in working on genre detection as a probabilistic distribution of various genres as they pertain to the underlying styles of songs,albums and artists.We will be using a neural network model for this.We shall be tagging 10 genres and fine tune our model to achieve higher accuracy.
The dataset used for this project is GTZAN Music Genre Classification from kaggle.       
### The Team              
Jesse and Hazra will work jointly on building a neural network model for this project.                  
## Overview 
We are going to develop a deep learning project to automatically classify different musical genres from audio files. We will classify these audio files using their low-level features of frequency and time domain.
     
  
For this project we need a dataset of audio tracks having similar size and similar frequency range. 

![Screenshot 2024-04-08 231009](https://github.com/JessMog/Music-genre-classification/assets/40331541/9ae94d0f-cdd2-4368-8480-c557c23c77e0)
## Data Source(s)
We will be using the GTZAN genre classification dataset from kaggle for the music genre classification project and it was collected for this task only.
The GTZAN genre collection dataset was collected in 2000-2001. It consists of 1000 audio files each having 30 seconds duration. 

There are 10 classes ( 10 music genres) each containing 100 audio tracks. Each track is in .wav format. It contains audio files of the following 10 genres:
- Blues
- Classical
- Country
- Disco
- Hiphop
- Jazz
- Metal
- Pop
- Reggae
- Rock
## Music Genre Classification Approach
There are various methods to perform classification on this dataset. Some of these approaches are:
- Multiclass support vector machines
- K-means clustering
- K-nearest neighbors
- Convolutional neural networks

We will use the K-nearest neighbors algorithm because in various researches it has shown the best results for this problem.

## Goals of our Analysis
Musical genres are categorical labels created by humans to characterize pieces of music. A musical genre is characterized by the common characteristics shared by its members. These characteristics typically are related to the instrumentation, rhythmic structure, and harmonic content of the music.

Genre hierarchies are commonly used to structure the large collections of music available on the Web. Currently musical genre annotation is performed manually. Automatic musical genre classification can assist or replace the human user in this process and would be a valuable addition to music information retrieval systems. 

In addition, automatic musical genre classification provides a framework for developing and evaluating features for any type of content-based analysis of musical signals. Content is proposed. The performance and relative importance of the proposed features is investigated by training statistical pattern recognition classifiers using real-world audio collections. Both whole file and real-time frame-based classification schemes are described.


## Description of Data Analysis Tools 
As expected, there will be several stages in the project. Those will include exploratory data analysis, modeling (using machine learning), and possibly a scale-up from a sample of data to the full dataset. This part can also be tentative, and we will give feedback on the analysis we plan to carry out.

We shall download the dataset from kaggle and perform some statistical analysis on the dataset.

The methods will include :
- Importing  Libraries
- Understanding the audio files
- Visualizing audio files
- Feature ExtractionScaling the features
- Dividing Training and Testing Dataset
-Building the model
Model Evaluation In this proposal classification of ten musical genres is achieved. This result is comparable to results reported for human musical genre classification.


## Data Products for the proposed Project 
Data products include results of statistical tests, performance analyses of learning algorithms, visualizations of the data or model parameters.
This proposal presents a non-conventional approach for the automatic music genre classification problem.

The proposed approach uses multiple feature vectors and a pattern recognition ensemble approach, according to space and time decomposition schemes.
Despite  music genre classification being a multi-class problem, we accomplish the task using a set of binary classifiers, whose results are merged in order to produce the final music genre label (space decomposition). 

 
Music segments are also decomposed according to time segments obtained from the beginning, middle and end parts of the original music signal (time-decomposition).
 The final classification is obtained from the set of individual results, according to a combination procedure. Classical machine learning algorithms such as Naïve-Bayes, Decision Trees, k Nearest-Neighbors, Support Vector Machines and Multi-Layer Perceptron Neural Nets are employed. 
Experiments were carried out on a music dataset called GTZAN Music Genre Classification. It consists of 1000 audio files each having 30 seconds duration. There are 10 classes ( 10 music genres) each containing 100 audio tracks and  contains audio files from 10 music genres.
