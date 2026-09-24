# 📊 Data Analytics — Level 2 Portfolio

Welcome to my **Level 2 Data Analytics Portfolio**, documenting my practical application of Python, statistics, machine learning, and data visualization to real-world datasets.

This repository contains a collection of progressively advanced data analytics projects completed as part of my professional data analytics training and internship journey.

The projects demonstrate my ability to move from **data preparation and exploration to statistical analysis, predictive modeling, time-series analysis, and unsupervised machine learning**.

---

## 👨‍💻 About Me

I am an **Engineer by profession and a Certified Data Analyst**, currently transitioning fully into the technology and data analytics field.

My focus is on developing practical skills in:

- 🐍 Python
- 🐼 Pandas & NumPy
- 📊 Matplotlib & Seaborn
- 🤖 Machine Learning
- 📈 Statistical Analysis
- 🗄️ SQL
- 📊 Power BI
- 📗 Excel
- 📉 Data Visualization
- 🔍 Exploratory Data Analysis

My goal is to use data to uncover insights, solve business problems, and support better decision-making.

---

# 📁 Repository Structure

```text
Level-2-Data-Analytics/
│
├── Task-1-Regression-Analysis/
│   ├── regression_analysis.ipynb
│   ├── dataset/
│   └── README.md
│
├── Task-2-Time-Series-Analysis/
│   ├── time_series_analysis.ipynb
│   ├── dataset/
│   └── README.md
│
├── Task-3-Clustering-Analysis/
│   ├── clustering_analysis.ipynb
│   ├── dataset/
│   └── README.md
│
└── README.md
```

---

# 📌 Level 2 Projects

## 1️⃣ Task 1 — Regression Analysis

### 🎯 Objective

The objective of this project was to investigate the relationship between housing characteristics and house prices and develop a regression model capable of predicting house prices.

### 📊 Dataset

The project uses a housing dataset containing variables describing different characteristics of residential properties.

For the regression analysis, **RM (average number of rooms)** was selected as the predictor variable and **MEDV (median house value)** as the target variable.

### 🔎 Analysis Performed

The project covered:

- Data loading
- Data cleaning
- Data inspection
- Exploratory data analysis
- Selection of predictor and target variables
- Relationship analysis
- Train/test splitting
- Linear regression modeling
- Prediction generation
- Model evaluation
- Data visualization

### 🤖 Model

**Linear Regression**

The model was trained to estimate:

```text
MEDV = f(RM)
```

### 📈 Model Results

The final model produced:

| Metric | Result |
|---|---:|
| R² | **0.370757** |
| MSE | **46.144775** |
| RMSE | **6.792995** |

### 💡 Key Finding

The analysis showed a **positive relationship between the average number of rooms and house value**. However, the R² value of approximately **0.371** indicates that RM alone does not explain all the variation in house prices.

This demonstrates an important machine-learning principle: **a variable can have a meaningful relationship with a target without being sufficient on its own for highly accurate prediction.**

### 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# 2️⃣ Task 2 — Time Series Analysis

### 🎯 Objective

The objective of this project is to analyze historical stock-price data as a time series and identify patterns, trends, and changes over time.

### 📊 Dataset

The project uses historical stock market data containing information such as:

- Stock symbol
- Date
- Open price
- High price
- Low price
- Close price
- Trading volume

### 🔎 Analysis Planned

The analysis covers:

- Date conversion
- Time-series indexing
- Data validation
- Stock-price trends
- Daily price movements
- Rolling averages
- Trend analysis
- Visualization
- Interpretation of temporal patterns

### 📈 Key Questions

The analysis investigates questions such as:

- How does stock price change over time?
- Are there visible upward or downward trends?
- How does trading volume change over time?
- What patterns can be observed using moving averages?
- How can historical data be visualized effectively as a time series?

### 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# 3️⃣ Task 3 — Clustering Analysis

### 🎯 Objective

The objective of this project is to apply **K-Means clustering** to group observations based on similarities in their characteristics.

### 🔎 Analysis Process

The project demonstrates:

- Data preparation
- Feature selection
- Feature scaling
- Exploratory analysis
- K-Means clustering
- Elbow method
- Cluster interpretation
- Visualization of clusters

### 🤖 Algorithm

**K-Means Clustering**

The model identifies groups of observations with similar characteristics without requiring predefined target labels.

### 📊 Model Selection

The **Elbow Method** is used to evaluate different values of K and identify an appropriate number of clusters.

The analysis will document:

- Within-cluster variation
- Inertia values
- Elbow visualization
- Selected number of clusters
- Cluster characteristics

### 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# 🧰 Tools & Technologies

| Category | Tools |
|---|---|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook |
| Version Control | Git & GitHub |
| Analytics | Statistical Analysis |
| Modeling | Regression & Clustering |

---

# 📚 Skills Demonstrated

Through these projects, I demonstrate practical experience with:

### Data Preparation
- Loading datasets
- Inspecting datasets
- Handling missing values
- Checking data types
- Preparing analytical datasets

### Exploratory Data Analysis
- Descriptive statistics
- Distribution analysis
- Relationship analysis
- Trend identification
- Data visualization

### Machine Learning
- Supervised learning
- Linear regression
- Model training
- Train/test splitting
- Prediction
- Model evaluation

### Unsupervised Learning
- K-Means clustering
- Feature preparation
- Elbow method
- Cluster interpretation

### Time Series
- Date/time handling
- Temporal analysis
- Trend analysis
- Rolling statistics
- Time-series visualization

---

# 📈 Project Workflow

Each project follows a structured analytical workflow:

```text
Data Collection
      ↓
Data Inspection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Selection
      ↓
Model Development
      ↓
Model Evaluation
      ↓
Visualization
      ↓
Interpretation
      ↓
Conclusion
```

This workflow allows the analysis to remain reproducible, structured, and professionally documented.

---

# 🎯 Learning Outcomes

Completing these projects has strengthened my ability to:

- Work with real-world datasets
- Transform raw data into analysis-ready datasets
- Perform exploratory data analysis
- Build and evaluate machine-learning models
- Interpret statistical results
- Analyze trends over time
- Apply unsupervised learning techniques
- Communicate analytical findings through visualization
- Document data projects professionally using GitHub

---

# 🚀 Future Improvements

Future versions of these projects may include:

- Multiple-variable regression models
- Feature engineering
- Model comparison
- Hyperparameter optimization
- Advanced time-series forecasting
- Additional clustering algorithms
- Interactive dashboards
- Power BI integration
- SQL-based data extraction
- Automated analytical pipelines

---

# 📂 How to Use This Repository

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Level-2-Data-Analytics.git
```

Navigate into the project:

```bash
cd Level-2-Data-Analytics
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the relevant task folder and run the notebook cells sequentially.

---

# 📌 Portfolio Highlights

### 📊 Regression Analysis
Predicting house values using linear regression and evaluating model performance.

### 📈 Time Series Analysis
Analyzing historical stock-price movements and identifying temporal trends.

### 🔵 K-Means Clustering
Using unsupervised machine learning to identify groups based on similarities within the data.

---

# 🤝 Connect With Me

I am open to opportunities involving:

- Data Analytics
- Business Intelligence
- Data Visualization
- Python Analytics
- SQL
- Power BI
- Junior/Mid-Level Data Analyst roles
- Remote Data Analytics opportunities

**GitHub:** `https://github.com/YOUR-USERNAME`

**LinkedIn:** `https://www.linkedin.com/in/rich-ejim-0a24b5295/`

---

## ⭐ If You Find This Repository Useful

Feel free to explore the individual projects, review the notebooks, and follow my journey as I continue developing my skills in **Data Analytics, Machine Learning, and Business Intelligence**.

**Turning data into insights. Building skills through practical projects.**
