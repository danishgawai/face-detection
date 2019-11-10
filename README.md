# face-detection
In this code we will try to detect faces with names
data set can be found in kaggle https://www.kaggle.com/dansbecker/5-celebrity-faces-dataset
here we try to achieve maximum accuracy with limited data 
it is not easy achieve high accuracy with such little data 
later we will also try transfer learning to achieve higher accuracy with same data.
facedetectionwithouttl (2).ipynb in this file we do not use transfer learning 
and try to train the model with limited data . hence unable to achieve higher accuracy.
Again we train the model with transfer learning from vgg16 model which uses imagenet as weights.
Now we train our model with already available model by changing the final hidden layer according to our model reqirements.
 This type of learning is called transfer learning and by this we are able to achieve higher accuracy with less data
