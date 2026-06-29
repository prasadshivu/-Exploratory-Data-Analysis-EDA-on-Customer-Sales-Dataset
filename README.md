# 📊 Exploratory Data Analysis (EDA) on Customer Sales Dataset

A Python-based Exploratory Data Analysis (EDA) project that analyzes customer sales data to gain meaningful insights through data preprocessing, statistical analysis, and visualization. The project demonstrates essential data science techniques such as handling missing values, correlation analysis, distribution analysis, and outlier detection.

---

# 🚀 Project Overview

This project focuses on understanding customer behavior by analyzing a sales dataset. It includes data validation, preprocessing, summary statistics, and visualizations to uncover trends and relationships between different customer attributes.

The project is ideal for beginners learning **Data Science**, **Feature Engineering**, and **Exploratory Data Analysis (EDA)** using Python.

---

# ✨ Features

* Load and validate the dataset
* Remove duplicate header rows
* Convert columns to appropriate numeric data types
* Handle missing values using:

  * Median Imputation
  * Mean Imputation
* Generate descriptive statistics
* Analyze spending distribution
* Compute correlation matrix
* Visualize correlations using a heatmap
* Detect outliers using boxplots

---

# 📂 Dataset

**Dataset:** `sales_data.csv`

The dataset includes customer information such as:

* Customer_ID
* Age
* Spending
* Visits_Per_Month

---

# 🛠️ Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/EDA-Customer-Sales-Analysis.git
```

Navigate to the project directory:

```bash
cd EDA-Customer-Sales-Analysis
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

---

# ▶️ Running the Project

Run the Python script:

```bash
python EDA_project.py
```

---

# 📁 Project Structure

```text
EDA-Customer-Sales-Analysis/
│
├── sales_data.csv
├── EDA_project.py
├── README.md
└── requirements.txt
```

---

# 🔄 Workflow

1. Load the dataset
2. Validate file existence and content
3. Remove duplicate header rows
4. Convert columns to numeric format
5. Handle missing values
6. Display summary statistics
7. Plot spending distribution
8. Calculate correlation matrix
9. Visualize correlation heatmap
10. Detect age outliers using a boxplot

---

# 📊 Visualizations

The project generates:

* 📈 Spending Distribution Histogram
* 🔥 Correlation Heatmap
* 📦 Age Boxplot

These visualizations help identify customer spending patterns, relationships between variables, and potential outliers.

---

# 📚 Concepts Covered

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Missing Value Imputation
* Data Validation
* Descriptive Statistics
* Correlation Analysis
* Data Visualization
* Outlier Detection

---

# 📌 Sample Output

```text
Understanding the Dataset

Successfully loaded

Shape of the dataset:
Rows: XXXX
Columns: XXXX

Handling Missing Values...

Median Age: XX

Mean Spending: XXXX

Correlation Matrix

Plotting Correlation Heatmap

Finding Outliers...
```

---

# 🔮 Future Enhancements

* Add feature scaling (StandardScaler / MinMaxScaler)
* Perform categorical encoding
* Build machine learning prediction models
* Create interactive dashboards using Plotly or Streamlit
* Export cleaned datasets for further analysis
* Automate EDA report generation

---

# 👨‍💻 Author

**Shiva**

If you found this project useful, consider giving it a ⭐ on GitHub. Contributions, suggestions, and improvements are always welcome!
