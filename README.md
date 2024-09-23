# California Housing Regression Analysis

**Comprehensive linear regression analysis and model comparison on California Housing dataset**

## Overview

This project demonstrates practical application of regression analysis techniques for housing price prediction. It provides a systematic approach to supervised learning, from exploratory data analysis through model comparison and evaluation.

## Tech Stack

- **Python 3.x** - Core programming language
- **Jupyter Notebook** - Interactive development environment
- **scikit-learn** - Machine learning library (datasets, models, metrics)
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **statsmodels** - Statistical modeling and tests

## Data & Analysis

### Dataset
The project uses scikit-learn's built-in **California Housing dataset**:
- **20,640 samples** from the 1990 California census
- **8 numeric features**: MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude
- **Target variable**: Median house value (MedHouseVal)
- **No external files required** - dataset is loaded programmatically

### Analysis Pipeline
1. Exploratory Data Analysis
2. Correlation Analysis
3. Single Feature Regression
4. Multiple Feature Regression
5. KNN Regression
6. Model Evaluation
7. Visualization

## Setup & Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Install Dependencies

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone the repository
2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook california_housing_regression_analysis.ipynb
```

4. Execute cells sequentially from top to bottom using `Shift + Enter`
