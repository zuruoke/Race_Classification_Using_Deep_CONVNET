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
