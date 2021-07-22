# MusicGenreClassification
Final Project Machine Learning Course

A link to the datasets on Kaggle: 
https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification

-> What I did? 

I created a model (XGBooster Classifier) with 90% success which classifies 3 second audio files into the their genre, from the following list of genres:
blues, classical, country, disco, hiphop, jazz, metal, pop, reggae and rock. 

I worked with the Mel-Spectrograms database and with the two CSV databases in parallel, comparing the results of each model for all three.

My work steps:
* read each of the datasets
* check them (that there is no missing data, everything is balanced, numerical values, etc.), and I arranged what is needed
* divide them into X (feature matrix) and y (label column)
* normalize the values of X
* divide the X and y into 80% training-set and 20% test-set
* run Machine Learning Techniques and report the results
* run Deep Learning Techniques (CNN model) on the Mel-Spectograms data
* analysis of results using Confusion Matrix and answer the project questions
* I developed a "Shazam Genres" system that allows you to insert a song audio as a 3-second wav file, or alternatively record one of these from the notebook, I extracted the required data from it (as it appears in the dataset). Finally I activated the selected model and said what the genre of the given song is.

The techniques I used and the success rates:
![](https://github.com/HilaShoshan/MusicGenreClassification/blob/main/results/results_table.png)

For details, it is worth taking a look at the notebook itself :)
