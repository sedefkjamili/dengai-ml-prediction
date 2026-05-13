# 🦟 DengAI
Machine learning project for predicting dengue fever outbreaks using climate and environmental data.

DengAI is a machine learning project focused on predicting weekly dengue fever outbreaks using climate and environmental data. The project compares traditional regression techniques with ensemble learning methods to forecast dengue case counts for two tropical cities: San Juan (Puerto Rico) and Iquitos (Peru).

## 🚀 Overview

Dengue fever is a mosquito-borne disease strongly influenced by environmental and climatic conditions such as temperature, humidity, precipitation, and vegetation. Early prediction of outbreaks can help public health organizations allocate resources more effectively and reduce the spread of disease.

This project uses machine learning models trained on historical climate and epidemiological data from the DrivenData DengAI competition dataset.

## 🔍 Features

### 📊 Data Preprocessing
- Missing value imputation using city-specific averages
- Time-aware train/validation split
- Separate modeling for each city
- Seasonal feature handling using `weekofyear`

### 🔬 Feature Engineering
- Climate and environmental indicators
- Vegetation indices (NDVI)
- Temperature and humidity variables
- Time-series aware structure

### 🧠 Machine Learning Models
- Polynomial Regression (Baseline)
- Gradient Boosting Regression
- Time-series forecasting evaluation

### 📈 Performance Evaluation
- Mean Absolute Error (MAE)
- Comparison between baseline and ensemble models
- Forecasting horizon analysis
- Feature importance visualization

## 🗂️ Repository Structure

```text
DengAI/
├── data/                  # Prediction outputs and datasets
├── notebooks/             # Jupyter notebooks for training and analysis
├── reports/               # Presentation slides and project report
├── images/                # Figures, plots, and visualizations
├── src/                   # Source code for preprocessing and modeling
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## 🧪 Technologies & Libraries

- Python 3.10+
- scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/DengAI.git

cd DengAI
```

##  Install dependencies:

```bash
pip install -r requirements.txt
🧠 Model Training & Evaluation
```

Run the notebook:

jupyter notebook

or execute training scripts inside /src.

## 📊 Results
Gradient Boosting Regression significantly outperformed Polynomial Regression.
Polynomial models showed overfitting at higher degrees.
Best performance was achieved using short-term forecasting horizons.
Environmental variables such as temperature and vegetation indices were among the most influential features.

## 📚 Dataset Source
DrivenData – DengAI: Predicting Disease Spread
Climate and environmental datasets for:
San Juan, Puerto Rico
Iquitos, Peru

## 👩‍💻 Authors
Rabia Şevval Aydın
Sedef Kjamili

Istanbul Technical University
BLG527E – Machine Learning Term Project

## 📄 License

This project is for academic and educational purposes.
