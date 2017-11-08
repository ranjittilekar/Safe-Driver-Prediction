# Safe-Driver-Prediction

## Project Overview

A key challenge that every insurance company faces today is to charge an appropriate premium amount to a driver based on his driving history. Considering the competition, there has to be a near to perfect balance between pricing your insurance rates low enough to lure you from a competitor, but high enough to make a profit on your future accidents. This involves an elaborate risk assessment which varies widely from customer to customer, and a deep understanding of different risk factors helps predict the likelihood and cost of insurance claims.
Every insurance company has a lot of historical data for all of its customers which can be utilized to build a powerful predictive model to better serve their customers.  


## Project Highlights

Nothing ruins the thrill of buying a brand new car more quickly than seeing your new insurance bill. The sting’s even more painful when you know you’re a good driver. It doesn’t seem fair that you have to pay so much if you’ve been cautious on the road for years.
Porto Seguro, one of Brazil’s largest auto and homeowner insurance companies, completely agrees. Inaccuracies in car insurance company’s claim predictions raise the cost of insurance for good drivers and reduce the price for bad ones.
In this analysis, we will be building a model that predicts the probability that a driver will initiate an auto insurance claim in the next year. A more accurate prediction will allow them to further tailor their prices, and hopefully make auto insurance coverage more accessible to more drivers.



## Install

This project requires Python 3.6 and the following Python libraries installed:

    - NumPy
    - Pandas
    - matplotlib
    - scikit-learn
    - XGboost 

You will also need to have software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included. Make sure that you select Python 3.x installer.

## Run

In a terminal or command window, navigate to the top-level project directory customer_segments/ (that contains this README) and run one of the following commands:

ipython notebook Safe_Driver_Prediction_Udacity.ipynb
or

jupyter notebook Safe_Driver_Prediction_Udacity.ipynb
This will open the Jupyter Notebook software and project file in your browser.

## Data

In this problem, we will predict the probability that an auto insurance policy holder files a claim.
In the train and test data, features that belong to similar groupings are tagged as such in the feature names (e.g., ind, reg, car, calc). In addition, feature names include the postfix bin to indicate binary features and cat to indicate categorical features. Features without these designations are either continuous or ordinal. Values of -1 indicate that the feature was missing from the observation. The target column signifies whether or not a claim was filed for that policy holder. As we don’t have target column provided in test dataset. To verify my model, I will be dividing the train.csv file in training and testing dataset. 
Dataset Details – 
    • The dataset contains 595212 rows and 59 columns
    • features/columns consist of only two datatypes - Integer and floats
    • Target variable inspection – There are two classes for the target variable – 
                0 - Claim was not filed – 573,518 rows
                1 - Claim was filed – 21,694 rows
    • As we can see very few people have filed the claim as per the given data.
    
File descriptions
    • train.csv contains the training data, where each row corresponds to a policy holder, and the target columns signifies that a claim was filed.


