# Team Members

Ashutosh Patil <br>
Sagar Shashikant Sutar <br>
Satya Bhaskara Ganesh Susarla<br>
Sayali Nilangekar <br>

# User Guide  
There are three Jupyter Notebook files in this repository: (1) 255_Project_Regression.ipynb, (2) 255_Regression_Test.ipynb, & (3) 255_Project_Classification.ipynb

- 255_Project_Regression.ipynb: This file contains the code for running the regression analysis on the dataset and training the regression models

- 255_Regression_Test.ipynb: This file contains a sandbox type environment for loading the saved regression models in the 'models' folder and using them for predictions and scoring on the 'test_data_reg.csv' file. The user can use the pretrained models to generate predictions and do other functions.

- 255_Project_Classification.ipynb: This file contains the code for training and running classification models on the dataset

The dataset* necessary to run these files can be found at the following website: https://archive.ics.uci.edu/ml/datasets/yearpredictionmsd 

*NOTE: Due to the large file size of the dataset, we are unable to upload the dataset directly to GitHub. Therefore, please download the dataset from the aforementioned website.

# Other Files
- pca.joblib: This file contains the fitted PCA transform. This PCA transformer is loaded in the sandbox file and is ready to be used on test data.

- minmaxscaler.joblib: This file contains the fitted MinMaxScaler from the regression analysis file. This MinMaxScaler is loaded in the sandbox file and is ready to be used on test data.

- test_data_reg.csv: This file contains test data that is loaded in the regression test sandbox file mentioned above
# Project Description

Our project presents a regression and classification analysis of a subset of the Million Songs Dataset. We have attempted to use various regression models to successfully predict the release year of a song and also tried to use various classification models to categorize songs by decade based on various features given in the dataset linked above.
