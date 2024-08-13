Overview:
The purpose of this analysis is to cerate a model for nonprofit foundation Alphabet Soup that can help them select applicants for funding that have the best chance to succeed in their ventures. The goal is to design a model that has an accuracy score of 75% or higher.

Results:

Data Preprocessing

-What variable(s) are the target(s) for your model?
	IS_SUCCESSFUL is the target variable.

-What variable(s) are the features for your model?
	Every other column apart from IS_SUCCESSFUL are features.

-What variable(s) should be removed from the input data because they are neither targets nor features?
	EIN and NAME variables were removed because they were neither targets nor features.

Compiling, Training, and Evaluating the Model

-How many neurons, layers, and activation functions did you select for your neural network model, and why?
	Initially I had 3 layers. first hidden layer had 80 neurons, 2nd hidden layer with 30 neurons, and the output layer had 1. I used relu and sigmoid functions because we had used them in class. This resulted in an accuracy score of 72.86%.

-Were you able to achieve the target model performance?
	I was unable to achieve the target model performance.

-What steps did you take in your attempts to increase model performance?
	In my 1st optimization attempt I changed the neurons to 39,5,1 respectively, that resulted in an accuracy score of 72.78%. In my 2nd optimization attempt I added another layer and changed neurons to 92,91,90, and 1 respectively. This resulted in an accuracy score of 72.73%. In my 3rd optimization attempt I added another layer and changed neurons to 40, 30, 20, 10, and 1 respectively. This resulted in an accuracy score of 72.82%.

Summary:
Since I was unable to reach the goal of achieving 75% or higher accuracy score I would not recommend this model. I think experimenting with different activation functions, dropping a layer instead of adding, and adjusting neuron numbers might lead to the a 75% of higher accuracy score.

