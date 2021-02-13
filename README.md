# Computer_vision_project

The aim of this project is bank churn prediction, i.e whether a customer will leave the bank or stay with the bank. This porject has two parts. The first part is 
Cascade_Tabnet(credit: https://github.com/DevashishPrasad/CascadeTabNet) uses CNN to read tabular data from scanned pdf images. 
Steps : 1. We have to import the necessary modules. 2. Clone the repository of the Cascade_Tabnet. 3. Load the pre-trained model. 4. Provide input to the code.
The input of the code is a scanned png image which contains tabular data. 5. Store the output of the data. The output is to be used for further analysis of data.  


The second code analyses the data using deep neural networks and predicts the churning. Given that we obtained the transactions data from Cascade_Tabnet, the next steps are : 1. Read the data from Cascade_tabnet output. For this case lets use a demo file. 2. The lodaded data consists of several coloumns viz. Name of the customer, Age,country,  bank balance, Whether the customer stayed or left the bank etc. We should plot different parameters to see any correlation between them. 3. The attributes include the customer details and the labels include whether the customer left or stayed in the bank. The next step includes the pre-processing step where the attributes are converted into one-hot encodings. 4. The next step includes building the model architecture and tuning the hyperparameters. 5. This is followed by training the model. 6. Finally, we can test our model with predictions. The input should be any customer with name, counrty , age, balance. The output should be whether the customer will stay or leave the bank. This is confirmed by the evaluation of the confusion matrix.   
