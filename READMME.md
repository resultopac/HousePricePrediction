# House Price Prediction 🏠

A comprehensive machine learning project for predicting house prices using multiple regression algorithms. This project demonstrates end-to-end data science workflow including data cleaning, feature engineering, model training, and evaluation.

## 📋 Project Overview

This project implements and compares three different machine learning models for house price prediction:
- **Linear Regression** - Baseline model
- **Random Forest Regressor** - Ensemble method
- **XGBoost Regressor** - Gradient boosting algorithm

The models are evaluated using R² score and Mean Absolute Error (MAE) metrics to determine the best performing algorithm.

## 🗂️ Project Structure

```
house-price-prediction/
│
├── house_price_prediction.ipynb    # Main Jupyter notebook
├── data.csv                        # Dataset
├── requirements.txt                # Python dependencies
├── README.md                       # Project documentation
└── venv/                          # Virtual environment (not tracked)
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd HousePricePrediction
```

2. **Create a virtual environment**

**On Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

3. **Install required packages**
```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**
```bash
jupyter notebook house_price_prediction.ipynb
```

## 📊 Dataset

The dataset (`data.csv`) contains various features related to house properties. The preprocessing pipeline includes:
- Handling missing values
- Removing irrelevant features
- Feature engineering (creating new meaningful features)
- Data normalization/standardization

## 🔧 Project Workflow

### 1. Data Cleaning
- Identified and handled missing values
- Dropped unnecessary columns
- Addressed outliers and inconsistencies

### 2. Feature Engineering
- Created new features from existing ones
- Applied domain knowledge to enhance predictive power
- Performed feature selection

### 3. Model Training
Trained three different models:
- **Linear Regression**: Simple baseline model
- **Random Forest**: Ensemble learning with multiple decision trees
- **XGBoost**: Advanced gradient boosting algorithm

### 4. Model Evaluation
Models are evaluated using:
- **R² Score**: Measures how well the model explains variance in the data
- **Mean Absolute Error (MAE)**: Average absolute difference between predictions and actual values

## 📈 Results

| Model | R² Score | MAE |
|-------|----------|-----|
| Linear Regression | 0.88 | 52466.35 |
| Random Forest | 0.98 |  11842.14 |
| XGBoost | 0.99 | 10944.51 |

*Note: Run the notebook to see actual performance metrics*

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning algorithms
- **XGBoost**: Gradient boosting framework
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development environment

## 📝 Usage

1. Ensure your virtual environment is activated
2. Open the Jupyter notebook
3. Run cells sequentially from top to bottom
4. Observe the data cleaning process, feature engineering steps, and model comparisons
5. Experiment with different hyperparameters or add new features



## 📧 Contact

Name-Surname: Resül Topaç

E-Mail: resultopac04@gmail.com

Project Link: [https://github.com/resultopac/HousePricePrediction](https://github.com/resultopac/HousePricePrediction)

⭐ If you found this project helpful, please consider giving it a star!
