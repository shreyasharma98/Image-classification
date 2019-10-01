# Image-classification 
Using Keras
 
# TASK :
This is an internship project where I was given an organised training set that has 4 defined directories for 4 categories . 
There's also a test directory which contain some random images , the aim is to classify the images in the test dir. based on training set . The results should be stored in the csv file which contain 2 column : 1 - Image file path 2- The predicted category .  

# Data set : 

https://drive.google.com/open?id=1Iei0n3Dk5xJCzF3aFOR8in6G3cNLEy8z

# The imports

This is a basic implementation of image classification using CNN. As we know , Keras is the most popular open-source tool for implementing Neural networks genrally used for image classification.

      from keras.layers import Conv2D         #for convoluion operation.
      from keras.layers import MaxPooling2D   #for pooling.
      from keras.layers import Flatten        #flatening.
      from keras.layers import Dense          #for ANN full connection.
      from keras.models import Sequential     #for Ann full connection.


## Steps for CNN - Convolution Neural Network

      Step 1: Convolution Operation.
      Step 1(b): ReLU Layer.
      Step 2: Pooling.
      Step 3: Flattening.
      Step 4: Full Connection.
