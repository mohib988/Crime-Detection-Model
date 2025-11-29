# Anomalous Action Detection 


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
   - [Anomalous Action Detection Dataset](https://www.kaggle.com/datasets/sayantanroy10121999/anomalous-action-detection-dataset)

2. Download the dataset
use the script at define in cell 
```
import kagglehub

# Download latest version
path = kagglehub.dataset_download("sayantanroy10121999/anomalous-action-detection-dataset")

print("Path to dataset files:", path)

```
adjust the path according to the need

## Running the Project

Execute the notebook sections in order:

1. **Data Loading** - Loads and extracts the dataset
2. **Data Cleaning** - Handles missing values and outliers
3. **Feature Scaling** - Standardizes numerical features
4. **Train-Test Split** - Splits data for training and testing
5. **Model Creation** - Creating Detection Model
6. **Training** - Training Model
7. **Evaluation** - Evaluating the Modle

## Project Structure

```
.
├── .venv/                  # Virtual environment
├── requirements.txt        # Python dependencies
├── Crime-detectoin.ipynb          # Main Jupyter notebook
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
# Crime-Detection-Model
