# deep_learning

Overview of the analysis: Explain the purpose of this analysis.
Answer: The purpose of this analysis is to determine which companies would become successful if BeautifulSoupCharity funded them. So in this data, the targeted column is "IS_SUCCESSFUL".

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model? AnswerThe Is_SUCCESSFUL is the veriable that is the target in this model. What variable(s) are the features for your model? The ramianing columns excluding IS_SUCCESSFUL is used as the features for this model. What variable(s) should be removed from the input data because they are neither targets nor features? Answer The "NAME", and "EIN" was removed and for the second attempt the "NAME" feature was removed.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Answer:I have chosen 3 hidden layers with many neurons. The activations I used are: first, real, and for other layers, sigmoid was used. Because it enhances the level of accuracy up to 75%. 
Were you able to achieve the target model performance? 
Answer Yes I tried to achieve the best result and achieve the target model performance, but not completely. 
What steps did you take in your attempts to increase model performance? 
Answer: I added another hidden layer, as I had 2 hidden layers, and then I added another layer using the sigmoid activation function. I tried to figure out if I should increase or decrease the value for hidden_nodes_1, hidden_nodes_2, and hidden_nodes_3. Once I increase the value, it gives me higher performance, but when I try to add more, it gives me a lower model accuracy score. 
Summary: Summarize the overall results of the deep learning model. AnswerThe result to find the accuracy in this model was accomplished as it was asking for 75%. We can classify which organizations will be successful with the funding by BeautifulSoupcharity. Include a recommendation for how a different model could solve this classification problem. 
