Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

1. What variable(s) are the target(s) for your model?
**Target is the Is-Successful column**
2. What variable(s) are the features for your model?
**Features list of this model are the name, application type classification use_case organization income special consideration status and ask amount**
3. What variable(s) should be removed from the input data because they are neither targets nor features?
**EIN (Employee Identification)

Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
**3 hidden layers each with many neurons becayse computes to increase the accuracy above 75%**
2. Were you able to achieve the target model performance?
**Yes**
3. What steps did you take in your attempts to increase model performance?
**Required to convert the NAME into data points which has the biggest impact on improving proficiency**

Summary: Summarize the overall results of the deep learning model. 

**Overall the accuracy above 75% we are able to correctly classify each in the test 75% of the time.
And an applicant has an 80% chance to be successful if they the following:
Name of applicants appears more than 5 times
type of applications such as T3-T8, T10 & T19
Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
