# 🧠 Coding Samurai Data Science Internship Projects

This repository showcases the projects I completed as part of my **Data Science Internship at Coding Samurai**.  
Each project focuses on applying key **data science and visualization skills** using industry tools like **Excel** and **Python (Pandas, Matplotlib, Seaborn)**.

---

## 🚴‍♂️ Project 1: Sales Data Analysis (Excel)

### 📋 Project Overview
The goal of this project was to perform a **simple data analysis** on a retail-style dataset (Bike Buyers data) using **Microsoft Excel**, focusing on descriptive statistics, data cleaning, and interactive visualizations.

### 🎯 Objectives
- Clean and organize raw data for better analysis.  
- Perform **basic descriptive analysis** to find trends and insights.  
- Build **interactive PivotTables and charts**.  
- Design a **dashboard** to visualize key metrics effectively.

### 🧠 Skills Demonstrated
- Data Cleaning & Transformation  
- Descriptive Analytics  
- Excel PivotTables & PivotCharts  
- Dashboard Creation  
- Data Visualization & Insights Communication  

### 🗂️ Dataset Details
**Dataset Name:** Bike Buyers Dataset  
Each record represents a potential customer with demographic and lifestyle details.

| Column Name | Description |
|--------------|-------------|
| ID | Unique Customer ID |
| Marital Status | Married / Single |
| Gender | Male / Female |
| Income | Annual income |
| Children | Number of children |
| Education | Highest education level |
| Occupation | Job category |
| Home Owner | Whether the customer owns a home |
| Cars | Number of cars owned |
| Commute Distance | Distance traveled to work |
| Region | Geographic region |
| Age | Customer’s age |
| Age Bracket | Age category (Adolescent, Middle Age, Old) |
| Purchased Bike | Whether the customer purchased a bike |

### ⚙️ Steps Performed

#### 1. Data Cleaning
- Standardized text values (e.g., converted “M/F” to “Male/Female”).  
- Added a new column **“Age Bracket”** based on the age range.  
- Removed inconsistencies and formatted income values.

#### 2. Data Analysis
Created **three PivotTables** to explore:
1. Average Income per Purchase  
2. Customer Commute Distance  
3. Customer Age Bracket  

#### 3. Dashboard Creation
Built a dynamic **Excel Dashboard** with:
- PivotCharts linked to analyses.  
- **Slicers** for Region, Marital Status, and Gender.  
- All slicers synchronized for interactive filtering.

### 📊 Key Insights
- Married individuals showed higher average income levels.  
- Most short-distance commuters (0–1 miles) didn’t purchase bikes.  
- The **Middle Age group** (30–50 years) made up the largest buyer segment.  

### 💡 Tools Used
- **Microsoft Excel 2016**
  - PivotTables  
  - PivotCharts  
  - Slicers  
  - Conditional Formatting  

### 🚀 Outcome
This project enhanced my understanding of:
- Data analysis workflow from raw → insights → visualization  
- Building professional Excel dashboards  
- Communicating insights effectively through visuals  

---

## 🚢 Project 2: Exploratory Data Analysis on Titanic Dataset (Python)

### 📋 Project Overview
This project involved performing **Exploratory Data Analysis (EDA)** on the **Titanic dataset** to uncover trends and insights related to passenger survival.  
It was completed using **Python** with libraries such as Pandas, Matplotlib, and Seaborn.

### 🎯 Objectives
- Perform **data cleaning** and handle missing values.  
- Analyze relationships between features like **Age, Gender, Class, and Survival**.  
- Apply **visualization techniques** to highlight insights.

### 🧠 Skills Demonstrated
- Python (Pandas, NumPy)  
- Data Cleaning & Transformation  
- Exploratory Data Analysis (EDA)  
- Data Visualization (Matplotlib, Seaborn)  
- Feature Engineering (One-Hot Encoding)

### ⚙️ Steps Performed

#### 1. Data Understanding
- Loaded the Titanic dataset and explored its structure using `.info()`, `.describe()`, and `.head()`.

#### 2. Data Cleaning
- Filled missing values (e.g., mean age for missing ages, mode for embarked values).  
- Dropped unnecessary columns like PassengerId and Cabin for simplicity.

#### 3. Data Visualization
- Used **Seaborn and Matplotlib** for visual insights:
  - Survival rate by gender  
  - Age distribution of passengers  
  - Relationship between passenger class and survival  
  - Boxplots for age vs class 

#### 4. Statistical Summary
- Explored survival rates using group-based analysis (e.g., by Gender and Class).  
- Compared key trends using pivot-style summaries.

### 📊 Key Insights
- Females had a significantly higher survival rate than males.  
- First-class passengers were more likely to survive than third-class.  
- Most passengers aged between **20–40 years**.  
- Missing values in the dataset had noticeable patterns tied to passenger class.

### 💡 Tools Used
- **Python**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  

### 📘 Conclusion
Through this analysis, I gained practical experience in:
- Applying EDA methods to real datasets.  
- Handling missing data and encoding categorical variables.  
- Building visual stories using Python libraries.

---

## 🏠 Project 3: Simple Linear Regression on House Prices (Python)

### 📋 Project Overview
This project demonstrates **Simple Linear Regression** using **Python** to predict **house prices** based on **area (in square feet)**.  
It focuses on understanding the **linear relationship** between two continuous variables — *Area* and *Price* — using machine learning techniques.

### 🎯 Objectives
- Understand the concept of **Simple Linear Regression**.  
- Build and train a regression model using **Scikit-learn**.  
- Visualize the **relationship between Area and Price**.  
- Evaluate model accuracy using performance metrics.

### 🧠 Skills Demonstrated
- Machine Learning (Supervised Learning)  
- Data Preprocessing  
- Model Training & Prediction  
- Data Visualization  
- Evaluation Metrics Interpretation  

### ⚙️ Steps Performed

#### 1. Data Understanding
- Loaded a dataset containing **two columns** — *Area* and *Price*.  
- Explored the dataset using `.head().

#### 2. Data Visualization 
- Used **Matplotlib** for visualization.

#### 3. Model Building
- Trained a **Linear Regression model** using `LinearRegression()` from **Scikit-learn**.

#### 4. Model Evaluation
- Predicted prices on test data.  
- Plotted the **Regression Line** to visualize actual vs predicted results. 

### 📊 Key Insights
- Larger areas correspond to higher house prices.  
- The model fits the dataset accurately with minimal error.

### 💡 Tools Used
- **Python**
  - Pandas  
  - NumPy  
  - Matplotlib   
  - Scikit-learn  

### 📘 Conclusion
This project provided practical experience in applying **Machine Learning regression techniques** for **real estate price prediction**.  
It solidified my understanding of **data modeling, visualization, and performance evaluation** in a regression context.

---

## 👨‍💻 Author
**Syed Ahmed Ali Shah**  
📧 [ahmedalilm10@gmail.com](mailto:ahmedalilm10@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ahmed-shah-b4a458284)  
🌐 [Portfolio](https://shahjee10.github.io/) 

---

## 🏷️ Tags
`#Excel` `#DataAnalytics` `#Dashboard` `#Python` `#EDA` `#Visualization` `#Regression` `#MachineLearning` `#Internship` `#CodingSamurai`
