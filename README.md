# ML Week 3 – Decision Tree Classifier

## Objective
To build a Decision Tree classification model that predicts whether a customer will purchase a product or service based on demographic and behavioral data.

## Dataset
- Bank Marketing Dataset
- Source: UCI Machine Learning Repository
- File used: bank.csv

## Problem Type
Binary Classification  
Target variable: `y`  
- yes → customer subscribed  
- no → customer did not subscribe  

## Approach
1. Loaded and explored the dataset
2. Encoded categorical variables using Label Encoding
3. Split the dataset into training and testing sets (80/20)
4. Trained a Decision Tree Classifier using scikit-learn
5. Evaluated the model using accuracy score and confusion matrix

## Algorithm Used
- Decision Tree Classifier

## Evaluation Metric
- Accuracy Score

## Result
The trained Decision Tree model achieved good accuracy in predicting customer purchase behavior on unseen test data.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## How to Run the Project

### Prerequisites
Ensure that Python 3.8 or above is installed on your system.

Install the required libraries using pip:

pip install pandas numpy scikit-learn matplotlib seaborn

### Steps to Run
1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Ensure the dataset file `bank.csv` is present in the same directory as the notebook.
4. Launch Jupyter Notebook:

jupyter notebook

5. Open the file `decision_tree_classifier.ipynb`.
6. Run the notebook cells sequentially from top to bottom.

### Output
- The model trains a Decision Tree classifier on the Bank Marketing dataset.
- The final output displays the accuracy score.
- A confusion matrix visualization is generated to evaluate model performance.

## Sample Output

## Sample Output

Accuracy Score:
0.88

Confusion Matrix:
![Confusion Matrix](confussion_matrix.png)

## Conclusion
This project demonstrates the use of a Decision Tree model for solving a real-world classification problem using structured customer data.
