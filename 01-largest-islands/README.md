# Largest Islands in the World

**Project 1** of my **Data Science Essentials with Python** portfolio, completed as part of the **Cisco Networking Academy Data Science Essentials** course.

This project uses **Pandas** and **Matplotlib** to explore the world's 100 largest islands through structured analytical questions about geography, climate, island size, and international governance.

---

## Project Objectives

This project answers the following analytical questions:

1. Which are the ten largest tropical islands by area?
2. Which island is the largest in each geographic region?
3. How does island area decrease with global rank?
4. Which islands are governed by multiple countries?
5. Does ranking climates by island count produce the same result as ranking them by total land area?

---

## Dataset

| Property | Value |
|----------|-------|
| File | `largest-islands.csv` |
| Rows | 100 |
| Columns | 6 |
| Features | `region`, `island`, `area`, `countries`, `climate`, `rank` |
| Missing Values | 0 |
| Source | Visual Capitalist (2021), compiled from Britannica and Wikipedia |

---

## Technologies Used

- Python 3.12.4
- Pandas
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Key Findings

- The **tropics** contain the largest number of islands in the dataset, with **41** of the world's 100 largest islands located in tropical climates.

- Greenland dominates the dataset, being approximately **14× larger** than the 10th-ranked island. This creates a strong visual outlier on the linear-scale chart.

- **7** islands are governed by multiple countries, with **Borneo** shared by Indonesia, Malaysia, and Brunei.

- Climate rankings differ depending on the metric used. While the **tropics** rank first by both island count and total land area, the **temperate climate contains more islands than the polar climate (32 vs. 27)**, yet the **polar climate has a much greater total land area** because it includes exceptionally large islands such as Greenland.

- The dataset required **no preprocessing**, as it contained **zero missing values** and all columns had consistent data types.

---

## Visualization

### Island Area by Global Rank

![Area by Rank](images/plots/area_by_rank_line_chart.png)

**Linear Scale**

- Clearly highlights Greenland as an extreme outlier.

**Logarithmic Scale**

- Compresses the effect of the outlier, revealing the overall decline in island size across all 100 ranked islands.

---

## Skills Demonstrated

This project demonstrates practical experience with:

- Reading CSV datasets using Pandas
- Exploratory Data Analysis (EDA)
- Data filtering and sorting
- GroupBy aggregation
- String-based filtering
- Ranking and comparison analysis
- Data visualization using Matplotlib
- Markdown documentation
- Git version control
- GitHub project organization

---

## Project Structure

```text
01-largest-islands/
│
├── README.md
├── notebook/
│   └── largest_islands.ipynb
├── data/
│   └── largest-islands.csv
└── images/
    └── plots/
        └── area_by_rank_line_chart.png
```

---

## Installation

Clone the repository.

```bash
git clone https://github.com/dakshita01/data-science-portfolio.git
```

Move into the repository.

```bash
cd data-science-portfolio
```

Activate the virtual environment.

### Windows

```powershell
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

Install the project dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

Open:

```text
01-largest-islands/notebook/largest_islands.ipynb
```

---

## Learning Outcomes

Through this project, I strengthened my understanding of:

- Loading and inspecting structured datasets
- Selecting and filtering data using Pandas
- Aggregating data with GroupBy
- Comparing different statistical perspectives on the same dataset
- Building informative visualizations with Matplotlib
- Communicating findings through clear documentation
- Organizing a reproducible data science project using Git and GitHub

---

## License

This project is part of my personal learning portfolio created while completing the **Cisco Networking Academy Data Science Essentials** course.

The analysis and documentation are my own implementation based on the concepts learned throughout the course.