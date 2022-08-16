# Smile-Classification
# About all steps in project
•	Loading data, EDA, Imagedatagenerator, Data Augmentation

1.	First of all I have used Kaggle notebook for the project and I have downloaded data  from the drive and uploaded it to Kaggle notebook as private 
2.	Now I have imported necessary libraries 
3.	Now I have created a training data frame and done EDA on it
4.	Now I have created a function that is going to add ‘.jpg’ at the end of every ‘image_name’ in training and testing data frame
5.	Now I have shown some images to check for pixels of images (and found out 250x250 as best pixels)
6.	Now I  have created ImageDataGenerator for training, validation, and testing and also applied data augmentation 
7.	Now I have shown some images with their label

•	Creating model without using pre-trained base

8.	Now I have created a model without using a pre-trained base or transfer learning  
9.	Now I have used a model checking point from Keras for saving the best weights so that we don’t have to fit our model every time for the number of epochs
10.	Now I have fitted the model with training and validation data for 40 epochs and also used callback for apply model checkpoint during training
11.	Now I have plotted graphs of accuracy and loss for the number of epochs
12.	Now I have evaluated my model for training and testing data using the trained model
13.	Now I have evaluated the model for training and testing data with a saved model that is saved by model checking point with best weights and also checked the shape of prediction for testing data

•	Creating model with pretrained base

14.	Now I have created a function that takes pretrained base as its parameter and creates the model
15.	Now I have used different pretrained bases 

• Steps for applying transfer learning to model (same steps for all pretrained bases)

16.	First of all I have created a pre-trained base object from Keras. applications and used hyperparameters compatible with our data 
17.	Now I have given this object to created function as parameters and it will return compiled model
18.	Now I have shown the summary of the model that is gonna show how many parameters are there and how many trainable parameters
19.	Now I have created a model checkpoint object to give during the fitting of data 
20.	Now after fitting the data I have shown Accuracy, Loss vs number of epochs graphs
21.	Now I have evaluated the model for both training and testing data
22.	Now I have also evaluated for both training and testing data using saved model and also checked the shape of test prediction data
