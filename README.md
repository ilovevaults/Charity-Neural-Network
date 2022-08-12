# Charity-Neural-Network
## Goals
The goal of this analysis was to use neural networking to help Alphabet Soup's business team determine from a list of companies which ones will receive loans from Alphabet Soup and if the company will be successful if it receives money. Python's TensorFlow library was used to train and evaulate the data given. The data used consists of a list of companies that are currently receiving funding
## Results  
### Data Repurposing
The target variable in this analysis was the "Is_Succesful" column while both the "EIN" and "NAME" columns were neither targets or features so both of them were removed. The rest of the columns that were not removed became the features.
For the first attempt there were 8 neurons used in the first layer while there were 6 in the second one. Both of these layers used the relu activation function and the outer layer used the sigmoid activation function. This was the result from the first attempt with all of these variables.
![Accuracy](https://user-images.githubusercontent.com/98357581/177649241-ac36315a-46f1-4e8d-bc3f-b3d561d54550.png)
After 3 more tries I was not able to reach the accuracy target of 75% but there was an improvement on my third try. The first thing I did was increase the number of nodes in each hidden layer to 200 instead of the default amount. The first hidden layer I changed the activatiion function to softmax but I still kept the number of epochs.
![Optimization Accuracy](https://user-images.githubusercontent.com/98357581/177650808-92a8b4d6-e2c5-4ddf-9e53-0dfa193e8bbf.png)
## Summary
The next steps I can try to take to increase the accuracy are to make sure the columns that are being uses are relevant, learn more about different activation functions and see which ones will fit best with the dataset, and figure out the optimal amount of neurons and layers to use.
