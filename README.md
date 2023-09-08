# American-Citizens-Annual-Income-Prediction

The dataset used in this notebook contains information about individuals' demographics, education, work experience, and other relevant factors. The income column in the dataset serves as the target variable, categorized into two classes: "<=50K" (indicating income less than or equal to 50,000)and ">50K"

You also can check my notebook for this dataset to earn more information.

Column	Description
age	: Age
workclass : 	A general term indicating the employment status of an individual.
fnlwgt	 : Final weight, representing the number of individuals that this row represents (a representative sample).
education	 : Highest level of education achieved by an individual.
education.num : 	Highest level of education achieved by an individual in numerical form.
marital.status	: Marital status of an individual. Note that Married-civ-spouse refers to a civilian spouse, and Married-AF-spouse refers to a spouse in the Armed Forces.
occupation	: General type of occupation of an individual.
relationship :	Relationship of this individual with others, for example, spouse (Husband). Each data point has only one relationship.
race	 : Race
sex	Biological : sex of an individual.
capital.gain	: Capital gains of an individual.
capital.loss	: Capital losses of an individual.
hours.per.week	: Number of hours the individual reported working per week.
native.country	 : Country of origin.
income	: Income, less than or equal to $50,000 (<=50K) or more than that (>50K).

python packages:

1) numpy
2) pandas
3) matplotlib
4) seaborn
5) plotly ( express , graph_objects,offline)
6) dataprep
7) train test split
8) tensorflow
9) from sklearn import metrics
10) from sklearn.metrics import classification_report, confusion_matrix,precision_score, f1_score
11) from sklearn.preprocessing import LabelEncoder, StandardScaler, OrdinalEncoder
12) from imblearn.over_sampling import SMOTE

questions :

1) give an overview about the data?
2) check if there is missing values or duplicates?
3) get some information about the target column?
4) get data description or statistical summary?
5) check the data nun unique values?
6) drop the education column?
7) replace the ? with NaN to detect the missing values easily?
8) get the stats and the insigths about the data?
9) plot the correlation about the data?
10) plot the missing values ?
11) make an bar chart about the missing values counts?
12) make a pie chart to get the percentage of the incomes that <= 50k and > 50k ?
13) make a label encoder to the columns of the data?
14)  Replace missing values with the most frequent value?
15)  make a  Box plot for numreical values and detecting outliers?
16)  make a Histogram plot for numerical values?
17)  make a scatter plot for numerical values?
18)  make a correlation heatmap to see the correlation between the features?
19)  Balancing data by  seperating dataframe into X and y?
20)  Increasing values and making our data balaced by using SMOTE?
21)   Create balanced X and y and split it for train and test ?
22)   use standard scaler to standarize the features?
23)   modeling using deep learning ANN ?
24)   make a neural network by putting input layers and two hidden layers and output layers?
25)   fit the model with the x_train and y_train with epochs = 20 ?
26)   get the final accuracy and the loss of the test ?
27)   get the final accuracy and the loss of the train ?
