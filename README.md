#  Titanic Data Analysis – Task 3

##  Project Overview

This project is part of the **Data Analysis with Python Internship**. The objective is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset by cleaning the data, handling missing values, answering analytical questions, and creating meaningful visualizations.

The project demonstrates essential data analysis techniques using Python and helps build storytelling skills through data visualization.

---

##  Objectives

- Clean and preprocess the Titanic dataset.
- Handle missing values using appropriate techniques.
- Perform Exploratory Data Analysis (EDA).
- Analyze survival rates based on different factors.
- Visualize insights using professional charts.

---

##  Dataset

- **Dataset:** Titanic Dataset
- **Source:** Kaggle Titanic Dataset

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

##  Data Cleaning

The following preprocessing steps were performed:

- Filled missing values in the **Age** column using the mean.
- Filled missing values in the **Embarked** column using the mode.
- Removed the **Cabin** column due to excessive missing values.
- Created a new **AgeGroup** column.
- Created a new **FamilySize** column using:

```python
FamilySize = SibSp + Parch
```

---

##  Exploratory Data Analysis

### 1. Survival Rate by Age Group

Passengers were categorized into:

- Child
- Teen
- Young Adult
- Adult
- Senior

The survival rate was calculated for each group.

### 2. Survival Rate by Embarkation Port

Compared passenger survival rates based on embarkation ports:

- Southampton (S)
- Cherbourg (C)
- Queenstown (Q)

### 3. Survival Rate by Family Size

Analyzed how family size influenced passenger survival.

---

##  Visualizations

The notebook includes the following visualizations:

- 1. Age Distribution Histogram
- 2. Correlation Heatmap
- 3. Survival Rate by Family Size Bar Plot

---

##  Key Insights

- Younger passengers generally had better survival rates.
- Female passengers showed higher survival rates than male passengers.
- Passengers embarking from Cherbourg had comparatively higher survival chances.
- Small families had better survival rates than passengers traveling alone or with very large families.
- Passenger class and gender significantly influenced survival.

---

##  How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/Titanic_Data_Analysis.git
```

2. Open the **Titanic_Task3_Mini_EDA.ipynb** notebook in **Google Colab** or **Jupyter Notebook**.

3. Install the required libraries (if needed):

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run all notebook cells sequentially.

---

##  Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Handling missing values
- Feature engineering
- Exploratory Data Analysis (EDA)
- GroupBy operations in Pandas
- Data visualization using Matplotlib and Seaborn
- Extracting meaningful insights from real-world datasets

---

##  Internship Task

**Internship:** Data Analysis with Python Internship

**Task:** Task 3 – Titanic Mini Exploratory Data Analysis (EDA)

---

##  Author

**Nikhil**

B.Tech – Computer Science and Engineering

Vignan's Institute of Information Technology

---

⭐ If you found this project helpful, consider giving this repository a star!
