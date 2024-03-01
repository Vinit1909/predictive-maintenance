
# Predictive Maintenance of Aircraft Engines

## Objective
The primary objective of this project is to predict the time to failure (TTF) of aircraft engines based on sensor data, operational settings, and derived features. This enables scheduling maintenance more effectively and reducing unplanned downtime.

## Data
The project utilizes sensor readings (`s1` to `s21`), operational settings (`setting1`, `setting2`, `setting3`), and time to failure (`ttf`) data. Additional transformed data featuring averages of sensor readings (`av1` to `av21`) is also employed.

## Exploratory Data Analysis (EDA)
The EDA involves visualizing sensor readings and operational settings, identifying correlations, and understanding engine behavior up to failure, informing feature selection for modeling.

## Machine Learning Algorithms
- **Random Forest**: Variations explored in feature sets.
- **Hyperparameter Tuning**: Grid search optimizes parameters like tree depth and criteria.
- **Evaluation**: Models are evaluated on ROC AUC, accuracy, precision, and recall.


