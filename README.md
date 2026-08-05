# Data Science Portfolio

![Python](https://img.shields.io/badge/Python-3.12.4-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

**Dakshita Biwal**  
B.Tech Computer Science Engineering Student | Aspiring Data Scientist

[LinkedIn](https://linkedin.com/in/YOUR-LINKEDIN) • [GitHub](https://github.com/dakshita01)

---

# About This Portfolio

This repository contains **10 end-to-end data science projects** completed while studying the **Cisco Networking Academy - Data Science Essentials** course.

The projects collectively demonstrate the complete data analysis workflow-from exploratory data analysis and data cleaning to feature engineering, statistical modeling, visualization, and evidence-based storytelling.

Every project is self-contained and includes:

- A well-documented Jupyter Notebook
- The original dataset(s)
- Saved visualizations
- A detailed project-specific README
- Reproducible project structure

Rather than focusing only on producing charts or machine learning models, these projects emphasize **careful reasoning, honest interpretation, and clear communication of analytical findings.**

---

# Portfolio at a Glance

- **10** end-to-end data science projects
- **15+** real-world datasets analyzed
- **20+** professional visualizations
- **3** linear regression models
- **100%** Python
- Consistent documentation and repository structure across every project

---

# Projects

| # | Project | Focus | Key Techniques | Key Finding |
|---|---------|-------|----------------|-------------|
| **01** | [Largest Islands](01-largest-islands/) | Exploratory Data Analysis | Filtering, sorting, grouping, string operations | Greenland is approximately **14× larger** than the world's 10th-largest island. |
| **02** | [Emoji Sentiment](02-emoji-sentiment/) | Data Cleaning | Feature engineering, categorical analysis | Emoji sentiment remains largely positive after filtering low-frequency emojis. |
| **03** | [Volcanic Eruptions](03-volcanic-eruptions/) | Data Integration | Datetime parsing, table merging | Identified volcanoes with ongoing eruptions using merged datasets. |
| **04** | [Typing Speeds](04-typing-speeds/) | Statistical Reasoning | Confounding variable analysis, large-scale aggregation | Apparent typing-speed differences shrink substantially after controlling for finger count. |
| **05** | [Cooling Coffee](05-cooling-coffee/) | Data Visualization | Multi-line plots, annotations, comparative visualization | Using a lid preserves considerably more heat than insulation alone. |
| **06** | [Longest Divers](06-longest-divers/) | Comparative Analysis | Feature engineering, grouped aggregation, ranking | Cuvier's Beaked Whale recorded the longest dive in the dataset. |
| **07** | [Blood Pressure & Age](07-blood-pressure-age/) | Statistical Modeling | Linear regression, model interpretation | Blood pressure increases with age in the USA but remains nearly constant among the Yanomami population. |
| **08** | [Whale Heart Rates](08-whale-heart-rates/) | Time-Series Analysis | Datetime feature engineering, regression modeling | Longer dives are associated with higher post-dive recovery heart rates, although the sample size is small. |
| **09** | [Coral Conundrum](09-coral-conundrum/) | Evidence-Based Investigation | Data cleaning, multi-dataset analysis, competing hypotheses | Multiple mechanisms together provide a better explanation than any single hypothesis. |
| **10** | [Silent Spring](10-silent-spring/) | Historical Data Storytelling | Time-series analysis, comparative visualization, historical interpretation | Ecological evidence associated with DDT appears before widespread public attention following *Silent Spring*. |

---

# Skills Demonstrated

## Data Analysis

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Missing Value Analysis
- Feature Engineering
- GroupBy Aggregation
- Multi-table Data Integration
- Datetime Parsing
- Percentage Change Analysis

## Statistical Analysis

- Linear Regression
- Model Interpretation
- Correlation vs. Causation
- Confounding Variable Analysis
- Comparative Population Analysis
- Hypothesis Evaluation
- Sample Size Interpretation

## Data Visualization

- Line Charts
- Horizontal Bar Charts
- Scatter Plots
- Comparative Visualizations
- Multi-panel Figures
- Time-Series Visualization
- Chart Annotation
- Publication-quality Matplotlib Figures

## Python & Tools

- Python 3.12.4
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Git
- GitHub
- VS Code

---

# Portfolio Philosophy

Throughout this portfolio I intentionally avoid overstating conclusions.

Where appropriate, I distinguish between:

- Correlation and causation
- Observational evidence and experimental evidence
- Statistical evidence and speculation
- Public attention and real-world outcomes

The objective is not simply to produce attractive visualizations, but to communicate analyses that are transparent, reproducible, and supported by the available evidence.

---

# Repository Structure

```text
data-science-portfolio/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── 01-largest-islands/
├── 02-emoji-sentiment/
├── 03-volcanic-eruptions/
├── 04-typing-speeds/
├── 05-cooling-coffee/
├── 06-longest-divers/
├── 07-blood-pressure-age/
├── 08-whale-heart-rates/
├── 09-coral-conundrum/
└── 10-silent-spring/
```

Each project follows a consistent structure.

```text
0X-project-name/
│
├── README.md
├── notebook/
├── data/
├── images/
│   └── plots/
└── src/        (only included where required)
```

---

# Running the Projects

Clone the repository.

```bash
git clone https://github.com/dakshita01/data-science-portfolio.git
```

Move into the repository.

```bash
cd data-science-portfolio
```

Create and activate a virtual environment.

### Windows

```powershell
python -m venv venv
venv\Scripts\activate
```

### macOS / Linux

```bash
python -m venv venv
source venv/bin/activate
```

Install the required packages.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

Open any notebook inside its corresponding project folder.

---

# Data Sources

Most datasets used throughout this portfolio were provided through the **Cisco Networking Academy – Data Science Essentials** course and originate from publicly available scientific, historical, and governmental data sources.

Individual project READMEs include dataset-specific attribution where applicable.

---

# License

This repository is licensed under the **MIT License**.

All analyses, feature engineering, visualizations, documentation, and project organization represent my own implementation while completing the Cisco Networking Academy **Data Science Essentials** course.
