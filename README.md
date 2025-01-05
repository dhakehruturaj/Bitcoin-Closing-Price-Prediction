# Bitcoin Price Prediction using Machine Learning

## Overview
This project focuses on predicting the closing price of Bitcoin using machine learning techniques. The prediction is based on historical data, including features such as the opening price, day high, day low, and the date-time. This repository implements various linear regression-based machine learning models to predict Bitcoin prices and evaluate their performance.

---

## Table of Contents
1. [Dataset](#dataset)
2. [Algorithms Used](#algorithms-used)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Future Work](#future-work)
8. [Contributing](#contributing)
9. [License](#license)

---

## Dataset
The dataset used in this project contains historical Bitcoin price data. Key features include:
- **Opening Price**: The price at which Bitcoin started trading for the day.
- **Day High**: The highest price of Bitcoin during the day.
- **Day Low**: The lowest price of Bitcoin during the day.
- **Date-Time**: Reference to the specific day.
- **Closing Price** (Target): The price at which Bitcoin ended trading for the day.

You can find or preprocess the data using publicly available financial market datasets.

---

## Algorithms Used
The following machine learning algorithms were used for prediction:
1. **Linear Regression**
2. **Support Vector Regression (SVR)**
3. **Bayesian Ridge Regression**
4. **Lasso Lars Regression**

---

## Project Structure
```
bitcoin-price-prediction/
├── data/                # Contains the dataset
├── notebooks/           # Jupyter notebooks for EDA and model training
├── models/              # Saved models (if applicable)
├── results/             # Evaluation metrics and visualizations
├── src/                 # Source code for data preprocessing and modeling
│   ├── preprocess.py    # Data cleaning and feature engineering scripts
│   ├── train.py         # Model training scripts
│   └── evaluate.py      # Scripts to evaluate model performance
├── README.md            # Project documentation
└── requirements.txt     # Required Python packages
```

---

## Installation
### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook (optional)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bitcoin-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bitcoin-price-prediction
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage
1. **Data Preprocessing**:
   - Ensure the dataset is placed in the `data/` directory.
   - Run the preprocessing script to clean and prepare the data:
     ```bash
     python src/preprocess.py
     ```

2. **Training Models**:
   - Train the models using the provided script:
     ```bash
     python src/train.py
     ```

3. **Evaluation**:
   - Evaluate the performance of the trained models:
     ```bash
     python src/evaluate.py
     ```

4. **Visualization**:
   - Explore the results and visualizations in the `results/` directory or view them in the Jupyter notebooks in `notebooks/`.

---

## Results
The models were evaluated based on metrics such as:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

| Model                 | MAE   | MSE   | RMSE  | R²   |
|-----------------------|-------|-------|-------|-------|
| Linear Regression     | XX.XX | XX.XX | XX.XX | XX.XX |
| Support Vector (SVR)  | XX.XX | XX.XX | XX.XX | XX.XX |
| Bayesian Ridge        | XX.XX | XX.XX | XX.XX | XX.XX |
| Lasso Lars            | XX.XX | XX.XX | XX.XX | XX.XX |

---

## Future Work
1. Incorporate additional features, such as trading volume and external market trends.
2. Experiment with non-linear models (e.g., Random Forest, XGBoost, Neural Networks).
3. Integrate live price prediction using APIs.
4. Deploy the model using Flask/Django for a web-based interface.

---

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or create a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Acknowledgments
Special thanks to the creators of the datasets and libraries used in this project. The models were built using Python's robust data science and machine learning libraries, including:
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

