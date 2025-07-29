
# 🍷 Wine Quality EDA Project

## 📁 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of the red wine dataset from the *Portuguese Vinho Verde* region. It aims to uncover patterns, relationships, and data quality issues that influence wine quality using physicochemical attributes.

The dataset can be used for both **regression** and **classification** tasks. However, this project emphasizes exploratory analysis to help understand key factors affecting wine quality.

---

## 📊 Dataset Information

The dataset contains **physicochemical** tests as input variables and **sensory quality scores** as the output variable.

- Source: UCI Machine Learning Repository
- Records: 1599 samples
- Features: 11 numeric input variables and 1 target output (`quality`)

### 🔢 Features (Input Variables):

| Variable | Description |
|----------|-------------|
| `fixed acidity` | Tartaric acid level in g/dm³ |
| `volatile acidity` | Acetic acid level (vinegar taste) |
| `citric acid` | Citric acid content (freshness) |
| `residual sugar` | Remaining sugar after fermentation |
| `chlorides` | Salt concentration |
| `free sulfur dioxide` | SO₂ that protects wine from microbes |
| `total sulfur dioxide` | Total SO₂ (free + bound) |
| `density` | Density of the wine |
| `pH` | Acidity level |
| `sulphates` | Antimicrobial and wine stability factor |
| `alcohol` | Alcohol content in % |

### 🎯 Target Variable:

- `quality`: Wine quality score (integer between 0 and 10, rated by tasters)

---

## 📌 Goals of the Analysis

- Understand distribution and correlations between variables.
- Identify features with the most influence on wine quality.
- Analyze outliers, skewness, and imbalance in the dataset.
- Visualize key trends using Python (Pandas, Matplotlib, Seaborn).

---

## 🛠️ Tools & Libraries Used

- **Python** (Jupyter Notebook)
- **Pandas** for data manipulation
- **NumPy** for numerical operations
- **Matplotlib / Seaborn** for data visualization
- **Scikit-learn** for basic preprocessing and metrics (optional)

---

## 📈 Key Insights

- Higher alcohol levels generally correlate with better wine quality.
- Volatile acidity has a negative impact on quality.
- Wines with balanced pH and sulphates tend to be rated higher.
- The quality score distribution is imbalanced with most wines rated 5 or 6.

---

## 📂 File Structure

```bash
📁 WineQualityEDA
│
├── 1.0-WinequalityEDA.ipynb         # Main EDA Jupyter Notebook
├── winequality_red_corrected.csv    # Cleaned dataset with comma delimiters
└── README.md                        # Project overview and documentation
```

---

## ✅ How to Run the Project

1. Clone or download the repository.
2. Open the notebook: `1.0-WinequalityEDA.ipynb`.
3. Ensure all dependencies are installed using:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
4. Run all cells for full analysis.

---

## 📬 Author

**Anuj Agarwal**  
[LinkedIn](https://www.linkedin.com/)
