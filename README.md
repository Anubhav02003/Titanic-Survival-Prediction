#  Titanic Survival Prediction Using Machine Learning

##  Importing Libraries

In this project, I started by importing key Python libraries that support **data handling, numerical analysis**, and **visualization**:

- **pandas** – For reading and manipulating structured data like tables.
- **numpy** – Used for efficient numerical computations and working with arrays.
- **seaborn** – Built on matplotlib, it makes creating informative statistical plots easier.
- **matplotlib.pyplot** – A core plotting library to help visualize trends and patterns in the data.

##  Loading the Data

Using **pandas**, I loaded the Titanic dataset from CSV files, separating it into **training** and **test** sets. These datasets include vital details about passengers that form the basis for predicting survival outcomes.

##  Exploratory Data Analysis (EDA)

I performed **EDA** to understand the data better:

- Analyzed distributions of important numerical features like **Age, SibSp (siblings/spouses), Parch (parents/children), and Fare**.
- Explored potential **relationships and correlations** between features to identify patterns that might influence survival chances.

## Data Cleaning

Data cleaning played a crucial role. I:

- Handled **missing values** using appropriate imputation strategies.
- **Removed columns** like *PassengerId, Name, Ticket,* and *Cabin* as they added little value to prediction.
- Created or transformed features using **feature engineering** to improve model performance.

##  Model Building and Testing

I trained and tested multiple **machine learning models** to find the most accurate one for survival prediction. These included:

- **Decision Tree**
- **RandomForest**
- **XGBoost**
- **LGBM**
- **ExtraTrees**
- **Logistic Regression**

The best model achieved a predictive accuracy of **73.8%**, reflecting strong performance on the task.

##  Test Prediction and Submission

Using the best model, I made predictions on the **test dataset** and prepared a **submission file** for final evaluation. This step tested how well the model generalizes to new, unseen data.

## Conclusion

With a final accuracy of **73.8%**, the model effectively predicts which passengers survived the Titanic disaster. This project highlights how **machine learning** can be applied to real-world historical data and helps uncover the key factors that influenced survival.
