# Neural Network Model Report

1. Overview of the analysis: Explain the purpose of this analysis.
   The purpose of this analysis is to create a neural network model that can predict whether applicants will be successful if funded by Alphabet Soup.  
2. Results:  

### Data Preprocessing  

- The target variable is the "IS_SUCCESSFUL" column - which indicates whether the money was used effectively.
- For the first model made in the "Starter_Code.ipynb" notebook, the variables used as features included: application type, affiliation, classification, use case, organization, status, income amount, special considerations and ask amount. For the three models that were made in the "AlphabetSoupCharity_Optimization.ipynb" file, the variables used as features included all that were formerly mentioned, except for the "special considerations" feature. This feature was omitted for the 3 models in the effort of increasing model accuracy.
  ![model features](https://github.com/nishithapliyal/deep-learning-challenge/blob/main/Screenshot%202024-10-20%20at%209.36.50%20PM.png)
- The variables that were removed from the input data were the "EIN" and "NAME" columns because these served as identification columns that were neither targets nor features in the model.  

### Compiling, Training, and Evaluating the Model

- For the first neural network created, I created two hidden layers, one with 80 neurons and the other with 30 neurons. The relu activation function was used for both layers. For the subsequent neural networks created in the effort to increase accuracy, the number of neurons were adjusted, another hidden layer was added to one of them, and activation functions were varied. I chose the number of neurons based on what I have learned in class. I used the relu and tanh activation functions based on what I learned in class.
- I was not able to reach the target model performance of a 75% accuracy. The highest accuracy model I achieved was about 73% accurate.
- To increase model performance, I changed the number of neurons for each hidden layer, added another hidden layer, changed activation functions, and dropped one feature from the dataset. I also changed the number of epochs for some of the models.


3. Summary:
- The deep learning model achieved an accuracy of about 73%. This means the model can accurately predict whether applicants will be successful 73% of the time. A different model that utilizes different activation functions and more hidden layers may be able to increase model accuracy. Binning the features differently may also create a more accurate classification model. 
