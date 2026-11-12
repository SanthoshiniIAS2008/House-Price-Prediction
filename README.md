# House Price Prediction using Machine Learning

## Project Overview
This project uses Machine Learning to predict house prices based on different property features. A Linear Regression model is trained using the Kaggle House Prices dataset.

## Objective
To build a machine learning model that predicts house prices and evaluates its performance using regression metrics.

## Dataset
- **Source:** Kaggle – House Prices: Advanced Regression Techniques
- **Training records:** 1,460 houses
- **Features:** 79 input features
- **Target column:** SalePrice

[Download the dataset from Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Workflow
1. Load the housing dataset.
2. Explore the dataset and understand its features.
3. Handle missing values.
4. Separate input features and target variable.
5. Split the data into training and testing sets.
6. Perform data preprocessing.
7. Train a Linear Regression model.
8. Predict house prices.
9. Evaluate model performance.
10. Visualize actual vs predicted prices.

## Model Used
**Linear Regression**

## Model Evaluation Results

| Metric | Result |
|---|---:|
| Mean Squared Error (MSE) | 941,500,506.81 |
| Root Mean Squared Error (RMSE) | 30,683.88 |
| R² Score | 0.8773 (87.73%) |

The model explains approximately 87.73% of the variation in house prices on the test dataset.

## Project Visualization
The project includes:
- House Price Distribution
- Actual vs Predicted House Prices

## How to Run
1. Download or clone this repository.
2. Open the `.ipynb` notebook using Google Colab or Jupyter Notebook.
3. Download the Kaggle `train.csv` dataset.
4. Upload `train.csv` to your Colab session.
5. Run the notebook cells in order.

## Project Structure
```text
House-Price-Prediction/
│
├── Week2_House_Price_Prediction.ipynb
└── README.md
```

## Conclusion
A Linear Regression model was successfully developed to predict house prices. The model achieved an R² score of 87.73%, demonstrating its ability to explain a substantial portion of the variation in house prices.

---
**Machine Learning Project | Python | Linear Regression**
