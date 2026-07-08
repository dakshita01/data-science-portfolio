# Longest Divers Analysis

**Project 6** of my **Data Science Portfolio**, developed while completing the **Cisco Networking Academy Data Science Essentials** course.

This project focuses on **data visualization, feature engineering, grouped aggregation, and comparative analysis** using a marine animal diving dataset. The objective is to compare dive durations across species and animal categories while demonstrating effective visualization techniques for communicating rankings and group comparisons.

---

## Project Objectives

This project answers the following analytical questions:

1. Which marine animals have the longest recorded dive durations?
2. How do the longest animal dives compare to the human breath-hold record?
3. How does average dive duration differ across animal categories?
4. Which animal category shows the greatest variation in dive duration?

---

## Dataset

| Property | Value |
|----------|-------|
| File | `longest-diving-animals.csv` |
| Rows | 108 |
| Columns | 4 |
| Features | `animal`, `category`, `duration`, `source` |
| Missing Values | None |
| Source | Longest Diving Animals Dataset |

---

## Technologies Used

- Python 3.12.4
- Pandas
- Matplotlib
- Jupyter Notebook
- Git & GitHub

---

## Data Preprocessing

The dataset required minimal preprocessing before analysis.

The following steps were performed:

- Verified the dataset structure and confirmed there were no missing values.
- Created a new `duration_hours` feature for easier interpretation of long dive durations.
- Calculated category-level summary statistics using groupby aggregation.
- Computed the range of dive durations within each category after excluding single-species groups.

---

## Key Findings

- **Cuvier's Beaked Whale** recorded the longest dive in the dataset at **222 minutes (3.7 hours)**.

- **Toothed whales** appear most frequently among the **15 longest-diving species**, highlighting their exceptional diving ability.

- **Turtles** and **walruses** have the highest average dive durations by category, although each category contains only a single species and should therefore be interpreted cautiously.

- **Toothed whales** exhibited the greatest variation in dive duration among categories represented by multiple species.

- The dataset required minimal preprocessing, with no missing values and only one derived feature (`duration_hours`) created to improve interpretability.

---

## Visualizations

### Top 15 Longest Divers

![Top 15 Longest Divers](images/plots/top15_longest_divers.png)

Ranks the fifteen longest-diving marine animals and includes the human breath-hold record as a reference line for comparison.

---

### Average Dive Duration by Category

![Average Dive Duration by Category](images/plots/avg_duration_by_category.png)

Compares average dive duration across animal categories while displaying the number of species contributing to each average.

---

## Skills Demonstrated

This project demonstrates practical experience with:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- GroupBy aggregation
- Comparative Analysis
- Ranking and Sorting
- Horizontal Bar Charts
- Plot Annotation
- Comparative Visualization
- Pandas DataFrame manipulation
- Matplotlib customization
- Data storytelling
- Markdown documentation
- Git version control
- GitHub project organization

---

## Project Structure

```text
06-longest-divers/
│
├── README.md
├── notebook/
│   └── longest_divers.ipynb
├── data/
│   └── longest-diving-animals.csv
└── images/
    └── plots/
        ├── top15_longest_divers.png
        └── avg_duration_by_category.png
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
06-longest-divers/notebook/longest_divers.ipynb
```

---

## Learning Outcomes

Through this project, I strengthened my understanding of:

- Designing ranking visualizations using horizontal bar charts
- Creating derived features to improve data interpretation
- Summarizing grouped data with Pandas
- Comparing categories using aggregated statistics
- Annotating charts to provide additional context
- Communicating analytical findings through effective visualizations
- Organizing reproducible data science projects using Git and GitHub

---

## License

This project is part of my personal learning portfolio developed while completing the **Cisco Networking Academy Data Science Essentials** course.

The analysis, feature engineering, visualizations, and documentation are my own implementation based on the concepts learned throughout the course.