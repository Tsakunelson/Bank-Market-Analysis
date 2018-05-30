# Bank-Market-Analysis
Problem Statement
- Marketing selling campaigns constitute a typical strategy to enhance business.
- Companies use direct marketing when targeting segments of customers by contacting them to meet a specific goal.

In this project, we predicting the success of telemarketing calls for selling bank-long term deposits using Neural Networks (Keras Framework) as classifier models
 NB: A term deposit is a cash investment held at a financial institution for an agreed rate of interest over a fixed amount of time. 

If the classifier has high accuracy, the banks can arrange a better management of available resources by focusing on the potential customers “SELECTED” by the classifier.


Dataset Description

- The dataset is related with direct marketing campaigns of a Portuguese banking institution. 
- 41,188 samples.
- 20 features: 
    Age
    Job
    Account balance
    Number of contacts performed before this campaign and for this client 
    Outcome of the previous marketing campaign
    Etc… 
- One target/output/dependent Variable:  Has the client subscribed a term deposit? (yes/no)/(1/0)

One hot encoding
This technique was used in data processing/cleaning to render categorical variables easier to manage and compute


Framewok Description

Deep Neural Network with 5 layers
  - Input layer (64 neurons)
  - First  hidden layer (32 neurons) 
  - Second hidden layer(16 neurons) 
  - Third hidden layer(8 neurons)
  - Output layer (1 neuron)

Cross entropy used as cost functon 

Activation functions: Relu(fo hidden layer), Sigmoid function(for output layer)

Framework: Keras

Classification Report

   precision    recall  f1-score   support

     (No)0       0.89      1.00      0.94     29254
    (Yes)1       0.00      0.00      0.00      3696

avg / total       0.79      0.89      0.84     32950
