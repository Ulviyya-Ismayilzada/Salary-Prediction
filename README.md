# Salary-Prediction
In this project we are focused on predicting the salaries of data professionals by diving into the world of regression problem, analyzing data, feature engineering, modeling and developing model for getting well-performed model.

EDA
Within Exploratory Data Analysis stage  we unveiled valuable insights about data professionals' salaries. For this we involved data visualization, summary,statistics, and identifying patterns in the data .
Our dataset contains 2639 rows × 13 columns. Data types of data are object, float and integers. Totally in the dataset there was 161 duplicated data and removed them. Additionally, there was 12 missing value. Due to our target is to give  salary prediction for data professionals checking value counts of designation can be good insight.
Age distribution demonstrate that main age group of data professionals is over 20 and below 30.Additionally, by visualize correlation between features such as salary and designation, experience, salary and sex we can find that experience plays crucial role in salary.

Feature engineering
In our dataset, there is a feature as ‘date of joining the company’. However, this feature alone cannot provide special insights. By using this feature, we can calculate the experience in the company and add this value to the result of past work experience. This will give us the total experience of the workers, which will be a strong feature for predicting salary. Furthermore, some features, such as ID, are deleted at this stage.

Data Preprocessing
In this stage we prepare  our data for model training. This includes handling missing values, encoding categorical variables, and scaling or normalizing features as needed.
Firstly, due to amount of our missing values is lower comparison with shape of dataset we can remove them without handling. Additionally, for this stage we have used pipeline for handling scaling and encoding.  

Conclusion
As we know, we needed to predict continuous data, which means we would need regression models. Firstly, we used a train-test split for dividing the dataset. Additionally, we experimented with different algorithms such as Linear Regression, Decision Trees, Random Forests, and Gradient Boosting. To avoid overfitting, cross-validation was used for all models. Furthermore, GridSearchCV was implemented for hyperparameter tuning to find the best parameters.
