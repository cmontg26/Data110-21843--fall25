# Week 4 Assinment: Crime Data Visualization (2022-2023)

In this assignment, we will analyze real-world crime data from 2022 to 2023, sourced from the **FBI's Crime Data** as reported by the Brennan Center. According to the Brennan Center’s analysis, most crimes, including murder, have seen significant drops in 2023.

Source: [FBI Data Confirms Drop in Most Crimes in 2023, Especially Murders](https://www.brennancenter.org/our-work/analysis-opinion/fbi-data-confirms-drop-most-crimes-2023-especially-murders)

## Dataset

| **Offense**                  | **Offenses per 100,000 People (2023)** | **Change in Offenses per 100,000 People (2022-2023)** |
|------------------------------|----------------------------------------|-------------------------------------------------------|
| Aggravated Assault            | 264.1                                  | -3.3                                                  |
| Burglary                      | 250.7                                  | -8.1                                                  |
| Larceny                       | 1,347.2                                | -4.9                                                  |
| Motor Vehicle Theft           | 318.7                                  | +12.0                                                 |
| Murder                        | 5.7                                    | -12.0                                                 |
| Rape (revised definition)     | 38.0                                   | -9.8                                                  |
| Robbery                       | 66.5                                   | -0.8                                                  |

---

## Task 1: Basic Bar Chart for Crime Rates in 2023

In this task, you will create a **bar chart** showing the offense rates per 100,000 people for each type of crime in 2023.

### Instructions:
- Create a bar chart for crime rates in 2023.
- Customize the bar colors and add gridlines.
- Label the axes and add a title.

---

## Task 2: Change in Crime Rates (2022 vs. 2023) with Unique Colors

In this task, you will create a **horizontal bar chart** that visualizes the **percentage change** in offense rates from 2022 to 2023 for each crime type. Each bar should have a unique color for better distinction.

### Instructions:
- Create a horizontal bar chart showing the **change in offense rates**.
- Assign a unique color to each crime type.
- Label the axes and add a title.

### Additional Instructions:
1. **Why does this bar graph make more sense than Task 1's bar graph?**
   - Think about how **absolute numbers** (like total crime rates) might be misleading compared to **percentage changes**.
   - Explain why seeing the **change** over time is more insightful than just seeing the total number of offenses for a single year.
   
2. **Improve the clarity of your bar graph**:
   - Create **multiple versions** of the bar chart for Task 2, each time making the chart more **clear and readable**.
   - Experiment with different color schemes, labels, and gridlines.
   - In each iteration, focus on improving the ease with which someone can quickly understand the trends in crime rates.

---

## Task 3: Multi-Series (Grouped) Bar Chart with Fake Data

In this task, you will practice making a **multi-series grouped bar chart** using a simple, fake dataset.  
Imagine three companies (**Company A, Company B, Company C**) that each sell three products (**Product 1, Product 2, Product 3**).

### Instructions:
- Create a dataset with sales values for each company’s three products.
- Plot a grouped bar chart with **3 bars per company** (Product 1, Product 2, Product 3).
- Add labels, a title, and a legend.

💡 Example structure for your dataset:
```python
companies = ["Company A", "Company B", "Company C"]
product1 = [20, 34, 30]
product2 = [25, 32, 34]
product3 = [30, 35, 27]
