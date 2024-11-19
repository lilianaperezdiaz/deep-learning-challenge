# Deep Learning 

**Dependencies**
1. sklearn.model_selection
2. sklearn.preprocessing
3. pandas
4. tensorflow 

**Overview**

Running this machine allows us to process data to analyze the patterns within the data through neural networks. With neural networks we start by splitting the dataset, scale and standardize each feature, fit the model to the training data, transform the data and create a sequential model. Finally, we are also able to add the layers and output layers to identify the structure of the sequential models. By training the model we are allowing the machine to find all parameters with the lowest loss while the sequential model allows us to stack the layers of data which are also known as the neural networks. This model is measuring target variable IS_SUCCESSFUL through a binary of 0 for not successful and 1 for successful with the feature variable’s being all of the other columns listed once EIN and NAME columns were removed since they were neither target or features. 

**Results***

Our model for the Alphabet Soup Charity Optimization at 100 epochs shows that the more epochs run, the higher the accuracy which decreases the amount of loss.  The outcome of this model is showing us if the money that was funded to the applicates was used successfully or not. By adding a validation split to the machine and altering the hidden node layers of the models we can attempt to increase the accuracy of the model to get closer to 75%. I was able to decrease both the first and second hidden node layers to increase the accuracy of the model to start at 74.11% with a loss of 53.49% and end at 74.62% with a loss of 53.11%. I decreased the layers of the model to reduce the possibility of overfitting the data and have the model work better with the training data without having the model memorize the training data. With the decreased layers the model got slighting closer to the target however it did not reach 75% after various tries. To continue improving the model I changed the layers multiple times to see which combination allowed the model to get closer to 75%. 
![image](https://github.com/user-attachments/assets/cb4557ab-ece6-401d-bda5-dcc86365d187)


**Resources**
https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.cs 
