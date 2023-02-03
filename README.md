# Neural_Network_Charity_Analysis

## Project Over view

This machine learning project aimed to build a classifier that can accurately predict whether a charity will have a successful outcome if they fund a particular applicant. This was accomplished by creating a binary classifier capable of predicting whether applicants will be successful if supported by Alphabet Soup.

## Results
- Data preprocessing The target variable in this model was the IS_SUCCESSFUL column. That referred to whether the money was used effectively or not.

- Compiling, Training, and Evaluating the Model In the first layer, the number of neurons used was 80, and the activation function was the ReLU function. In the second layer, the number of neurons used was 30, and the activation function remained the same. Finally, the procedure used was the sigmoid function for the output layer.

- To achieve an accuracy greater than 75%, we dropped only the EIN column and applied bucketing on the NAME column. We also used three hidden layers of 100 neurons, 30 neurons, and ten neurons, respectively; for the second and third hidden layers, we used the sigmoid activation function. The epochs number wasn't changed. This resulted in an accuracy of almost 79%, which successfully met our expected value.

## Results

In this project, we used neural networks to build a classifier that could accurately predict the likelihood of a successful outcome for charities that funded particular applicants. The classifier was trained on a dataset of previous funding decisions and their outcomes and achieved an accuracy of 78.9% when tested on a separate data set. This high level of precision allows charities to make more informed funding decisions, increasing the chances of a successful outcome for both the charity and the funded applicant. Overall, using neural networks proved to be an effective method for building a classifier that can accurately predict the success of charitable funding decisions.
