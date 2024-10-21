# Neural Network Model Report

1. Overview of the analysis: Explain the purpose of this analysis.
   The purpose of this analysis is to create a neural network model that can predict whether applicants will be successful if funded by Alphabet Soup.  
2. Results:  

### Data Preprocessing  

- The target variable is the "IS_SUCCESSFUL" column - which indicates whether the money was used effectively.
- For the first model made in the "Starter_Code.ipynb" notebook, the variables used as features included: application type, affiliation, classification, use case, organization, status, income amount, special considerations and ask amount. For the three models that were made in the "AlphabetSoupCharity_Optimization.ipynb" file, the variables used as features included all that were formerly mentioned, except for the "special considerations" feature. This feature was omitted for the 3 models in the effort of increasing model accuracy.
- The variables that were removed from the input data were the "EIN" and "NAME" columns because these served as identification columns that were neither targets nor features in the model.  

### Compiling, Training, and Evaluating the Model

- For the first neural network created, I created two hidden layers, one with 80 neurons and the other with 30 neurons. The relu activation function was used for both layers. For the subsequent neural networks created in the effort to increase accuracy, the number of neurons were adjusted, another hidden layer was added to one of them, and activation functions were varied.  
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take in your attempts to increase model performance?


3. Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
