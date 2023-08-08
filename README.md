# Heart Disease Prediction Project

This project aims to predict the presence of heart disease in patients using machine learning algorithms. The dataset used for this project contains various medical attributes and a binary target indicating the presence (1) or absence (0) of heart disease.

## Dataset

The dataset contains the following attributes:

- age
- sex
- chest pain type
- resting blood pressure
- serum cholesterol
- fasting blood sugar
- resting electrocardiographic results
- maximum heart rate achieved
- exercise induced angina
- ST depression induced by exercise relative to rest
- slope of the peak exercise ST segment
- number of major vessels colored by fluoroscopy
- thal (thalassemia)

## Project Structure

- `heart.csv`: The dataset file.
- `heart_disease_prediction.ipynb`: Jupyter Notebook containing code for data preprocessing, exploratory data analysis, and model training.
- `README.md`: This README file explaining the project.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/Subrat66/Heart_disease_prediction.git

2. Install the required packages:
    pip install pandas matplotlib seaborn numpy scikit-learn

3. Open and run the heart_disease_prediction.ipynb Jupyter Notebook to preprocess the data, perform exploratory data analysis, and train machine learning models.

## Results

The project evaluates two machine learning algorithms: Logistic Regression and Random Forest Classifier. Performance metrics including accuracy, precision, recall, and F1-score are reported for each algorithm. The Random Forest model generally demonstrates superior performance compared to the Logistic Regression model.
