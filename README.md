# Neural_Network_Charity_Analysis

### Overview of the analysis: Explain the purpose of this analysis.
Alphabet Soup, is a nonprofit philanthropic foundation dedicated to help various organizations around the world. By building a deep learning neural network with an at least 75% predictive accuracy we will attempt to determine the success or failure of charitable donations to non-profits.

This neural network is built to help Alphabet Soup make future decisions on who should receive charitable grants based on historical data. The dataset contains information from 34,000 organizations which will be used to build a model with high predictive accuracy.

### Results: Using bulleted lists and images to support your answers, address the following questions.


##### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- IS_SUCCESSFUL: was the money used effectively

What variable(s) are considered to be the features for your model?
- APPLICATION_TYPE: Alphabet Soup application type
- AFFILIATION: Affiliated sector of industry
- CLASSIFICATION: Government organization classification
- USE_CASE: Use case for funding
- ORGANIZATION: Organization type
- STATUS: Active status
- INCOME_AMT: Income classification
- SPECIAL_CONSIDERATIONS: Special consideration for application
- ASK_AMT: Funding amount requested

What variable(s) are neither targets nor features, and should be removed from the input data?
- EIN and NAME: Identification columns

##### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?


Were you able to achieve the target model performance?
- No, the model achieved 73% accuracy

What steps did you take to try and increase model performance?
 
### Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
