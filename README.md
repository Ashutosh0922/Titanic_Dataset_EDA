# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs detailed Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, relationships, and anomalies that could impact predictive modeling.

## Technologies Used
- **Python 3.10**
- **Pandas** for data manipulation
- **NumPy** for numerical computations
- **Matplotlib** and **Seaborn** for data visualization
- **Plotly** for interactive charts (optional)

---

## Project Steps

### 1. Data Loading
- Imported the Titanic dataset into a Pandas DataFrame.
- Displayed the first few rows and checked the basic structure using `.info()` and `.describe()`.

### 2. Data Cleaning
- Identified missing values and handled them appropriately:
  - Filled missing `Age` values with the median.
  - Filled missing `Embarked` values with the mode.
- Dropped unnecessary columns like `PassengerId`, `Name`, `Ticket`, and `Cabin`.
- Converted categorical variables (`Sex`, `Embarked`) into numerical format using Label Encoding.

### 3. Statistical Summary
- Calculated important statistics like mean, median, standard deviation, minimum, and maximum values.
- Summarized key insights such as:
  - Average age of passengers.
  - Distribution of passengers across different classes (`Pclass`).

### 4. Data Visualization
- **Histograms**: Plotted distributions for features like `Age`, `Fare`, `Pclass`, and `Survived`.
- **Boxplots**: Visualized outliers in features like `Age` and `Fare`.
- **Correlation Heatmap**: Identified relationships between features (e.g., `Pclass` and `Survival`).
- **Pairplots**: Observed feature-to-feature relationships visually.

### 5. Insights and Patterns
- Higher survival rates were observed among females compared to males.
- Passengers from higher classes (`Pclass 1`) had better survival rates.
- Younger passengers had a slightly higher chance of survival.
- Strong correlation observed between `Fare` and `Pclass`.

---

## Conclusion
This EDA provides valuable insights into the Titanic dataset, helping in feature selection and understanding the data better before applying machine learning models. Proper EDA ensures higher model performance and interpretability.

---
