# Ml-assignment-
README: Linear Regression and Dataset Exploration
Program 1: Dataset Exploration and Data Splitting
Objective: This program explores the Iris dataset and splits it into training and testing sets.

Description:

Dataset Loading: The program loads the Iris dataset, which contains measurements of iris flowers and their species labels. It uses the load_iris function from the sklearn.datasets module.

Exploration: It displays the first five rows of the dataset to give an initial view of the data. It also provides the shape of the dataset (i.e., the number of rows and columns) and summary statistics for each feature, including mean, standard deviation, minimum, and maximum values.

Data Splitting: The dataset is divided into training and testing subsets. The training set is used to build the model, while the testing set evaluates its performance. An 80-20 split is used, meaning 80% of the data is allocated to training, and 20% to testing.

Program 2: Linear Regression with User Input
Objective: This program implements a linear regression model to predict salaries based on years of experience and allows user input to make predictions.

Description:

Data Preparation: The program uses a synthetic dataset where the features are YearsExperience, and the target variable is Salary. This dataset is used to train the linear regression model.

Model Training: A linear regression model is trained using the training subset of the data. The model learns the relationship between years of experience and salary.

Model Evaluation: After training, the model’s performance is evaluated using Mean Squared Error (MSE), which measures the average squared difference between predicted and actual values.

User Input: The program prompts the user to input years of experience. It then uses the trained model to predict and display the corresponding salary based on the user-provided experience

