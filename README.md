# Task2_ML-AL_EDA
📌 Project Overview: I have completed my Second task of AI & ML INTERNSHIP of Elevate Lab.In this project focuses on 
 analyzing the Titanic dataset to understand Exploratory Data Analysis (EDA) and the characteristics that influenced survival 
 during the disaster. 
 The goal is to understand data using statistics and visualizations.Generate summary statistics ,Create histograms and 
 boxplots for numeric features,Use pairplot/correlation matrix,patterns, trends, or anomalies and feature-level inferences.
 

📊 Technologies Used  1.Pandas 2.NumPy 3.Matplotlib 4.Seaborn 5.Jupyter Notebook

📁 Dataset The dataset used is the famous Titanic passenger dataset from Kaggle, containing features like: 1.Name, Age, Sex, Pclass (Passenger Class) 2.Fare, Cabin, Embarked 3.Survived (Target column)

🛠️ Data Cleaning & Preprocessing Removed the Cabin column due to many missing values.

🛠️Filled missing values in: 1.Age column with the mean age 2.Embarked column with the most frequent value ('S') 3.Dropped any rows with remaining missing values.

📈 Exploratory Data Analysis (EDA) Distribution plots of Age, Fare, and survival status.

🛠️Comparison of survival based on: Gender Passenger class (Pclass) Embarkation port Used updated histplot() instead of deprecated distplot() for KDE visualizations.

🔍 Key Insights Females had a higher chance of survival compared to males. Higher class passengers (Pclass 1) had better survival rates. Younger passengers also showed slightly better survival chances..

🔍 feature-level inferences:
Pclass (Passenger Class): Lower Pclass (1st class) passengers had higher survival rates. The fare distribution shows that 1st class passengers paid more and were treated with priority.

Age: Most passengers were aged 20–40. Children (0–12) had better survival rates — priority might’ve been given during evacuation. Seniors (60+) had low survival, possibly due to mobility or health.

Fare: Highly skewed — a few passengers paid very high fares (possibly rich or VIPs). Higher fare → Higher survival rate (likely tied to better class and facilities).

SibSp & Parch: Most people had no siblings/spouses or parents/children aboard. Small families (1–2 members) had slightly better survival. Large families showed lower survival — possibly due to difficulty in managing everyone.

Survived: Only about 38% survived, as seen in the summary stats. Survival is influenced most by Pclass, Age, and indirectly by Fare.

