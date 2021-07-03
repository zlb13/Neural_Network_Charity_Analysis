# Neural_Network_Charity_Analysis

## Overview of Analysis
This analysis created a binary classsifier to predict whether applicants will be successful if funded by Alphabet Soup. The csv file was preproccessed  for a Neural Network Model using pandas and Sckit-learns libary. The model is then compiled, trained and evaluated to calculate the models loss and accuracy. Finally, TensorFlow was used to optimize the model to achieve a target predictive accuracy higher than 75%.


### Results

* Data Preprocessing

Target variable : IS SUCCESSFUL

Feature variables: 

APPLICATION_TYPE            
AFFILIATION                
CLASSIFICATION              
USE_CASE                    
ORGANIZATION                
STATUS                      
INCOME_AMT                   
SPECIAL_CONSIDERATIONS       
ASK_AMT                   
 
Removed Variables: EIN and Name

 * Compiling, Training, and Evaluating Model

 Two hidden layers wer used for the modiel. One with 8 neurons and the other with 5 neurons. The ReLu activation function used for both hidden layes and sigmoid activation function for th outer layer. Unfortunely the the model did not achieve the target model perfomance of 75%. Model accucary was only 51%. 

 Three attempts were made to optimzize and increase the model perfomance. First the activation function for the hidden layers were changed to Tanh. Second, additional neurons were added to the hidden layers and the epoch inreased to 200. Finally, an additional hidden layer was added.

#### Summary

In Summary, the Neural network model of accucacy is only 50%, which would not be ideal to use.  Even with the attempts to optimize the model the results did not improve significanltly. All three optimizations attempts only improved slightly to 55% accuracy. Another machine model, I recommend to use is the Logistic Regression model, which is also a binary classification model.