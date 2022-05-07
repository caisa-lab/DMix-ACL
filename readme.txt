Instructions for running the model:  

1) Install the required packages using requirements.txt 
2) Replace the Dataset PATH to where it is stored locally. (Line 422)
3) Replace the Probability Matrix to the place where it is locally stored. (Line 1599)
4) Set the Threshold value. (Line 545)
5) Change bert-base-uncased to bert-base-multilingual-uncased incase running for languages other than english. (Line 197,465,532)
6) Replace the num_label with the number of labels in the dataset (Line 311)
7) Number of training samples in the dataframe (Line 443)


We have used some standard GLUE Datasets that could be downloaded using the transformer dataset or their official webpage.

For the Distance Matrix, run the code given in matrix.py.

The code is well documented for further explanation.