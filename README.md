# Race_Classification_Using_Deep_CONVNET
Using a Deep CONVNET to Build a Model for Classifying Different Races such as Mongoloid, Negroid and Caucasian

This kernel uses a deep CONVNET that was trained on Google GPU to perform Race Classification on a zipped file containing faces of different races.

Each of the image are either labelled as:

- Caucasian: includes people of American and European descent, also known as whites

- Mongoloid: includes people of Asian descent, especially Eastern Asian
 
- Negroid: includes people of African descent or black Americans

The zip Dataset contains various images of faces of different races which was aggregated from https://www.shutterstock.com/ 

I'll use it to build an face image classifier using a **tf.keras.Sequential.model** and build a data(input data pipline) using **tf.keras.preprocessing.image.ImageDataGenerator.**

This project workflow includes:

- Loading the zipped dataset from my google drive

- Examining and understanding the dataset

- Building a Data Image input pipeline

- Building a Deep CONVNET Architecture

- Training a CNN model

- Testing the model

- Using the model for prediction on new data


All these will be done with tensorflow 2.x.

# RESULTS

![3444](https://user-images.githubusercontent.com/51057490/82643128-edb4b000-9c06-11ea-8688-4f18cfe51fb3.JPG)

![4555](https://user-images.githubusercontent.com/51057490/82643139-f311fa80-9c06-11ea-95b9-8ff069342b3e.JPG)

![44666](https://user-images.githubusercontent.com/51057490/82643148-f6a58180-9c06-11ea-98b1-96b0164d09f6.JPG)

