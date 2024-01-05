# E-Commerce-data-Linear-Regression-

This project explores the relationship between various features of an e-commerce website and the yearly amount spent by customers. The main objective is to predict the yearly amount spent by customers based on different factors.

## Dataset

The dataset used in this project is named "Ecommerce Customers" and is loaded using the Pandas library.

## Dependencies

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Project Structure

- `Ecommerce Customers`: CSV file containing the dataset.
- `Ecommerce_Linear_Regression.ipynb`: Jupyter Notebook file with the code for data analysis and linear regression modeling.

## Analysis and Modeling

- Data is explored using various visualizations, including joint plots.
- Features such as 'Avg. Session Length,' 'Time on App,' 'Time on Website,' and 'Length of Membership' are used to predict 'Yearly Amount Spent.'
- The dataset is split into training and testing sets using `train_test_split`.
- Linear Regression model is implemented using scikit-learn's `LinearRegression`.
- The coefficients of the model are examined, and predictions are made on the test data.

## Results

A scatter plot is created to visualize the actual vs. predicted values on the test data.

```python
# Scatter plot
import matplotlib.pyplot as plt

plt.scatter(x=y_test, y=predicted_val)
plt.xlabel('Actual Yearly Amount Spent')
plt.ylabel('Predicted Yearly Amount Spent')
plt.title('Actual vs Predicted Yearly Amount Spent')
plt.savefig('scatter_plot.png')  # Save the plot as an image
plt.show()
![Scatter Plot](scatter_plot.png)


