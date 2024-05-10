Overview of the analysis: Explain the purpose of this analysis.

In this challenge, I used a machine learning model to predict the charity's success rate.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?

The target variables are the data in the 'IS_SUCCESSFUL' column.

What variable(s) are the features for your model?

The features are EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

What variable(s) should be removed from the input data because they are neither targets nor features?

Variables removed were EIN column and NAME column.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

In the first model, I used 2 hidden layers with 100 neurons and ReLU activation.  Output layer used the Sigmoid activation.

Were you able to achieve the target model performance?

I was able to achieve 75% accuracy with this model.

What steps did you take in your attempts to increase model performance?

Adding 2 hidden layers increase the accuracy to just under 75%.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
