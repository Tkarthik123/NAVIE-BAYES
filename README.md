# NAVIE-BAYES

**Decision Tree – CART Algorithm**

   
**Aim:**

Write a program to learn construction of the decision tree by using CART algorithm. Use 
an appropriate data set for building the decision tree and apply this knowledge to classify a new 
sample.
Theory:
CART (Classification and Regression Trees) is a machine learning algorithm used for 
both classification and regression tasks. It operates by recursively partitioning the data into 
subsets based on the most significant feature that best separates the classes or minimizes the 
regression error. CART builds a binary tree where the internal nodes represent features, and the 
leaf nodes correspond to the class labels or predicted values. This algorithm is highly 
interpretable and can handle both numerical and categorical data, making it widely used in 
various fields due to its simplicity and effectiveness.
● Gini index is a metric for classification tasks in CART. It stores sum of squared 
probabilities of each class. We can formulate it as illustrated below.
Gini = 1 – Σ (Pi)2
for i=1 to number of classes


**Algorithm:**


Step 1: Install Kaggle in colab notebook by using command !pip install kaggle

Step 2: Create a directory with name .kaggle by using the command ! mkdir ~/.kaggle

Step 3: Do the procedure to download kaggle.json file and upload to colab

Step 4: Copy this kaggle.json file into the .kaggle directory by using command 
 ! cp kaggle.json ~/.kaggle/
 
Step 5: Change the permissions of the Kaggle.json file with following command
 ! chmod 600 ~/.kaggle/kaggle.json
 
Step 6: Now download dataset by using command 
 !kaggle datasets download -d saurabh00007/iriscsv
 
Step 7: If the file is in Zip format unzip it by the command ! unzip iriscsv.zip

Step 8: Now start working on this iris dataset after importing essential libraries.

Step 9: Read and verify the dataset by checking its feature names, shape, info, head, tail, unique
etc…

Step 10: Import following CART specific libraries
from sklearn.tree import DecisionTreeClassifier
from sklearn.model_selection import train_test_split
from sklearn import metrics

Step 11: Fix target variable ‘y’ as feature ‘Species’ and X as all remaining features except id

Step 12: Split dataset into training set and test set

Step 13: Create Decision Tree classifer object

Step 14: Train Decision Tree Classifier

Step 15: Predict the response for test dataset

Step 16: Calculate accuracy of the model

Step 17: Print decision tress

**Result:**

CART Algorithm is implemented with suitable dataset and performance is measures
