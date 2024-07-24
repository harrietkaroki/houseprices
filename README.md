# House Prices Prediction Project

## Overview
This project aims to predict house prices using a Random Forest model. The dataset used is the House Prices - Advanced Regression Techniques dataset from Kaggle.

## Data Preprocessing
- Filled missing numerical values with the mean.
- Filled missing categorical values with "Unknown".
- Applied one-hot encoding to categorical features.

## Model Training
- Split the dataset into training and validation sets.
- Used GridSearchCV for hyperparameter tuning.
- Evaluated the model using Mean Squared Error (MSE) and R-squared (R2).

## Results
- Best model performance on validation set:
  - Mean Squared Error (MSE): 842535374.3887578
  - R-squared (R2): 0.890156513343683

## Files
- `final_random_forest_model.joblib`: Trained Random Forest model.
- `house_prices_notebook.ipynb`: Jupyter notebook with all steps and code.
- `data/`: Directory containing the dataset (if permissible).

## Usage
To use the trained model, load it using joblib:
```python
import joblib


3. **Save the file** as `README.md` in the root directory of your project.

4. **Add the README.md file to your Git repository**:

```bash
git add README.md


model = joblib.load('final_random_forest_model.joblib')
