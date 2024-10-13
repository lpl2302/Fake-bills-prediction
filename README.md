# Fake-bills-prediction
This project analyzes a dataset of banknotes to determine whether they are genuine or fake using various measurements.

**Dataset:** https://www.kaggle.com/datasets/alexandrepetit881234/fake-bills/data

## Introduction
This project analyzes a dataset of banknotes to determine whether they are genuine or fake using various measurements. The analysis is performed using Python libraries such as `pandas`, `numpy`, `matplotlib`, and `scikit-learn`. This is a pracice assignment for multiple linear regression, a method I learn from Machine learning with Python by IBM

### a) Requirements
The project requires the following Python libraries, which can be installed using the provided commands:

- pandas: For data manipulation and analysis.
- matplotlib: For creating visualizations.
- scikit-learn: For applying machine learning algorithms, specifically linear regression.
- numpy

### b) Dataset

The dataset (`fake_bills.csv`) contains the following columns:
- `is_genuine`: A boolean indicating if the bill is genuine (`True`) or fake (`False`).
- `diagonal`, `height_left`, `height_right`: Measurements of the bill's dimensions.
- `margin_low`, `margin_up`: Measurements of the bill's margins.
- `length`: The length of the bill.

## II. Usage

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:

  ```bash
  jupyter notebook main.ipynb
  ```

## III. Citations

- Dataset: https://www.kaggle.com/datasets/alexandrepetit881234/fake-bills/data
- Learning and practicing: https://www.coursera.org/learn/machine-learning-with-python
