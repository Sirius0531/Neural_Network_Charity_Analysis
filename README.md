# Neural_Network_Charity_Analysis

This project is using Machine Learning and Neural Network. Identify the features from the dataset to create a classifier. The model will help to predict if the applicants successfully get the fund from a Charitable organization.

**1. Clean and process the data to get ready for meural network
**2. Compile and train the model
**3. Optimize the model base on the accuracy

1st attempt, drop the "STATUS" feature:
![This is an image](https://github.com/Sirius0531/Neural_Network_Charity_Analysis/blob/main/Resources/1st%20attempt.PNG)

No siginificant increase accuracy:
![This is an image](https://github.com/Sirius0531/Neural_Network_Charity_Analysis/blob/main/Resources/1st%20attempt%20result.PNG)

2n attempt, drop the "ASK_ATM" feature:
![This is an image](https://github.com/Sirius0531/Neural_Network_Charity_Analysis/blob/main/Resources/2nd%20attempt.PNG)
No siginificant increase accuracy:
![This is an image](https://github.com/Sirius0531/Neural_Network_Charity_Analysis/blob/main/Resources/2nd%20attempt%20result.PNG)

3rd, change the optimizer to 'rmsprop'
![This is an image](https://github.com/Sirius0531/Neural_Network_Charity_Analysis/blob/main/Resources/3rd.PNG)

Increase accuracy to 0.73!
![This is an image](https://github.com/Sirius0531/Neural_Network_Charity_Analysis/blob/main/Resources/3rd%20result.PNG)
