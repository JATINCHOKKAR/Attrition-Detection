# Attrition-Detection
                                                             
Attriton refers to the process of downsizing the workforce of a company 
we can say that attrition is a gradual voluntary reduction of employees (through resignation and retirement )who are not then replaced. This means that attrition decrease the size of the workforce

The objective of this project is to predict the attriton rate for each employee to find out who's more likely to leave the organizaion.

It will help organizations to find ways to prevent attrition for to plan in advance the hiring new candidate

Attrition proves to be costly and time consuming problem 

Project Workflow

Read the Csv file

Did some Data Preprocessing 

 Converted all the Categorical variable into Numerical variable

 Handled the missing values.

Did Some Exploratory Data Analysis using Box Plot to check the Outliers type things.

Did Some Feature Engineering like Checked the Correlation after that did some feature tranformation (Binning)
	
Then to check the Multicollinearity used the Variance Inflation Factor Technique

Understand how features  are related with our target (If our target is not dependent on any feature then we can remove them)

Then handled with some imbalanced data 

 
Split the data for training and testing purpose usign train_test_split

Then Train the Naive Bayes Classifier Model on the training data

After that Predict the testing data and got an accuracy of 91%




