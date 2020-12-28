# T20 Cricket Score Prediction
Currently, in T20 cricket matches first innings score is predicted based oncurrent run rate during the ongoing match. It does not take into consideration other factors like cumulative overs, cumulative runs, wickets left, etc. Thus, in this repository a method has been proposed to predict the score of the first innings using machine learning. Before proposing this method,a comparative analysis has been done using multiple linear regression, random forest regression and artificial neural networks. It has been found in the results that error in random forest regression is less than current rate method in estimating the final score

##### Codes
- Regression_Forest_code.py: 
It has two ML algos
a. Multiple regression
b. Random forest regression

- ANN_code.py:
It has deep learning algo:
a. Artificial neural networks

- Dataset
Training dataset
all_2009-8: IPL 2009-2017

- Testing dataset
2018: IPL 2018 
2019: IPL 2019 
