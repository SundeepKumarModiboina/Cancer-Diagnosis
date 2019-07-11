# Cancer-Diagnosis
Multi Class Classification

The Cancer Diagnosis has two files.
1. Cancer data.csv and the 
2. Cancer Diagnosis.ipynb

1. Cancer data.csv

The cancer data.csv file is the input data file for predicting the cancer type.
This contains two features, Text and the Class.
Text is the description of the cancer type and Class is the cancer type.
Under the Class feature, there are a total of 9 Unique Class Types.
A sample of the top 5 rows of the csv file data is shown below.

	Text							Class
0	abstract background non small cell lung cancer...	1
1	abstract background non small cell lung cancer...	2
2	recent evid demonstr acquir uniparent disomi a...	2
3	oncogen mutat monomer casita b lineag lymphoma...	3
4	oncogen mutat monomer casita b lineag lymphoma...	4

2. Cancer Diagnosis.ipynb

This file is the Jupyter Notebook which has the code for classifying the Cancer Type.
Text processing is done and the models KNN, SVM, Naive Bayes, Random Forest are used.
