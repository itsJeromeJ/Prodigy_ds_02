# Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

This project involved the following steps:

1. **Data Loading**: Loaded the Titanic dataset from a CSV file.
2. **Handling Missing Values**:
   - Dropped the `Cabin` column due to a high number of missing values.
   - Imputed missing `Age` values with the median age.
   - Filled missing `Embarked` values with the most frequent port.
3. **Feature Engineering**:
   - Extracted `Title` from the `Name` column.
   - Created a `Family_Size` feature by combining `SibSp` and `Parch`.
4. **Encoding Categorical Variables**:
   - Encoded the `Sex` column into numerical values.
   - Applied one-hot encoding to the `Embarked` column.
5. **Data Visualization and EDA**:
   - Explored survival rates, showing higher survival for females and first-class passengers.
   - Visualized the distribution of `Age` and `Fare` and their relationship with survival.
6. **Correlation Analysis**:
   - Generated a correlation matrix to explore relationships between features.
7. **Data Preparation for Modeling**:
   - Split the dataset into features (`X`) and the target variable (`y`) for modeling.

The dataset : https://www.kaggle.com/c/titanic/data
