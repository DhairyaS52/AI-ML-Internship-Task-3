# Task 3 - Linear Regression

## AI & ML Internship

In this task, I worked with the `Housing.csv` dataset and used Linear Regression to predict house prices. I implemented both Simple Linear Regression and Multiple Linear Regression and compared their performance using different evaluation metrics.

## Objective

The main aim of this task was to understand how Linear Regression works and how it can be used for predicting continuous values.

The task includes:

* Simple Linear Regression
* Multiple Linear Regression
* Data preprocessing
* Train-test split
* Model evaluation
* Regression visualization
* Understanding model coefficients

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* GitHub

## Dataset

The dataset used for this task is `Housing.csv`.

It contains different features related to houses, which are used to predict the house `price`.

The target variable is:

```text
price
```

The dataset contains both numerical and categorical columns. The categorical columns were converted into numerical values using one-hot encoding before training the multiple regression model.

## Steps Performed

The following steps were followed in the notebook:

1. Loaded the housing dataset.
2. Checked the columns, data types and missing values.
3. Checked and removed duplicate rows if present.
4. Handled missing values.
5. Separated the input features and target variable.
6. Converted categorical features into numerical features.
7. Split the data into training and testing sets.
8. Built a Simple Linear Regression model.
9. Built a Multiple Linear Regression model.
10. Evaluated both models.
11. Created graphs to visualize the results.
12. Checked and displayed the model coefficients.

## Simple Linear Regression

For Simple Linear Regression, I used `area` as the input feature and `price` as the target.

```text
area → price
```

The data was split into 80% training data and 20% testing data.

A regression line was also plotted to see the relationship between house area and price.

## Multiple Linear Regression

For Multiple Linear Regression, I used the available features in the dataset after preprocessing the categorical columns.

The model was created using Scikit-learn's `LinearRegression` class.

The model was then used to predict prices for the test data.

## Model Evaluation

The following metrics were used to evaluate the models:

### MAE

Mean Absolute Error shows the average absolute difference between the actual and predicted prices.

A lower MAE means the predictions are closer to the actual values.

### MSE

Mean Squared Error calculates the average of the squared prediction errors. It gives more importance to larger errors.

A lower MSE is better.

### R² Score

R² shows how well the model explains the variation in house prices.

A higher R² generally indicates a better fit.

## Visualizations

The notebook includes:

* Area vs Price with the regression line
* Actual Price vs Predicted Price
* A graph showing the regression coefficients

These graphs make it easier to understand the model results.

## Results

The notebook calculates the MAE, MSE and R² score for both models.

The final comparison is shown in the notebook after running all the cells.

| Model                      |          MAE |          MSE |           R² |
| -------------------------- | -----------: | -----------: | -----------: |
| Simple Linear Regression   | See notebook | See notebook | See notebook |
| Multiple Linear Regression | See notebook | See notebook | See notebook |

## Repository Files

```text
Task-3-Linear-Regression/
│
├── Housing.csv
├── Task_3_Linear_Regression_Housing.ipynb
└── README.md
```

## How to Run

The project was created and tested using Google Colab.

1. Open `Task_3_Linear_Regression_Housing.ipynb` in Google Colab.
2. Run the cells in order.
3. Upload `Housing.csv` when asked.
4. Run all the cells.
5. Check the model results and graphs.

The required Python libraries are:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## What I Learned

From this task, I learned:

* How Linear Regression is used for prediction.
* The difference between Simple and Multiple Linear Regression.
* How to split data into training and testing sets.
* How to evaluate regression models using MAE, MSE and R².
* How to visualize regression results.
* How to interpret regression coefficients.

## Author

**Dhairya Shah**

AI & ML Internship - Task 3
