# DataScience Portfolio

Repository containing portfolio of data science projects completed by me for academic and self learning purposes. The projects are written in Python(Jupiter Notebook). Click on the ipynb file to check the full analysis and code by me in each project. 

## Projects:

### [Building a Recurrent Neural Network Step by Step](https://github.com/rupontn/DataScience/blob/master/Building%20a%20Recurrent%20Neural%20Network%20Step%20by%20Step.ipynb)

Built a recurrent neural network step by step as part of coursera "Sequence Model" by deeplearning.ai. A basic RNN module is created where input time steps is equal to output time steps. At first the code for one time steps is created in  rnn_cell_forward function. Then it is looped over all time steps by rnn_forward function. rnn_forward function implement the forward propagation over time steps.  Main problem with simple RNN Network is the vanishing gradient problem. To solve this problem LSTM model is built where predicted value at each time steps will be estimated using local context. In LSTM cell there will be a forget state which will keep track of the important previous state. It has a value beteen 0 and 1. There is also a candidate value and update gate which decides which values are important to go to next state. one time step of a LSTM network is created by lstm_cell_forward function. lstm_forward function implement the forward propagation over all the time steps.

### [Titanic Survival Prediction](https://github.com/rupontn/DataScience/blob/master/Titanic%20Survival%20Prediction%205.ipynb)

This projects explore data analysis, data visualization and machine learning algorithms to predict survival of passengers on the titanic. Dataset is publicly available. In particular, this version was downloaded from the [Kaggle competition website](https://www.kaggle.com/c/titanic).
The jupyter notebooks contain the following:
 1. Feature exploration about the passengers on the titanic.
 2. Visualization of different feature to find out relationship with target survival prediction.
 3. exploration about the association of  different features of  dataset to predict survival of patient.  
 4. Preprocessing of the dataset for model building, including feature extraction and taking care of missing data. 
 5. Extraction of additional features from existing ones. The idea behind is to try to capture trends and insights that could be helpful     for the learning algorithms.
 6. General model building without deep adjustment of the parameters to get an idea of which model would work best for this dataset


### [House Price: Advance Regression](https://github.com/rupontn/DataScience/blob/master/House%20Price_%20Advance%20Regression%20Technique.ipynb)
This is another project from [Kaggle competition ](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) where 79 explanatory variable describes every aspects of a residential home and these factors are used to predict the house price. 
The jupiter notebook contains the following:
1. Taking care of missing values: There were a lot of missing values in the categorical variable and numerical variable. The missing    values in Categorical variable were replaced by most frequently appeared variable and missing value in numerical variable were replaced by the mean value. There were some variables where missing values were more than 40% of the actual data. These factors/variables were rejected to avoid wrong prediction.  
2. Feature Engineering: Encoding categorical variable and finding out that distribution in target variable is skewed in nature. Taking log of the target variable maked it more normal distributed dataset and improves the overall accuarcy. 
3. Train and Test the dataset: The existing dataset was splitted between validation set and training set to avoid overfitting. 
4. Evaluating different ML models: Lasso Model, Ridge Model, decision tree Regression, Random Forest Regression were used to predict the target price. 


### [Planar Data Classification with Neural Network](https://github.com/rupontn/DataScience/blob/master/Planar_data_classification_with_onehidden_layer_v6c.ipynb)
This project is a part of Coursera's Neural network and Deep Learning Course. It solves a Planar Data classification problem by using neural network. The Jupiter Notebook contains the following-
1. Use a 2 class classification neural network with a single hidden layer. 
2. Compute cross entropy loss. 
3. Compute forward and backward propagation. 

### [Cat Image Classifier with Neural Network](https://github.com/rupontn/DataScience/blob/master/Cat%20Image%20Classifier%20with%20Logistic_Regression%20with%20a%20Neural%20Network%20mindset.ipynb) 

This project is a part of Coursera's Neural network and Deep Learning Course. It solves Cat vs non Cat classification problem building a image recognition algorithm by deep neural network. 
