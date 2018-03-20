# Human Brains 

## Machine Learning

* A regression analysis to predict head size vs. brain weight.

## Instructions

* Started by creating a scatter plot of the data to visually see if any linear trend exists.

* Splited the data into training and testing using sklearn's `train_test_split` function.

* Next, used sklearn's linear regression model and fit the model to the training data.

* Used the test data to make new predictions. Calculate the MSE and R2 score for those predictions.

* Used `model.score` to calcualte the R2 score for the test data.

## Method Used 
* Least Squares 
* R-squared and Mean Squared Error for validity

## Data Set 
* brains.csv

Source: R.J. Gladstone (1905). "A Study of the Relations of the Brain to
to the Size of the Head", Biometrika, Vol. 4, pp105-123

Description: Brain weight (grams) and head size (cubic cm) for 237
adults classified by gender and age group.

Variables/Columns
GENDER: Gender  /*1=Male, 2=Female*/
AGE: Age Range  /*1=20-46, 2=46+*/
SIZE: Head size (cm^3)  21-24
WEIGHT: Brain weight (grams)  29-32

## Tools Used 
* Python
* Pandas
* Numpy
* Sklearn
* Matplotlib

## Conclusion

MSE, Mean Squared Error, score would make more sense if the data is normalized. MSE closed to '0' would be a good. 
R-squared value is here greather than 0.66 so the model is not weak but not that strong either. 
Other factors to consider: Age and Gender. 
