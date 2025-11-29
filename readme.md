# Car Price Prediction - Linear Regression Project

This project implements various linear regression techniques including OLS, SVD-based solutions, Gradient Descent, and PCA for dimensionality reduction to predict vehicle prices.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset Setup](#dataset-setup)
- [Running the Project](#running-the-project)
- [Project Structure](#project-structure)

## Prerequisites

- Python 3.12 or higher
- pip (Python package installer)
- Jupyter Notebook

## Installation

### 1. Create and Activate Virtual Environment

**Linux / Mac:**
```bash
python -m venv .venv
source .venv/bin/activate
```

**Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

## Dataset Setup

### Download the Dataset

1. Visit the Kaggle dataset page:
   - [Vehicle Price Cleaning Analysis & Prediction](https://www.kaggle.com/code/abdohassan01/vehicle-price-cleaning-analysis-prediction-sm)

2. Download the dataset as a ZIP file

3. Locate the downloaded ZIP file on your computer

### Configure Dataset Path

1. Open the Jupyter Notebook
2. Navigate to **Cell 3**
3. Update the `path` variable with your ZIP file location:

```python
path = "/path/to/your/downloaded/dataset.zip"
```

The code will automatically:
- Extract the ZIP file
- Locate `Car details v3.csv`
- Load it into a pandas DataFrame

## Running the Project

Execute the notebook sections in order:

1. **Data Loading** - Loads and extracts the dataset
2. **Data Cleaning** - Handles missing values and outliers
3. **Feature Scaling** - Standardizes numerical features
4. **Train-Test Split** - Splits data for training and testing
5. **OLS Regression** - Ordinary Least Squares implementation
6. **SVD-Based Solution** - Regression using Singular Value Decomposition
7. **Gradient Descent** - Iterative optimization approach
8. **PCA Analysis** - Principal Component Analysis for dimensionality reduction


## Project Structure

```
.
├── .venv/                  # Virtual environment
├── requirements.txt        # Python dependencies
├── Car-dekho-prediction.ipynb          # Main Jupyter notebook
├── README.md              
└── archive.zip                  # Dataset  (auto-created)
```

## Troubleshooting

### Issue: Module not found
**Solution**: Ensure all dependencies are installed
```bash
pip install -r requirements.txt
```

### Issue: Dataset not loading
**Solution**: Verify the path variable points to the correct ZIP file location

### Issue: Virtual environment not activating
**Solution**: Check Python installation and ensure `.venv` folder exists

## Dependencies

- numpy
- pandas
- scikit-learn
- matplotlib
- jupyter
- plolty
- statsmodels
## Acknowledgments

Dataset source: [Kaggle - Vehicle Price Analysis](https://www.kaggle.com/code/abdohassan01/vehicle-price-cleaning-analysis-prediction-sm)

---

**Note**: Make sure to run cells sequentially from top to bottom for proper execution.# Crime-Detection-Model
