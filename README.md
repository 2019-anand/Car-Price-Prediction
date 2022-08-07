# Description
This project aims to predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.
For example, the image below shows the predicted price of our Hyundai Grand i10.
![image](https://user-images.githubusercontent.com/98209132/183284321-99f7a581-7058-4532-991f-a2e6d748c0a8.png)
# Steps Involved----->
1.First of all the data was scraped from Quikr.com (https://quikr.com)

2.The data was cleaned (it was super unclean :( ) and analysed.

3.The linear Regresssion model was built on top of it.

4.the pipeline was created and then trained with X_train and Y_train and then predicted the y for X_test.

4.The Regression model was evaluated on the basis of the r2 scores and for getting the best r2 score random state was chosen by running a loop.

5.Finally the price was predicted for the old car for a new user information of features present in x_columns.  
