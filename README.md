# Simple Linear Regression Model
Employe Salary Prediction using Simple Linear Regression model in Python Programming

## 1. Importing the Libraries
- NumPy
- Matplotlib
- Pandas
## 2. Importing the Dataset
Import the dataset, which is :
- x = iloc Years of Experience
- y = iloc Salary
## 3. Splitting the dataset into the Training Set and Test Set
- Scikit Learn, import LinearRegression model
- make method of LinearRegression model named regressor
- fit the x_train and y_train
## 4. Predicting The Test Result
- making new variabel called y_pred (contains predicting salaries)
- predict x_test using regressor.predict()
## 5. Visualising the Training set Result
- Scatter plotting x_train and y_train, color is red
- Plotting x_train and y_pred, color is blue
- Make title "Salary vs Experience"
- Make X Label "Years of Experience"
- Make Y Label "Salary"
- Show the Visualisation
## 6. Visualising the Test set Result
- Scatter plotting x_test and y_test, color is red
- Plotting x_train and y_pred, color is blue
- Make title "Salary vs Experience"
- Make X Label "Years of Experience"
- Make Y Label "Salary"
- Show the Visualisation
## 7. Making single Prediction (ex: the salary of an employee with 12 years of experience)
- Predict the 12 years of experience using regressor.predict()
- Put 2D array into double square bracket
## 8. Getting the Final Linear Regression Equation with Values of the Coefficients
- Find coefficients using regressor object
- Find intercept using regressor object
