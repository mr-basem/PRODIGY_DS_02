# PRODIGY_DS_02
Titanic Dataset Analysis and Machine Learning Model
Project Overview
This project is part of my data science internship at Prodigy InfoTech. The goal is to predict the survival of passengers on the Titanic using various machine learning models and explore data patterns through visualizations.

Dataset
The dataset used for this project is the Titanic dataset, which contains information about the passengers aboard the Titanic. The key features include:

PassengerId: Unique ID for each passenger
Survived: Survival status (1 = survived, 0 = did not survive)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Sex: Gender of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Fare: Passenger fare
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Key Steps
1. Data Preprocessing
Removed irrelevant columns such as Name, Ticket, and Cabin.
Handled missing values for the Age and Embarked columns.
Converted categorical variables (such as Sex and Embarked) into numeric format for model training.
2. Exploratory Data Analysis (EDA)
Survival Distribution by Gender: Created a bar chart to analyze survival by gender, with males and females represented by distinct colors.
Age Distribution: Created histograms to visualize the distribution of ages for both survivors and non-survivors.
Family Size Analysis: Analyzed the relationship between family size (SibSp & Parch) and survival.
3. Machine Learning Models
Logistic Regression: Achieved 82% accuracy on training data and 80% on test data.
Support Vector Classifier (SVC): Achieved 80% accuracy on test data.
K-Means Clustering: Applied unsupervised clustering to identify passenger groups.
4. Model Evaluation
Confusion matrices were created to evaluate the performance of each model.
Accuracy scores and error rates were analyzed to identify the best-performing model.
Results
The Logistic Regression model was the most effective for predicting survival with an accuracy of 82%.
Visualizations provided insights into key survival factors, such as gender and age.
Visualizations
Survival by Gender: Bar chart showing survival rates for males and females.
Age Distribution: Histograms showing the distribution of ages for both survivors and non-survivors.
Fare Distribution: Visualized the distribution of ticket prices and calculated key statistics such as the mean and mode.
Correlation Heatmap: Displayed correlations between features like Age, Fare, and Survived.
Technologies Used
Python
Libraries: pandas, matplotlib, seaborn, scikit-learn
Machine Learning Algorithms
Logistic Regression
Support Vector Classifier (SVC)
K-Means Clustering
Jupyter Notebook: For code execution and visualization.
Future Work
Further tuning of machine learning models for improved accuracy.
Implementing additional machine learning algorithms (e.g., Random Forest, XGBoost).
More in-depth feature engineering to extract hidden insights from the data.
Acknowledgements
I would like to thank Prodigy InfoTech for giving me the opportunity to work on this project as part of my internship. It has been a great learning experience!

Contact
If you have any questions, feel free to reach out:

LinkedIn: https://www.linkedin.com/in/basem-fady-13966822b/
Email: basemfady2003@gmail.com
