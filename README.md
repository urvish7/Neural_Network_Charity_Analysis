# Neural_Network_Charity_Analysis

## Overview

Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With our knowledge of machine learning and neural networks, we’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

 - EIN and NAME—Identification columns
 - APPLICATION_TYPE—Alphabet Soup application type
 - AFFILIATION—Affiliated sector of industry
 - CLASSIFICATION—Government organization classification
 - USE_CASE Use case for funding
 - Organization type
 - STATUS—Active status
 - INCOME_AMT—Income classification
 - SPECIAL_CONSIDERATIONS—Special consideration for application
 - ASK_AMT—Funding amount requested
 - IS_SUCCESSFUL—Was the money used effectively
 
 If we boil down the purpose, its about to assist Alphabet Soup predit where  its about making an investments, then analysing data from more than 34,000 organizations and have funding receieved from Alphabet Soup over the years.
 
 ### The files which are going to be use in this Analysis are:
 
 
 [AlphabetSoupCharity.ipynb](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity.ipynb)
 [AlphabetSoupCharity.h5](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity.h5)
 [AlphabetSoupCharity_Optimization.ipynb](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimzation.ipynb)
 [AlphabetSoupCharity_Optimization_Attempt_1.h5](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimization_Attempt_1.h5)
 [AlphabetSoupCharity_Optimization_Attempt_2.h5](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimization_Attempt_2.h5)
 [AlphabetSoupCharity_Optimization_Attempt_3.h5](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimization_Attempt_3.h5)
 
 
## Results:

 -  What variable(s) are considered the target(s) for your model?
 Sol:  Its the IS_SUCCESSFUL column in our target in the deep learning neural network. 
 -  What variable(s) are considered to be the features for your model?
 Sol:  The list of the variable is :
        - APPLICATION_TYPE
        - AFFILIATION
        - CLASSIFICATION
        - USE_CASE
        - ORGANIZATION
        - STATUS
        - INCOME_AMT
        - SPECIAL CONSIDERATIONS
        - ASK_AMT
  
  - What variable(s) are neither targets nor features, and should be removed from the input data?
  Sol: They were :  EIN and NAME and the original columns were encoded.
  
  - How many neurons, layers, and activation functions did you select for       your neural network model, and why? 2 hidden, 80 neurons on first and 30     on second.
  
    hidden_nodes_layer1 = 80 hidden_nodes_layer2 = 30
    
    
  ![](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/Resources/ScreenShots/Hidden_node_layer1%3D80_hidden_nodes_layer2%3D30.png)
    
    
   - Were you able to achieve the target model performance?
    Sol:  No, We able to accomplish 68% of accuraccy.
    
   - What steps did you take to try and increase model performance?
    
   
 Attempt 1: Removed Noisy Variable only
    
 ![](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/Resources/ScreenShots/Attpt1.png)
    
 Attempt 2 - Removing Noisy Variables & Adding additional neurons to the hidden layers and hidden layers
    
![](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/Resources/ScreenShots/Attmpt2.png)
    
    
 Attempt 3 - Removing Noisy Variables, Adding additional neurons to the hidden layers and hidden layers & Changing activation to tanh
    
![](https://github.com/urvish7/Neural_Network_Charity_Analysis/blob/main/Resources/ScreenShots/Attmpt3.png)
    
    
## Summary:

we attempt to do analysis with several ways in our experience and we were able to achieve the desired accuracy of 75%

In order to compare with the results of the deep learning model it is been suggested to do addtional analysis using the Random Forest classifier.




    
    
    
    
    
    
  

        
