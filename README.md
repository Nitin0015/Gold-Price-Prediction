# **Gold Price Prediction**

This repository contains a Jupyter Notebook that demonstrates how to predict gold prices using machine learning techniques. The dataset used in this project includes historical data of gold prices along with other financial indicators.

---

## **Overview**

Gold is a valuable commodity, and its price is influenced by various factors such as stock market indices, oil prices, and currency exchange rates. This project aims to predict gold prices based on these financial indicators using a **Random Forest Regressor**. The model analyzes historical data to provide insights into future price trends.

The dataset includes features such as SPX (S&P 500 index), USO (crude oil prices), SLV (silver prices), and EUR/USD exchange rates, with the target variable (`GLD`) representing the gold price.

---

## **Dataset**

- **Source**: The dataset appears to be related to publicly available financial datasets.
- **Features**:
  - `Date`: Date of the record.
  - `SPX`: S&P 500 index value.
  - `GLD`: Gold ETF price (target variable).
  - `USO`: Crude oil ETF price.
  - `SLV`: Silver ETF price.
  - `EUR/USD`: Euro-to-US Dollar exchange rate.

---

## **Project Workflow**

1. **Data Loading**:
   - The dataset (`GoldPrice.csv`) is loaded into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics and visualizations are generated using Seaborn and Matplotlib to understand relationships between features and the target variable.
3. **Data Preprocessing**:
   - Missing values are handled if necessary.
   - Features are scaled for better model performance.
4. **Model Training**:
   - A Random Forest Regressor is used to predict gold prices.
   - The dataset is split into training and testing sets using `train_test_split`.
5. **Model Evaluation**:
   - Performance metrics such as Mean Absolute Error (MAE) and Mean Squared Error (MSE) are calculated to evaluate model accuracy.

---

## **Dependencies**

To run this project, you need the following Python libraries:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

You can install these dependencies using pip:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

---

## **How to Run**

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/GoldPricePrediction.git
   cd GoldPricePrediction
   ```

2. Ensure that the dataset file (`GoldPrice.csv`) is in the same directory as the notebook.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Gold-Price-Pred.ipynb
   ```

4. Run all cells in the notebook to execute the code.

---

## **Results**

The Random Forest Regressor provides predictions for gold prices based on financial indicators. Evaluation metrics such as MAE and MSE indicate how well the model performs in predicting prices. Further improvements can be made by experimenting with other regression models or feature engineering techniques.

---

## **Acknowledgments**

- The dataset was sourced from publicly available financial datasets or repositories.
- Special thanks to Scikit-learn for providing robust machine learning tools.

---
