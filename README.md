# Yes Bank Stock Price Prediction Using Machine Learning

## Description

Yes Bank is a banking company founded in 2004, offering a wide range of differentiated products for its corporate and retail customers through retail banking and asset management services. Being a publicly traded company, Yes Bank provides an opportunity for anyone to invest and become a shareholder.

However, the valuation of the company is significantly influenced by public perception, as share prices are often impacted by market sentiment and speculation. This project focuses on predicting Yes Bank’s stock price using historical data and machine learning models.

We have used a dataset containing five key features related to the stock market and trained regression-based machine learning models to predict the closing price of Yes Bank shares.

---

## Features

- Utilized historical Yes Bank stock data
- Preprocessed data with key features for prediction
- Implemented multiple regression models
- Evaluated model performance using appropriate metrics
- Visualized predictions vs actual values

---

## Dataset

The dataset includes the following features:
- Open Price
- High Price
- Low Price
- Last Traded Price
- Volume

The target variable is the **Close Price**.

---

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor
- Gradient Boosting Regressor

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/yes-bank-stock-prediction.git
cd yes-bank-stock-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the notebook or script to train and test the models:

```bash
python train_model.py
```

Or open the Jupyter notebook:

```bash
jupyter notebook YesBank_Prediction.ipynb
```

---

## Results

- The models were evaluated using metrics such as MAE, MSE, and R² score.
- Random Forest and Gradient Boosting showed the most accurate results.
- Visualizations demonstrate the effectiveness of predictions vs actual stock prices.

---

## License

This project is open-source and available under the MIT License.

---

## Author

Abhishek Parihar