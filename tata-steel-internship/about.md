This is the **"About"** section of the project. I will explain the project in as much detail as possible. 

* Let's start with the dataset. The dataset is a flat file (a .csv file, to be precise). It is a small dataset comprising **1338** rows and **7** columns. We have 6 independent variables - **age**, **sex**, **BMI**, **children**, **smoker**, and **region**, and one dependent variable, ***charges***. The dataset has discrete, continuous and categorical features.

* The features sex, smoker, and region are not numerical. We need to encode the features to be benificial for our analysis. 

* As a part of **data preprocessing**, we will check for *null* values. If the missing values constitute an insignificant number of samples, we would remove the missing values from the dataset.

* We will **NOT** be using **One Hot Encoding** for this purpose. Rather, we will be using simple mapping for all the categorical values.

* We would be employing different regression techniques and measuring their efficacies.
