# Task-6---Data-Science-example.

Project Title

This project uses the 'pandas' and 'numpy' libraries to load and manipulate data, and 'scikit-learn' library to train and evaluate a linear regression model.
The goal of this project is to demonstrate the use of these libraries in a machine learning project.


Libraries

This project requires the following libraries to be installed:
1. 'pandas' (version 1.0.0 or later)
2. 'numpy' (version 1.18.0 or later)
2. 'scikit-learn' (version 0.22.0 or later)


Dataset

This project uses the California Housing dataset, which can be loaded using the 'fetch_california_housing' function from 'scikit-learn' . The dataset contains information about housing prices in various neighborhoods in California, based on various features such as location, population, and median income.



Usage

To use this project, simply run the 'linear_regression.py' script.

The script first loads the California Housing dataset using 'fetch_california_housing' and converts it to a pandas DataFrame. It then splits the data into training and testing sets using 'train_test_split' function from 'scikit-learn'. The model is trained using 'LinearRegression' from 'scikit-learn' and evaluated using mean squared error from 'mean_squared_error' function from 'scikit-learn' .

The output of the script is the mean squared error of the model on the test set.

Mean Squared Error: 0.555891598695244



Conclusion

This project demonstrates the use of 'pandas', 'numpy', and 'scikit-learn' libraries in a machine learning project. The California Housing dataset was used to train and evaluate a linear regression model, and the mean squared error was calculated as a measure of performance. This project can serve as a starting point for more complex machine learning projects using these libraries.



Screen Shot:
![image](https://user-images.githubusercontent.com/59089400/228528982-82c4de12-55c8-4b68-9afc-f313fdfbafb5.png)
