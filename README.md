# Image-classification 
Using Keras
 
# TASK :
This is an internship project where I was given an organised training set that has 4 defined directories for 4 categories . 
There's also a test directory which contain some random images , the aim is to classify the images in the test dir. based on training set . The results should be stored in the csv file which contain 2 column : 1 - Image file path 2- The predicted category .  

# Data set : 

https://drive.google.com/open?id=1Iei0n3Dk5xJCzF3aFOR8in6G3cNLEy8z

## view to data

### Category 1 :  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Category 2 : 
<img src = "/pic/category 1_original_1013.png_bb7b257a-cd09-4d23-86b6-9de65832f938.png"  width="200" height="200"  /><img src="/pic/category 1_original_1013.png_bc4d56ae-3287-44e5-8e07-f227b0e11e4d.png"   width="200" height="200"/> 

<img src = "/pic/category 2_original_6000.png_8b9bab98-f39d-4ef7-b662-b634f15873f4.png"  width="200" height="200"  /><img src="/pic/category 2_original_6010.png_aeacf8a0-2f49-407f-83df-6d122e48adb8.png"   width="200" height="200"/> 

### Category 3 :  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  Category 4 :

<img src = "/pic/category 3_original_4000.png_b86d6a8c-14da-4af8-861f-9cae6a870f03 (1).png"  width="200" height="200"  /><img src="/pic/category 3_original_4000.png_e644cef7-524c-4694-957d-7e88320c11f6.png"   width="200" height="200"/> 
<img src = "/pic/category 4_original_C000.png_ffdbf440-bd70-469f-a7eb-3aed46400edb.png"  width="200" height="200"  /><img src="/pic/category 4_original_C010.png_2c356427-d1b3-4ef8-b7fb-fdc707b88100.png"   width="200" height="200"/> 

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
