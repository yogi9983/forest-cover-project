# forest-cover-project
to build classification methodlogy to predict the type of forest cover based on  the data


this is the given data from client side 
![forest1](https://user-images.githubusercontent.com/90147513/153174963-5aafad35-230d-4883-a955-1c96ccbfe855.PNG)

checking whether giving column are normally distributed  or not
![forest2](https://user-images.githubusercontent.com/90147513/153176240-7234d8c8-f948-482a-9749-d7d6d9210318.PNG)


applied standard normal distribution
![image](https://user-images.githubusercontent.com/90147513/153177022-bcfdb638-4f90-47ad-9a12-30959c4cc1b8.png)


Here using a plot i finded there is an imbalanced data in target column

![forest4](https://user-images.githubusercontent.com/90147513/153177456-f429f5c2-3772-4ab2-9e39-4c0721966cec.PNG)

here i did smote for  handling  imbalanced data

![forest5](https://user-images.githubusercontent.com/90147513/153177940-77983949-5bb1-4b58-9a5c-2c508423e0b5.PNG)



AFTER DATA PREPROCESSING I HAVE DONE DATA CLUSTERING IN THAT CLASS DIVIDED INTO FOUR CLUSTER AND IN MODEL SELECTION I USED KMEANS CLUSTERING AND XGBOOST TO CLASSIFY 
4 MODEL WAS CREATED AND PREDICTION WAS DONE BASED THE NEW TEST DATA WHICH CLUSTER IT BELONG THAT PARTICULAR MODEL WILL PREDICT
