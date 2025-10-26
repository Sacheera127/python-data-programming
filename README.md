# World War II Statistics - Data Analysis Assignment

## Overview
This project analyzes a simplified dataset of **World War II statistics** for different countries, covering various fronts and years between **1939 and 1945**.  
The dataset includes numerical and categorical columns related to:
- Military strength  
- Casualties  
- Spending  
- Allied support levels  

The analysis uses **Pandas** for data manipulation and **Matplotlib** for visualization.

---

## 📊 Analytical Questions (using Pandas)

1. **Find the total number of records (rows) and columns** in the dataset.  
2. **Calculate the average number of soldiers deployed** across all records.  
3. **Identify which country recorded the highest number of casualties overall.**  
4. **Find the mean and standard deviation** of the `Victory_Rate` column.  
5. **Determine the total military spending** by each country throughout the war period.

---

## 📈 Visualization Questions (using Matplotlib)

### 6. Histogram of `Victory_Rate`
Visualizes the distribution of victory rates.  
> The most frequent victory rate values are between **15 and 20**.






---

### 7. Bar Chart of Total Casualties per Country
Compares total casualties across countries.  
> **Italy** and **UK** have the highest casualties, while **Japan** has the lowest.

---

### 8. Scatter Plot: `Soldiers_Deployed` vs `Casualties`
Explores the relationship between deployed soldiers and casualties.  
> As deployment numbers increase, casualty figures also rise, showing an upward trend with some variability.

---

### 9. Bar Chart: Average `Allied_Support_Index` per Country
Compares the average level of Allied support among countries.  
> **USA** and **UK** show higher Allied support, while **Germany** and **Japan** show lower values.

---

### 10. Line Graph: Average `Military_Spending_USD_Million` per Year
Shows the trend of average military spending from 1939 to 1945.  
> Spending increases sharply around **1942**, peaking during major war years, and declines after **1943** as the war intensity decreases.

---

## 🧰 Tools & Libraries Used
- **Python 3.x**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook** or any IDE supporting Python data analysis

---

### 📂 Project Structure
 WWII_Statistics/
│
├── data/
│ └── wwii_dataset.csv
│
├── analysis/
│ └── wwii_analysis.ipynb
│
├── visuals/
│ ├── victory_rate_histogram.png
│ ├── casualties_bar_chart.png
│ ├── soldiers_vs_casualties.png
│ ├── allied_support_index.png
│ └── military_spending_trend.png
│
└── README.md

---

## 🧠 Insights
- Casualties generally increased with more troop deployments.
- Allied support varied greatly by country, highlighting global divisions.
- Military spending peaked around 1942–1943, aligning with historical escalation periods.

---

## ✍️ Author
Prepared by: **[sacheera127]**  
Course: *Data Analysis Assignment*

# World War II Statistics - Data Analysis Assignment
# Displaying README content using Python

def display_readme():
    print("=" * 70)
    print("🌍  World War II Statistics - Data Analysis Assignment")
    print("=" * 70)

    print("\n Overview")
    print("This project analyzes a simplified dataset of World War II statistics")
    print("for different countries between 1939 and 1945.")
    print("It includes data on:")
    print("  - Military strength")
    print("  - Casualties")
    print("  - Spending")
    print("  - Allied support levels")
    print("Libraries used: Pandas for data manipulation, Matplotlib for visualization.")

    print("\n Analytical Questions")
    print("  1. Total number of records (rows) and columns in the dataset.")
    print("  2. Average number of soldiers deployed.")
    print("  3. Country with the highest number of casualties.")
    print("  4. Mean and standard deviation of Victory Rate.")
    print("  5. Total military spending by each country.")

    print("\n Visualization Questions")
    print("  6. Histogram of Victory Rate")
    print("     ➤ Most frequent values: 15–20")
    print("  7. Bar Chart of Total Casualties per Country")
    print("     ➤ Italy and UK highest; Japan lowest")
    print("  8. Scatter Plot: Soldiers Deployed vs Casualties")
    print("     ➤ Upward trend with variability")
    print("  9. Bar Chart: Average Allied Support Index per Country")
    print("     ➤ USA and UK high; Germany and Japan low")
    print(" 10. Line Graph: Avg Military Spending per Year (1939–1945)")
    print("     ➤ Peak around 1942–1943; decline after 1943")

    print("\n Tools & Libraries Used")
    print("  - Python 3.x")
    print("  - Pandas")
    print("  - Matplotlib")
    print("  - Jupyter Notebook or any Python IDE")

    print("\n Project Structure")
    print("  WWII_Statistics/")
    print("  ├── data/")
    print("  │   └── wwii_dataset.csv")
    print("  ├── analysis/")
    print("  │   └── wwii_analysis.ipynb")
    print("  ├── visuals/")
    print("  │   ├── victory_rate_histogram.png")
    print("  │   ├── casualties_bar_chart.png")
    print("  │   ├── soldiers_vs_casualties.png")
    print("  │   ├── allied_support_index.png")
    print("  │   └── military_spending_trend.png")
    print("  └── README.md")

    print("\n Insights")
    print("  - Casualties increased with troop deployments.")
    print("  - Allied support varied by country.")
    print("  - Military spending peaked around 1942–1943.")

    print("\n Author")
    print("  Prepared by: sacheera127")
    print("  Course: Data Analysis Assignment")
    print("=" * 70)

# Run the function
display_readme()
