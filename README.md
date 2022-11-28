# OrangeHRM_DataTest_Cucumber

# Description

In this project, Cucumber is being used to apply a wide range of data from a dataset consisting of all negative credentials that as being allied to the login page of the following website: https://opensource-demo.orangehrmlive.com/

When invalid data is applied the login page shows an error "Invalid credentials". This error message is then asserted against each data in the dataset and every time the login attempt fails, the test case assertion passes.

# Things to be noted

A data set must contain either all the valid data or all the negative data. If the data set carrying negative data to be tested was to have valid data (i.e. credentials) in the middle of the dataset then it would have successfully logged in to the site and as a consequence for that, all the following data would have remained un-tested.

# Example of dataset

While valid credentials are the following:

Username: admin
Password: admin123

Invalid set of data that are being testded are:

![image](https://user-images.githubusercontent.com/40532866/204178801-3218689a-c6d6-456d-9d6e-5b898c9bdcf5.png)
