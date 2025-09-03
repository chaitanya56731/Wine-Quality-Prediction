***🍷 Wine Quality Prediction***

This project uses Machine Learning techniques to predict the quality of wine based on its physicochemical features. The dataset contains various attributes such as acidity, sugar, pH, and alcohol, which are used to classify wine quality on a scale of 0–10.
📖 Overview

The goal of this project is to build a predictive model that helps winemakers and quality controllers assess wine quality more efficiently.
I implemented classification models to determine wine quality based on physicochemical test results.
📂 Dataset

Source: UCI Machine Learning Repository – Wine Quality Dataset

***Features include:***

Fixed acidity
Volatile acidity
Citric acid
Residual sugar
Chlorides
Free sulfur dioxide
Total sulfur dioxide
Density
pH
Sulphates
Alcohol

***Tech Stack***

Programming Language: Python

**Libraries Used:**

Pandas & NumPy (data processing)
Matplotlib & Seaborn (data visualization)
Scikit-learn (machine learning models)
Jupyter Notebook (experimentation)

**📊 Model Performance**
Model	Accuracy	F1-Score
Logistic Regression	0.72	0.70
Decision Tree	0.74	0.72
Random Forest	0.81	0.79

***Random Forest Classifier gave best accuracy***

**Installation & Usage**

1) Clone the repository:
git clone https://github.com/chaitanya56731/wine-quality-prediction.git
cd wine-quality-prediction

2)Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate 

3)Install dependencies:
pip install -r requirements.txt

4)Run Jupyter Notebook:
jupyter notebook

***🏆 Results:***

Achieved 83% accuracy using Gradient Boosting.
Identified alcohol, volatile acidity, and sulphates as the most important features affecting wine quality.

**🔮 Future Improvements**

Use Deep Learning (Neural Networks) for higher accuracy.
Build a Flask/Django web app for interactive predictions.
Deploy the model using Streamlit or Heroku.
