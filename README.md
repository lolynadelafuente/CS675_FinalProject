# CS675 Titanic Dataset

## Dataset: Kaggle
Dataset : https://www.kaggle.com/competitions/titanic/data

## Purpose:
The purpose of our project is to predict with accuracy if a passenger aboard the titanic survives or not 
by utilizing machine learning algorithms with various predictive models for survival rate. 
By employing different classification algorithms, we aim to explore and
compare their performance in accurately identifying whether a passenger will survive or not
based on the provided attributes.

#### -Independent Variable (X) = All the columns except for the ‘Survived’ variable
#### -Dependent Variable(y) = ‘Survived’ (Predicting if a passenger survived (1='Y') or not (0='N'))

The analysis involved data preprocessing, exploratory analysis, feature engineering, conditional visualizations,
model building, evaluation, and comparison. Each step contributes to understanding the
dataset and evaluating the performance of various machine learning algorithms in
survival prediction.

### 1. Exploratory Analysis 
Conduct exploratory data analysis (EDA) to understand the distribution
and relationships between different features within the dataset. This will involve visualizations
and statistical summaries to gain insights into the data.

### 2. Data Pre-processing
- Handle missing values, if any, using techniques like imputation or deletion.
- Encode categorical variables if necessary.
- Scale numerical features to ensure uniformity in data range

### 3. Feature Engineering
- Create new features that might better represent underlying patterns in the data.

### 4. Conditional Visualization Points Based on Titanic Dataset
• Correlation Between Features:
 - Use a heatmap to visualize the correlation between different features in the dataset. (example)
 - Analyze which features are strongly correlated with each other and how they might impact survival.

• Distribution of Passengers Across Different Classes:
 - Plot all passenger classes (First, Second, and Third Class) in the same plane to visualize the distribution of 
passengers.
 - Analyze if there are any differences in survival rates or demographics across classes.

• Fare Distribution for Passengers in Different Classes:
 - Create a box plot or violin plot comparing the fare distribution for passengers in each class.
 - Explore if there are significant differences in fares between different passenger classes.

• Count of Non-Surviving Passengers Between Ages 20-30:
 - Count passengers between the ages of 20-30 who did not survive the disaster.
 - Visualize this count to understand the impact of age on survival rates among young passengers.

• Count of Passengers in Each Class:
 - Create a bar plot or count plot showing the count of passengers in each class.
 - Analyze the distribution of passengers across different classes to understand the demographics of the 
Titanic passengers.

### 5. Models for Analysis
Models chosen:
- Random Forest
- Decision Tree
- Logistic Regression
- K-Nearest Neighbors

  For each selected model:
- Train the model on the dataset.
- Evaluate its performance using appropriate metrics.
- Compare the performance of the models to determine their effectiveness in predicting passenger survival.
