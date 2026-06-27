# Data Science Track OASIS INFOBYTE Internship

This repository contains five end-to-end machine learning projects completed as part of the OASIS INFOBYTE Data Science internship track. Each project follows a consistent workflow: data loading & cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation all documented in a clean, commented Jupyter Notebook with an accompanying Word report.

## 📁 Project Structure

| Project | Notebook | Report | Dataset |
|---------|----------|--------|---------|
| 🌸 Iris Flower Classification | [📓 Notebook](Data_Science/Task_1_Iris_Classification.ipynb) | [📄 Report](Data_Science/Task_1_Iris_Classification_Report.docx) | Built into Scikit-learn |
| 📈 Unemployment Analysis | [📓 Notebook](Data_Science/Task_2_Unemployment_Analysis.ipynb) | [📄 Report](Data_Science/Task_2_Unemployment_Analysis_Report.docx) | [📊 Dataset](Data_Science/Unemployment_in_India.csv) |
| 🚗 Car Price Prediction | [📓 Notebook](Data_Science/Task_3_Car_Price_Prediction.ipynb) | [📄 Report](Data_Science/Task_3_Car_Price_Prediction_Report.docx) | [📊 Dataset](Data_Science/car_data.csv) |
| 📧 Email Spam Detection | [📓 Notebook](Data_Science/Task_4_Spam_Detection.ipynb) | [📄 Report](Data_Science/Task_4_Spam_Detection_Report.docx) | [📊 Dataset](Data_Science/spam.csv) |
| 📊 Sales Prediction | [📓 Notebook](Data_Science/Task_5_Sales_Prediction.ipynb) | [📄 Report](Data_Science/Task_5_Sales_Prediction_Report.docx) | [📊 Dataset](Data_Science/advertising.csv) |

## 🧠 Projects

### 1. Iris Flower Classification
Classifies iris flowers into Setosa, Versicolor, or Virginica from sepal/petal measurements.
- **Stack:** scikit-learn, pandas, seaborn
- **Models:** Logistic Regression, KNN, Decision Tree, Random Forest
- **Result:** KNN achieved **100% test accuracy**; petal length/width were the most discriminative features.

### 2. Unemployment Analysis with Python (India, COVID-19 impact)
Explores regional and temporal unemployment trends across Indian states from January–October 2020.
- **Stack:** pandas, matplotlib, seaborn
- **Result:** National unemployment more than doubled post-lockdown (9.2% → 13.0% average), peaking at **23.2% in May 2020**, with sharp regional variation (Haryana averaged 27.5%).

### 3. Car Price Prediction
Predicts the resale price of used cars from showroom price, age, mileage, and categorical features.
- **Stack:** pandas, scikit-learn, seaborn
- **Models:** Linear Regression, Random Forest Regressor, Gradient Boosting Regressor
- **Result:** Linear Regression performed best (**R² = 0.74**); present price and car age were the dominant predictors.

### 4. Email/SMS Spam Detection
NLP binary classifier distinguishing spam from legitimate (ham) messages.
- **Stack:** scikit-learn (TF-IDF, Naive Bayes), NLTK, WordCloud
- **Models:** Multinomial Naive Bayes, Logistic Regression
- **Result:** Naive Bayes achieved **97.7% accuracy** with the best recall (83.2%), making it the stronger choice for catching spam.

### 5. Sales Prediction from Advertising Spend
Predicts product sales from TV, Radio, and Newspaper advertising budgets.
- **Stack:** pandas, scikit-learn, seaborn
- **Models:** Linear Regression, Random Forest Regressor
- **Result:** Random Forest performed best (**R² = 0.98**); TV and Radio spend were the dominant sales drivers, Newspaper had negligible impact.

## 📊 Summary of Results

| # | Task | Best Model | Key Metric |
|---|------|-----------|------------|
| 1 | Iris Classification | K-Nearest Neighbors | 100.0% accuracy |
| 2 | Unemployment Analysis | EDA / statistical analysis | +3.7 pp unemployment post-COVID |
| 3 | Car Price Prediction | Linear Regression | R² = 0.741 |
| 4 | Spam Detection | Multinomial Naive Bayes | 97.7% accuracy, 83.2% recall |
| 5 | Sales Prediction | Random Forest Regressor | R² = 0.982 |

## 🛠️ Tech Stack

Python · pandas · NumPy · scikit-learn · matplotlib · seaborn · NLTK · WordCloud · Jupyter Notebook

## 📦 Datasets

| Task | Dataset | Source |
|------|---------|--------|
| 1 | Iris | [Scikit-learn Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html) |
| 2 | Unemployment in India | [Kaggle – Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india) |
| 3 | Vehicle Dataset from CarDekho | [Kaggle – Vehicle Dataset from CarDekho](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho) |
| 4 | SMS Spam Collection | [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) |
| 5 | Advertising Dataset | [Kaggle – Advertising Dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset) |
## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk wordcloud jupyter
jupyter notebook
```

Open any notebook and run all cells top to bottom. Each notebook is self-contained and loads its dataset from the `data/` folder (Task 1 loads directly from scikit-learn, no file needed).

## ✍️ Author

Nathaniel Data Science Intern, OASIS INFOBYTE

---
*This project was completed as part of a structured Data Science track internship assignment, covering classification, regression, and NLP across five real-world datasets.*

