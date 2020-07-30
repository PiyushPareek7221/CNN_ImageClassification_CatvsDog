# CNN_ImageClassification_CatvsDog

CNNs have broken the mold and ascended the throne to become the state-of-the-art computer vision technique. Among the different types of neural networks (others include recurrent neural networks (RNN), long short term memory (LSTM), artificial neural networks (ANN), etc.), CNNs are easily the most popular.

Recently created an image classification model with an accuracy of 91.8% using convolutional neural networks which is a part of deep learning.
The model predicts whether an image is of cat or dog by training on approx 20000 images of cats and dogs.
The dataset i have taken from kaggle.com .
The whole processes i have shown is in the article .
Take a look at it hope you would like it.

These are the following coding processes involved in this :-

1.) Importing the major libraries and layers which will be used to later in creating cnn and initializing the model.

2.) Adding layers and making the full connection.

3.) Compiling the model and setting 'adam' optimizer and binary_cross_entropy as loss function.

4.) Analyzing the model by seeing the different layers and parameters.

5.) Transforming and validating the train and test data by taking the data for test and train from directory.

6.) Training the model on given training dataset and setting the epoch to 28 to be more precise.

7.) At the end of this step we get the Accuracy of approx 91.8%.

Accuracy = 91.8%

8.) Now comes the part of prediction in which i have provided an image of dog and an image of cat one by one and then checking if the model is predicting well on the given test data.

So now our model predicts well on the given input.

Now the model prediction for cat and dog is over.
