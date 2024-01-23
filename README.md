# deep-learning-challenge


###Explain the purpose of the analysis 
### to find the right method and correct tool that help defining the proper applicants for funding with the best chance of success in their ventures

###What variable(s) are the target(s) for your model?
### is successful figures 

###What variable(s) are the features for your model?
### every column except is successful and the other two dropped EIN AND NAME 

###What variable(s) should be removed from the input data because they are neither targets nor features?
### EIN AND NAME 

###How many neurons, layers, and activation functions did you select for your neural network model, and why?
### I used three layers sith various number of hidden nodes in order to maximize the perromance but i was not able to maike it 75 percent or above 

###Were you able to achieve the target model performance?

###What steps did you take in your attempts to increase model performance?
###increase the layers removed extra columns and in addition to adding more extra nodes switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy.

###Summarize the overall results of your model
### in general, the deep learning model was around 72% as ccuraccy percentage, in predicting the classification problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. This could be achieved by doing additional data cleanup up front, as well as by using a model with different activation functions and iterating until higher accuracy is reached.
###Describe how you could use a different model to solve the same problem, and explain why you would use that model 
### we can use from other models like logistic regression, random forest, support vendor machine or decision tree 