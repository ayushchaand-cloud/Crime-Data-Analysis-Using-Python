# Crime Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing crime data using **Python, Pandas, Matplotlib, and Seaborn**. The main purpose of the project is to understand crime patterns based on different factors such as crime type, victim gender, city, and number of reported cases.

The project uses data analysis and visualization techniques to identify patterns and trends in different types of crimes.

---

## 🎯 Objectives

* Analyze crime cases using Python.
* Understand the distribution of different crime types.
* Compare crime cases based on victim gender.
* Identify cities with higher numbers of reported cases.
* Create graphs and visualizations for better understanding.
* Use basic data analysis techniques to find useful patterns.

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **NumPy**

---

## 📂 Project Structure

```text
Crime-Data-Analysis/
│
├──notebook.ipynb
├── crime_data.csv
├── README.md
└── images/
    └── visualizations/
```

> File names can be changed according to the actual files uploaded to the repository.

---

## 📊 Dataset

The dataset contains information related to reported crime cases.

Some important columns used in the analysis include:

* `Crime Description`
* `Victim Gender`
* `City`
* Other available crime-related attributes

The dataset is used only for **educational and analytical purposes**.

---

## 🔍 Analysis Performed

### 1. Crime Type Analysis

Different crime categories are analyzed to understand which types of crimes occur more frequently.

### 2. Gender-Based Analysis

Crime cases are compared based on the victim's gender.

For example, the analysis can be used to identify the number of male or female victims for a particular crime.

### 3. City-Wise Analysis

The project analyzes the number of cases reported in different cities.

This helps identify cities having comparatively higher reported crime cases.

### 4. Crime-Specific Analysis

Specific crimes such as:

* Identity Theft
* Cyber Crime
* Other available crime categories

are analyzed separately.

---

## 📈 Visualizations

Different graphs are created to make the analysis easier to understand.

Examples include:

* Bar Charts
* Count Plots
* City-wise Crime Charts
* Gender-wise Crime Charts
* Crime Category Comparisons

---

## 💻 Example Analysis

```python
id = (
    f[(f['Crime Description'] == 'IDENTITY THEFT') &
      (f['Victim Gender'] == 'M')][['City']]
    .value_counts()
    .sort_values(ascending=False)
    .reset_index()
)

id.columns = ['City', 'Case Count']
```

The above analysis finds the number of **Identity Theft cases involving male victims**, grouped by city.

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project Folder

```bash
cd Crime-Data-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Open:

```text
crime_analysis.ipynb
```

Run the cells from top to bottom.

---

## 📌 Key Findings

The analysis helps in understanding:

* Which crime categories are more common.
* How crime cases differ between male and female victims.
* Which cities have comparatively more reported cases.
* How different crime categories are distributed across locations.

The exact findings depend on the dataset used in the notebook.

---

## 📚 Learning Outcomes

Through this project, I learned how to:

* Load datasets using Pandas.
* Clean and filter data.
* Group data using `groupby()`.
* Count categorical values using `value_counts()`.
* Sort analytical results.
* Create visualizations using Matplotlib and Seaborn.
* Extract useful information from real-world datasets.
* Present data analysis results in a Jupyter Notebook.

---

## 🔮 Future Improvements

The project can be improved by adding:

* Interactive dashboards using **Power BI**.
* More advanced statistical analysis.
* Machine Learning models for crime prediction.
* Time-based crime trend analysis.
* Geographical crime visualization.
* More detailed correlation analysis.

---

## 👨‍💻 Author

**Ayush Singh**

B.Tech CSE | Data Analytics

### Skills Used

`Python` `Pandas` `SQL` `Matplotlib` `Seaborn` `Data Analysis`

---

## ⭐ Conclusion

This project demonstrates how Python-based data analysis can be used to explore crime datasets and identify meaningful patterns. Data visualization makes the results easier to understand and can help in further investigation and decision-making.

This project was created for **academic and learning purposes**.
