# Module 13: alphabet-soup

# Description

As a risk management associate at Alphabet Soup (a venture capital firm), we have been tasked with using a neural network (deep learning model) to predict the likely success of applicants if funded by Alphabet Soup.

Both categorical and numerical data for applicants were used in the model, which can be found in the venture_funding_with_deep_learning.ipynb notebook. In all three models were created. The original model with two hidden layers (run on 50 epochs) and two alternate models. The first alternate model, looked at improving the models accuracy by adding another hidden layer and the second alternate model built on this by increasing the number of epochs from 50 to 100. Results of each models accuracy are shown below:

|                   Model                             |    Accuracy    |	 
|-----------------------------------------------------|----------------|
| Original (2 hidden layers run on 50 epochs)         |	   0.73236	   |   
| Alt Model 1 (3 hidden layers run on 50 epochs)      |	   0.73084	   |   
| Alt Model 2 (3 hidden layers run on 1000 epochs)    |	   0.73037     |   


From the above results we see that the original model produced the highest accuracy score. The alternate models, although being run with more layers and epochs produced comparable accuracy scores but were still not as good as the original model.
