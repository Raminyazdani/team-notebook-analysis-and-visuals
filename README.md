# California Housing Regression Analysis

**Comprehensive linear regression analysis and model comparison on California Housing dataset**

## Overview

This project demonstrates practical application of regression analysis techniques for housing price prediction. It provides a systematic approach to supervised learning, from exploratory data analysis through model comparison and evaluation. The analysis compares linear regression (single and multiple features) with K-Nearest Neighbors regression on the California Housing dataset.

## Tech Stack

- **Python 3.x** - Core programming language
- **Jupyter Notebook** - Interactive development environment
- **scikit-learn** - Machine learning library (datasets, models, metrics)
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **statsmodels** - Statistical modeling and tests

## Repository Structure

```
california-housing-regression-analysis/
├── california_housing_regression_analysis.ipynb    # Main analysis notebook
├── requirements.txt                                 # Python dependencies
├── .gitignore                                      # Git ignore patterns
└── README.md                                       # This file
```

## Setup & Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Install Dependencies

Using the requirements file (recommended):
```bash
pip install -r requirements.txt
```

Or install packages individually:
```bash
pip install numpy matplotlib jupyter pandas seaborn scikit-learn statsmodels
```

## How to Run

1. Clone the repository and navigate to the project directory:
```bash
cd california-housing-regression-analysis
```

2. Install dependencies (if not already installed):
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook california_housing_regression_analysis.ipynb
```

Or use JupyterLab:
```bash
jupyter lab california_housing_regression_analysis.ipynb
```

4. Execute cells sequentially from top to bottom using `Shift + Enter`

## Data & Analysis

### Dataset
The project uses scikit-learn's built-in **California Housing dataset**:
- **20,640 samples** from the 1990 California census
- **8 numeric features**: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude
- **Target variable**: Median house value (MedHouseVal)
- **No external files required** - dataset is loaded programmatically via `fetch_california_housing()`

### Analysis Pipeline
1. **Exploratory Data Analysis**: Statistical summaries, missing value checks, feature distributions
2. **Correlation Analysis**: Feature correlations and multicollinearity detection
3. **Single Feature Regression**: Baseline model using AveRooms as predictor
4. **Multiple Feature Regression**: Model with 6 selected features
5. **KNN Regression**: Comparison with K-Nearest Neighbors approach
6. **Model Evaluation**: RSS, MSE, and R² metrics for all models
7. **Visualization**: Residual plots and model comparison

### Outputs
All outputs are displayed inline within the notebook:
- Statistical summaries and data exploration tables
- Correlation matrices and scatter plot matrices
- Model performance metrics (RSS, MSE, R²)
- Residual vs. fitted value plots
- Model comparison visualizations

## Key Features

- **Comprehensive Metrics**: Implementation of RSS, MSE, and R² from scratch
- **Model Comparison**: Side-by-side evaluation of linear vs. KNN regression
- **Feature Analysis**: Correlation analysis and feature selection strategies
- **Hyperparameter Exploration**: Investigation of K values for KNN regression
- **Professional Visualizations**: Clear plots for residual analysis and model performance
- **Self-Contained**: No external data files required - uses sklearn's built-in dataset
- **Reproducible**: Fixed random seeds and clear execution order

## Troubleshooting

### Common Issues

**Import Errors:**
```bash
ModuleNotFoundError: No module named 'sklearn'
```
Solution: Install scikit-learn: `pip install scikit-learn`

**Jupyter Not Found:**
```bash
jupyter: command not found
```
Solution: Install Jupyter: `pip install jupyter`

**Version Compatibility:**
- Ensure Python 3.7+ is installed: `python --version`
- Update pip if needed: `pip install --upgrade pip`
- If using Conda: `conda install jupyter scikit-learn numpy pandas matplotlib seaborn`

**Notebook Kernel Issues:**
- If kernel doesn't start, try: `jupyter notebook --no-browser`
- Restart kernel: Kernel → Restart in Jupyter menu
- Clear outputs and restart: Kernel → Restart & Clear Output

## Project Authors

- Ramin Yazdani
- Zein Younes

## License

This project is available for educational and portfolio purposes.
