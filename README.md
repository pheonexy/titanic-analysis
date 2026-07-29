#🚢 Titanic Survival Prediction

##📖 Project Overview
This project analyzes the famous Titanic dataset to uncover survival patterns and build predictive models. The dataset contains passenger information such as age, gender, ticket class, and survival status.

##📊 Dataset
Source: Kaggle Titanic Dataset (kaggle.com in Bing)

Key columns:

Survived: Target variable (0 = No, 1 = Yes)

Pclass: Ticket class (1st, 2nd, 3rd)

Sex: Gender

Age: Passenger age

Fare: Ticket price

Embarked: Port of embarkation

##🛠 Methods
Data Cleaning: Handle missing values, drop duplicates.

Exploratory Analysis: Survival rates by gender, age, and class.

Visualization: Charts showing correlations and distributions.

Feature Engineering: Create new features (e.g., FamilySize, Title).

Modeling: Logistic Regression, Random Forest, etc.

##📈 Results
Women had a much higher survival rate than men.

1st class passengers survived more often than 3rd class.

Children had better chances than adults.

Example visualization:

Bar plot of survival by gender

Heatmap of feature correlations

##📂 Repository Structure

titanic-survival-analysis-prediction/
│
├── data/                # Raw dataset
├── notebooks/           # Jupyter notebooks for analysis
├── src/                 # Python scripts (preprocessing, modeling)
├── results/             # Charts, tables, and outputs
└── README.md            # Project overview
