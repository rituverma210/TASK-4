# 🚢 Titanic Dataset - Mini Data Visualization Dashboard

## 📌 Project Overview

This project is part of my **Data Science with Python Internship**.

The objective of this project is to perform **Exploratory Data Analysis (EDA)** and build a mini data visualization dashboard using the Titanic dataset.

The project focuses on:

* Data Cleaning
* Feature Engineering
* Data Visualization
* Finding Insights from Data
* Storytelling using charts

---

# 🛠️ Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Jupyter Notebook

---

# 📂 Dataset

The Titanic dataset contains passenger information such as:

* Age
* Gender
* Passenger Class
* Fare
* Family Members
* Embarkation Port
* Survival Status

Dataset Source:
https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

---

# 🧹 Data Cleaning Performed

* Filled missing values in the `Age` column using Mean Imputation
* Filled missing values in `Embarked` using Mode
* Removed the `Cabin` column due to excessive missing values

---

# ⚙️ Feature Engineering

The following new features were created:

* `FamilySize = SibSp + Parch`
* `AgeGroup` using age categories

These features helped improve analysis and visualization.

---

# 📊 Visualizations Included

This dashboard contains multiple visualizations including:

1. Histogram of Age Distribution
2. Survival by Gender Bar Plot
3. Fare Distribution by Passenger Class (Boxplot)
4. Age vs Fare Scatterplot
5. Correlation Heatmap
6. Survival by Family Size Bar Plot

---

# 🔍 Key Insights

* Female passengers had higher survival rates
* Passenger class strongly influenced survival chances
* Children had better survival probability
* Family size affected passenger survival
* Higher fare passengers showed better survival trends

---

# 🎯 Learning Outcomes

Through this project, I learned:

* Exploratory Data Analysis (EDA)
* Data Cleaning Techniques
* Handling Missing Values
* Feature Engineering
* Data Visualization
* Storytelling with Data

---

# 📁 Project Structure

```text id="m6x5b3"
Titanic_Dashboard/
│
├── Titanic_EDA_Dashboard.ipynb
├── README.md
```

---

# 🚀 Future Improvements

* Add interactive dashboards using Plotly or Streamlit
* Apply Machine Learning models for prediction
* Perform advanced feature engineering
