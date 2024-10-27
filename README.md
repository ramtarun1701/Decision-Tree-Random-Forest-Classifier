# Decision-Tree-Random-Forest-Classifier
Decision Tree and Random Forest 

The dataset consists of seven columns, labeled from 0 to 6. The features appear to represent various categorical attributes related to car evaluations, with the last column (6) likely being the target variable for classification. I'll provide a brief overview of the dataset based on the initial inspection:

Features: Six columns (0 to 5) represent car attributes, potentially like price, maintenance cost, number of doors, seating capacity, trunk size, and safety.
Target Variable: Column 6 appears to classify car evaluation outcomes, e.g., "unacc" (unacceptable).

The dataset has 1,728 entries with seven columns, all of which are non-null and categorical. Here’s a summary of each column:

Features:

Column 0 and 1: Values are ['vhigh', 'high', 'med', 'low'], likely indicating levels like "very high" or "low."
Column 2: ['2', '3', '4', '5more'], possibly representing the number of doors.
Column 3: ['2', '4', 'more'], possibly representing seating capacity.
Column 4: ['small', 'med', 'big'], likely indicating trunk size.
Column 5: ['low', 'med', 'high'], possibly representing safety levels.
Target Variable (Column 6): ['unacc', 'acc', 'vgood', 'good'], which may represent car acceptability ratings. 

Next we had preprocessed the data by encoding categorical variables and splitting the dataset into training and testing sets

Decision Tree Cross-Validation Accuracy: 0.7934891513780682
Random Forest Cross-Validation Accuracy: 0.8091061405713328 
