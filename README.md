# Deep_learning_challenge


#Overview# 

"*" The aim of this undertaking is to construct a binary classifier that estimates the likelihood of applicants attaining prosperity following financial support from Alphabet Soup. To achieve this, we will make use of the attributes available in the dataset and employ diverse machine learning approaches to train and assess the model's effectiveness. The model which is being enhanced and tested is to attain an accuracy score of 75% or greater. 


#Results#

##Data Preprocessing##

What variable(s) are the target(s) for your model?

"*" The target variable in this model is "IS_SUCCESSFUL"

What variable(s) are the features for your model?

"*" The features for my model are NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, ASK_AMT.

What variable(s) should be removed from the input data because they are neither targets nor features?

"*" EIN , NAME were removed



##Compiling, Training, and Evaluating the Model##

How many neurons, layers, and activation functions did you select for your neural network model, and why?
"*" Two layers for the model were used along with each different models. 

Were you able to achieve the target model performance?
"*" I was not able to get the target performance of 75%

What steps did you take in your attempts to increase model performance?
"*" While trying to optimize my model's performance, I added a third layer with more neurons and each having different activation functions. STATUS category and SPECIAL_CONSIDERATIONS were removed. The cutoff values for  "CLASSIFICATION" and "APPLICATION_TYPE" were altered in hopes of finding data with better fit. 

#Summary#

Despite my efforts, even post optimization the accuracy of the model was 0.7293, still short of the required 75%. 
In order to enhance the model even further, I would contemplate modifying the dropout layers by adjusting their rates or eliminating them completely. Furthermore, I would investigate alternative activation functions and conduct experiments by altering the number of layers and neurons within the model's architecture is my prediction.

I also can include back the original NAME and EIN categories that were initially dropped in the starter file to see if it makes nay difference in the results. 
