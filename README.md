# Earthquake Prediction using Machine Learning

## Project Overview

This project focuses on predicting earthquake **magnitude** and **depth** using historical earthquake data. A machine learning model is built to analyze patterns based on location and time features.

The goal is to understand how different factors influence earthquake behavior and evaluate the performance of predictive models.

---

## Dataset

The dataset contains the following features:

* Date
* Time
* Latitude
* Longitude
* Depth
* Magnitude

Data preprocessing includes:

* Combining Date & Time into a timestamp
* Removing unnecessary columns
* Handling structured numerical inputs

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Model Used

* Random Forest Regressor
* GridSearchCV (for hyperparameter tuning)

---

## Project Workflow

1. Data Collection & Loading
2. Data Preprocessing
3. Feature Engineering (Timestamp conversion)
4. Train-Test Split
5. Model Training using Random Forest
6. Hyperparameter Optimization
7. Prediction & Evaluation
8. Data Visualization

---

## Results

* The model predicts earthquake **magnitude with good accuracy**
* **Depth prediction shows higher error** due to variability in geological conditions

### Evaluation Metrics:

* Mean Squared Error (MSE) used for performance evaluation

---

## Visualization

The project includes a scatter plot comparing:

* Actual values
* Predicted values

This helps visualize model performance.

---

---

## Key Insights

* Most earthquakes fall within lower magnitude ranges
* Depth varies significantly and is harder to predict
* Location (latitude & longitude) plays an important role
* Machine learning can identify patterns but has limitations with complex natural phenomena

---

## Future Improvements

* Use larger and more diverse datasets
* Try advanced models (XGBoost, Deep Learning)
* Improve feature engineering
* Add real-time prediction system

---



---

## Conclusion

This project demonstrates how machine learning can be applied to real-world problems like earthquake prediction. 
It highlights both the potential and limitations of predictive modeling in complex natural systems.

---
