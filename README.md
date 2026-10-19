# AI-Based Customer Spending Prediction

## Project Overview
This project focuses on predicting customer spending categories using machine learning. It was developed as part of my AI/ML internship project at Veda Technology.

The project uses customer details such as age, gender, and annual income to classify customers into Low, Medium, and High spending categories.

## Objectives
- Understand and analyse customer data.
- Perform data cleaning and exploratory data analysis.
- Visualize customer information using graphs.
- Build and compare machine learning classification models.
- Predict spending categories for new customer records.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Created and inspected a sample customer dataset.
2. Checked for missing values and duplicate records.
3. Created spending categories using spending scores.
4. Performed exploratory data analysis using five visualizations.
5. Prepared the input features and target variable.
6. Split the dataset into training and testing sets.
7. Trained Logistic Regression and Decision Tree models.
8. Compared models using accuracy, precision, recall, and F1-score.
9. Evaluated the selected model using a classification report and confusion matrix.
10. Tested the model with new customer records.

## Machine Learning Models
### Logistic Regression
Used as a baseline classification model to predict customer spending categories.

### Decision Tree Classifier
Used to learn patterns in customer information and classify spending categories.

## Dataset
This version of the project uses a synthetically generated dataset containing 200 sample customer records.

The dataset includes:
- Customer ID
- Gender
- Age
- Annual Income
- Spending Score
- Spending Category

**Note:** The data is synthetic and does not represent actual mall customers. The spending categories are defined for this project using the spending score.

## Evaluation Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The actual evaluation results are available in the executed Jupyter Notebook.

## How to Run the Project
1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   `pip install pandas numpy matplotlib seaborn scikit-learn`

3. Open the notebook in Jupyter Notebook.
4. Run the code cells.
5. Review the visualizations, model comparison, and sample predictions.

## Conclusion
This project helped me understand the basic machine learning workflow, including data preparation, visualization, model training, evaluation, and prediction.

It demonstrates how classification models can be used to explore customer spending patterns. Since the current dataset is synthetic, the results are for learning and demonstration purposes.

## Future Improvements
- Use a real customer dataset.
- Improve model performance through feature engineering and hyperparameter tuning.
- Test the models on a larger and more representative dataset.
- Explore additional classification algorithms.
