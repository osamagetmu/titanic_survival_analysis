# 🛳️ Titanic Survival Analysis – Advanced EDA Project

This project performs advanced Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights about survival rates.

---

## 🔍 Key Concepts

- **EDA**: Exploratory Data Analysis – the process of visually and statistically exploring a dataset to understand its structure, spot patterns, and detect anomalies.
- **Feature Engineering**: The creation or transformation of data columns to enhance the quality of analysis or machine learning performance.
- **Correlation**: A statistical measure that describes how two variables move in relation to each other.
- **Countplot**: A bar chart used to show the count of observations in each category.
- **Boxplot**: A plot that displays the distribution, median, and outliers of a numerical feature.

---

## 🧾 Dataset Column Meanings

| Column     | Description |
|------------|-------------|
| `Survived` | 0 = No, 1 = Yes |
| `Pclass`   | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| `Name`     | Full name of the passenger |
| `Sex`      | Gender |
| `Age`      | Age in years |
| `SibSp`    | Number of siblings/spouses aboard |
| `Parch`    | Number of parents/children aboard |
| `Fare`     | Ticket fare |
| `Embarked` | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |
| `Title`    | New feature extracted from Name (Mr, Mrs, Miss...) |
| `FamilySize` | SibSp + Parch + 1 |
| `AgeGroup` | Age binned into categories: Child, Teen, Adult, Senior |

---

## 📌 Project Features

- Fill missing values (e.g., Age, Embarked)
- Create new columns: `FamilySize`, `Title`, `AgeGroup`
- Visualize data distributions and survival patterns
- Generate a correlation heatmap between numerical features

---

## 📈 Visual Outputs

- `correlation_heatmap.png`: Shows correlation between features
- `survival_by_title.png`: Compares survival rates by title
- `age_boxplot.png`: Age distributions grouped by survival

---

## 🧰 Tools Used

- Python
- Pandas
- Seaborn
- Matplotlib

---

## 🚀 How to Run

1. Install requirements:
```bash
pip install -r requirements.txt
