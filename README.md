

# Student Performance Analysis and Prediction

## Roadmap

**Objective**: The main objective of this project is to analyze various factors influencing student performance and develop predictive models to forecast future student performance based on these factors.

**Data Collection**: The project starts with collecting a dataset of student performance. 

**Dataset**: The dataset used is sourced from [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977). It includes information on gender, ethnicity, parental education level, lunch type, test preparation, and scores in math, reading, and writing for 1000 students.

**Preprocessing**: 
- Inspecting data for missing values and duplicates
- Cleaning data and converting data types as necessary
- Descriptive statistics and initial visualizations

**Exploratory Data Analysis (EDA)**: 
- Distribution analysis of scores in math, reading, and writing
- Analyzing relationships between different features and scores
- Correlation heatmap to identify significant correlations

**Model Training**:
- Data Preparation: Splitting the dataset into features (X) and target variables (y), encoding categorical variables, and standardizing numerical variables
- Model Selection: Training and evaluating multiple regression models including Linear Regression, Ridge Regression, Lasso Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest, AdaBoost, Support Vector Regressor (SVR), CatBoost Regressor, and XGBoost Regressor
- Model Evaluation: Using metrics like R2 score, Mean Absolute Error (MAE), and Mean Squared Error (MSE) to evaluate model performance

**Evaluation**: The models are evaluated based on their predictive performance, and the best-performing model is selected for deployment.

**Model Deployment**: The best-performing model can be deployed using Flask, a lightweight web server gateway interface (WSGI) web application framework. This allows the model to be accessed via a simple web interface, enabling real-time predictions.

Overall, this project aims to provide insights into factors affecting student performance and develop robust predictive models to aid in educational planning and intervention strategies.

## Lessons Learned

This project provided a valuable opportunity to apply data science concepts to a practical problem. Key lessons learned include:
- The importance of data cleaning and preprocessing in ensuring accurate analysis
- How to use various regression models and evaluate their performance
- The critical role of feature engineering in improving model accuracy
- Insights into the factors that influence student performance

I’m excited about the potential applications of this project and look forward to exploring more ways to leverage data science in the field of education. 💡

## Authors

- [Devesh](https://github.com/Devesh061102)

## Acknowledgments

- [Kaggle - Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)
