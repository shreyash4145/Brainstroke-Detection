# Brain Stroke Prediction

## Overview

This project aims to develop a machine learning model to predict the likelihood of stroke occurrence based on patient data. Stroke is a leading cause of death and disability worldwide, and early detection is crucial for preventing strokes and improving patient outcomes. The project utilizes a dataset containing patient information such as age, gender, health factors, and lifestyle choices to build and evaluate the prediction model.

## Dataset

The dataset used in this project includes the following features:

- **Demographic Data**: Age, gender, region, state
- **Health Factors**: Body Mass Index (BMI), hypertension (high blood pressure), history of heart disease, smoking status, blood glucose levels

## Data Visualization

To better understand the data and its implications, various data visualization techniques were employed:

1. **Bar Plot**: Used to display the distribution of categorical variables.
2. **Count Plot**: Shows the frequency of occurrences of different categories within a categorical variable.
3. **Pie Chart**: Displays the proportion of each category in a whole.
4. **Histogram**: Represents the distribution of a continuous numerical variable.
5. **Heatmap Plot**: Visualizes data in a matrix format, useful for identifying patterns and correlations.

## Libraries Used

- **Pandas**: For data manipulation, cleaning, and analysis.
- **NumPy**: For numerical operations and array manipulation.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For creating more attractive and informative statistical graphics.
- **Sklearn preprocessing**: For preparing data for machine learning models.
- **sklearn.model_selection**: For data splitting, cross-validation, and parameter tuning.
- **category_encoders**: For converting categorical variables into numerical representations.
- **sklearn.svm**: For support vector machine (SVM) algorithms used in classification and regression tasks.

## Results

The project successfully developed a machine learning model capable of predicting stroke occurrence based on patient characteristics. The model's performance was evaluated using various metrics, and while further validation and potential refinement are necessary, the initial results are promising. The model can help healthcare professionals identify high-risk patients and implement preventative measures, potentially improving patient outcomes.

## Conclusion

This project demonstrates the potential of machine learning in early stroke risk assessment. By leveraging patient data, the developed model can assist healthcare professionals in prioritizing preventative measures, ultimately contributing to better patient care and outcomes.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/brain-stroke-prediction.git ```
2. Install Requirements
  ```bash
   pip install -r requirements.txt 
```
3. Run Notebooks
   ```Bash
   jupyter notebook brain_stroke_prediction.ipynb
   ```
