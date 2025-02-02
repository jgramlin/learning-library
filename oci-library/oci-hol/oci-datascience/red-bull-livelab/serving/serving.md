# Model Serving

## Introduction

This lab will walk you through the steps to deploy and serve the best trained model as:
  
  * API REST using the feature importance (variables) for the best model.

![Image alt text](./images/picture1.png)

It seems the Neural Network Classification is the best model to return the highest scores, correctly predicting the winner for 62% of the races.

Estimated Time: 1 hr

<b> Objectives </b>

In this lab, you will:
* Execute ``` 05.ML_Model_Serving.ipynb ``` to deploy the best ML model, which is served and consumed using REST API

<b> Prerequisites </b>

* An Oracle Free Tier, Always Free, Paid or LiveLabs Cloud Account


## **STEP 1**: Execute ``` 05.ML_Model_Serving.ipynb ``` to deploy the best ML model, served and consumed using REST API

Navigate to the ``` /redbull-analytics-hol/beginners/``` directory in your Jupyter Notebook session and execute ``` 05.ML_Model_Serving.ipynb ```. 

1. Our ML model must use Drivers confidence / points and Team/Constructor reliability / Points

   ![Image alt text](images/picture1.png)


2. Using 2021 Dataset to Calculate the Confidence/ reliability and Points per Constructor/ Driver after each race
  
  ![Image alt text](images/picture2.png)

  ![Image alt text](images/picture3.png)


3. We can detect the Feature Importance for our Best ML Model.The Qualifying Position is the main feature for our trained model. 

  ![Image alt text](images/picture4.png)

4. RF Explanation for First Decision Tree 

  ![Image alt text](images/picture5.png)

5. RF Explanation for 5 first Decision Trees

  ![Image alt text](images/picture6.png)



## Acknowledgements
* **Author** - Ignacio Martinez, Principal Advanced Support Engineer
* **Last Updated By/Date** - Samrat Khosla, Advanced Data Services, September 2021

## Need Help?
Please submit feedback or ask for help using our [LiveLabs Support Forum](https://community.oracle.com/tech/developers/categories/livelabsdiscussions). Please click the **Log In** button and login using your Oracle Account. Click the **Ask A Question** button to the left to start a *New Discussion* or *Ask a Question*.  Please include your workshop name and lab name.  You can also include screenshots and attach files.  Engage directly with the author of the workshop.

If you do not have an Oracle Account, click [here](https://profile.oracle.com/myprofile/account/create-account.jspx) to create one.
