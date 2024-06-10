# Music_genre-CNN-model
Introduction:

we will discuss the classification of music files based on the genres. Generally, people carry their favorite songs on smartphones. Songs can be of various genres. With the help of deep learning techniques, we can provide a classified list of songs to the smartphone user. We will apply deep learning algorithms to create models, which can classify audio files into various genres. After training the model, we will also analyze the performance of our trained model.

Dataset:

We will use GITZAN dataset, which contains 1000 music files. Dataset has ten types of genres with uniform distribution. Dataset has the following genres: blues, classical, country, disco, hiphop, jazz, reggae, rock, metal, and pop. Each music file is 30 seconds long.

Figure 01 represents the overview of our methodology for the genre classification task. We will discuss each phase in detail. We train three types of deep learning models to explore and gain insights from the data.

![image](https://github.com/nehaR21/Music_genre-CNN-model/assets/107937417/b82f6fb5-6aaa-4c1a-bbae-761edc644ce7)


After preprocessing the data, we create our first deep learning model. We construct a Convolution Neural Network model with required input and out units. The final architecture of our CNN model is shown in the given code. We use only spectrogram data for the training and testing.


