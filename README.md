# Space Y Rocket Landing Success Prediction

## Overview

This project aims to develop a robust predictive model to forecast the landing success of rockets, which is a crucial part of a cost-optimization strategy for Space Y, a new competitor to SpaceX. By accurately predicting landing outcomes, Space Y can minimize costs associated with failed landings and enhance the efficiency and reliability of their launch operations.

## Exploratory Data Analysis (EDA)

### Key Insights
- **Payload Mass and Success**:
  - Higher payload masses (4000 kg to 7000 kg) are generally associated with higher success rates.
- **Launch Site Performance**:
  - CCAFS SLC-40 demonstrated the highest success rate, making it a potential benchmark for operational efficiency.


## Model Development

### Model Comparison
Four machine learning algorithms were evaluated:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**

### Confusion Matrix Analysis for Decision Tree
- **True Positives (11)** and **True Negatives (5)**
- **False Positives (1)** and **False Negatives (1)**
- High precision (91.7%) and recall (91.7%) indicate strong predictive capability.

## Interactive Dashboard

### Key Features
- **Total Success vs. Failed Launches**:
  - Visualizes overall launch success and failure rates.
- **Payload and Success Correlation**:
  - Shows the relationship between payload mass and landing outcomes.

## Conclusion

The Decision Tree model, with its high accuracy and reliability, is the best choice for predicting rocket landing success. Implementing this model will enable Space Y to:
- Optimize launch operations.
- Reduce costs associated with failed landings.
- Enhance overall efficiency and competitiveness in the commercial space industry.

## Files and Folders

- **EDA Visualization Lab.ipynb**: Notebook containing exploratory data analysis and visualizations.
- **ML Prediction Part 5.ipynb**: Notebook detailing the model development and evaluation process.
- **GTP spacex dash.py**: Python script for creating an interactive dashboard.
- etc.

## Future Work

Future improvements could include:
- Further tuning of model hyperparameters to increase accuracy.
- Incorporating additional features that might affect landing success.
- Real-time data integration for continuous model updates and predictions.

## Contact

For any questions or feedback, please reach out to the project maintainer.

---

*This README was generated as part of a project to predict rocket landing success for Space Y, leveraging insights from SpaceX's launch data.*
