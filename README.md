# Titanic Data Visualization Dashboard

## Project Overview

This project presents a mini data visualization dashboard built using the Titanic dataset. The goal is to perform data cleaning, feature engineering, exploratory data analysis (EDA), and visualization to identify factors that influenced passenger survival.

The project demonstrates how raw data can be transformed into meaningful insights through statistical analysis and visual storytelling.

---

## Objective

The primary objectives of this project are:

- Clean and preprocess the Titanic dataset
- Handle missing values using appropriate techniques
- Create meaningful features for analysis
- Explore survival patterns among passengers
- Build multiple visualizations to communicate insights
- Practice data storytelling using charts and observations

---

## Tools & Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```plaintext
titanic-dashboard-analysis/
│
├── data/
│   └── titanic.csv
│
├── images/
│   └── (optional exported figures)
│
├── notebooks/
│   └── titanic_dashboard.ipynb
│
└── README.md
```

---

## Dataset Information

The Titanic dataset contains information about passengers aboard the RMS Titanic, including demographic details, ticket information, and survival outcomes.

Important attributes include:

- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Fare
- Embarkation Port (Embarked)
- Number of Family Members
- Survival Status

Target Variable:

- Survived
  - 0 = Did Not Survive
  - 1 = Survived

---

## Data Cleaning Performed

The following preprocessing steps were carried out before analysis:

### Missing Value Handling

- Missing values in the Age column were filled using the median age.
- The Cabin column was removed due to a large number of missing values.

### Duplicate Handling

- Duplicate records were identified and removed.

These steps helped improve data quality and ensure more reliable analysis.

---

## Feature Engineering

To enhance the analysis, additional features were created.

### FamilySize

A new feature was created using:

FamilySize = SibSp + Parch

Where:

- SibSp = Number of siblings/spouses aboard
- Parch = Number of parents/children aboard

This feature helps analyze the impact of family size on survival.

### AgeGroup

Passengers were categorized into:

- Child
- Teen
- Young Adult
- Adult
- Senior

This allowed survival patterns to be studied across age categories.

---

## Exploratory Data Analysis (EDA)

The project investigates several important questions:

### Survival Analysis

- Did gender influence survival chances?
- Did passenger class affect survival?
- Did age influence survival outcomes?
- Did family size impact survival?
- Did embarkation location affect survival rates?

### Passenger Demographics

- Age distribution of passengers
- Family size distribution
- Fare distribution across classes

---

## Visualizations Included

The dashboard contains multiple visualizations including:

### 1. Passenger Age Distribution Histogram

Displays the age distribution of passengers aboard the Titanic.

### 2. Survival Rate by Gender

Compares survival rates between male and female passengers.

### 3. Fare Distribution by Passenger Class (Boxplot)

Shows how ticket fares varied across passenger classes and highlights outliers.

### 4. Age vs Fare Scatterplot

Explores the relationship between passenger age and fare while considering survival status.

### 5. Correlation Heatmap

Visualizes relationships between numerical variables within the dataset.

### 6. Survival Rate by Passenger Class

Analyzes how socioeconomic status influenced survival outcomes.

### 7. Survival Rate by Embarkation Port

Compares survival patterns among passengers boarding from different locations.

### 8. Family Size Analysis

Examines the relationship between family size and survival probability.

---

## Key Insights

- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers showed the highest survival rates.
- Most passengers belonged to the young adult age group.
- Children generally had better survival chances than older passengers.
- Higher ticket fares were associated with improved survival outcomes.
- Family size influenced survival patterns.
- Survival rates varied across embarkation ports.
- Passenger class and fare showed meaningful relationships with survival.

---

## Conclusion

This project demonstrates how Exploratory Data Analysis (EDA) and data visualization can be used to uncover meaningful patterns in real-world datasets.

Through data cleaning, feature engineering, statistical analysis, and visual storytelling, important factors affecting Titanic passenger survival were identified and communicated effectively.

The dashboard approach makes complex data easier to understand and highlights the value of visualization in data-driven decision-making.

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <repository-link>
```

### 2. Install Required Libraries

```bash
pip install pandas matplotlib seaborn
```

### 3. Place Dataset

Move the Titanic dataset into the `data/` folder:

```plaintext
data/titanic.csv
```

### 4. Open Notebook

Open:

```plaintext
notebooks/titanic_dashboard.ipynb
```

### 5. Run All Cells

Execute all notebook cells sequentially to reproduce the analysis and visualizations.

---
