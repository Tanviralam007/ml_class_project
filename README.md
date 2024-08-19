# ML Class Project

1. [Objective](#objective)
2. [Data](#data)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Data Visualization](#data-visualization)
    - [Class Distribution](#class-distribution)
    - [Descriptive Statistics](#descriptive-statistics)
4. [Modeling](#modeling)
5. [Evaluation](#evaluation)
6. [Conclusion](#conclusion)

Here is the Data Dictionary:
- [Data Dictionary](./data_dict.md)

### **Objective**
The notebook aims to predict heart disease using machine learning models, employing various data analysis techniques and classifiers on a heart disease dataset.

### **Data**
The dataset, `heart.csv`, is loaded into a Pandas DataFrame. It contains several features related to health conditions, such as age, sex, chest pain type, cholesterol levels, maximum heart rate, and a target variable indicating the presence of heart disease.

### **Exploratory Data Analysis (EDA)**
- **Data Visualization**: The notebook uses Matplotlib and Seaborn to visualize relationships between variables, such as heart disease frequency by sex, age vs. maximum heart rate, and heart disease frequency by chest pain type.
- **Class Distribution**: A bar plot is used to show the distribution of heart disease vs. no heart disease cases.
- **Descriptive Statistics**: Functions like `df.describe()` provide summary statistics for numerical features, while `df.info()` is used to inspect the data types and check for missing values.

### **Modeling**
The dataset is split into training and test sets, preparing it for modeling. The notebook explores the following models:
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Random Forest Classifier**

### **Evaluation**
- **Model Metrics**: The models are evaluated using common classification metrics such as precision, recall, F1-score, and confusion matrices. ROC curves are also plotted to visualize the performance.
- **Hyperparameter Tuning**: `RandomizedSearchCV` and `GridSearchCV` are used for hyperparameter optimization to improve model performance.

### **Conclusion**
The notebook successfully builds and evaluates machine learning models for heart disease prediction. The models' performance is assessed through key metrics, providing insights into how well each classifier predicts heart disease. This notebook is still undergoing the contribution of some of my groupmates for optimization.
