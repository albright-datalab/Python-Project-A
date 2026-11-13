# 📊 Project Title

**Short Project Description:** Provide a brief, one- or two-sentence overview of the project, the dataset being analyzed, and the primary objective.

---

## 📌 Table of Contents

1. [Project Overview](#-project-overview)
2. [Project Impetus](#-project-impetus)
3. [Project Objectives](#-project-objectives)
4. [Dataset](#-dataset)
5. [Tools & Technologies](#-tools--technologies)
6. [Data Cleaning & Preparation](#-data-cleaning--preparation)
7. [Exploratory Data Analysis](#-exploratory-data-analysis)
8. [Key Findings](#-key-findings)
9. [Visualizations](#-visualizations)
10. [Recommendations](#-recommendations)
11. [Project Structure](#-project-structure)
12. [How to Run This Project](#-how-to-run-this-project)
13. [Limitations](#-limitations)
14. [Future Improvements](#-future-improvements)
15. [Author](#-author)

---

## 🔍 Project Overview

Describe the purpose of this project and what you are attempting to accomplish through data analysis.

**Project Goals:**
- Identify trends and patterns within the dataset.
- Analyze relationships between relevant variables.
- Generate insights through statistical analysis and visualization.
- Provide data-driven conclusions and recommendations.

## ❓ Project Impetus
It is no secret that the economic situation in our country has been getting more difficult. To better understand the economic reality the data from top 100 cities in the year f2020 will be evaluated. The intent is to gain insight and perspective to compare this historical benchmark to what is experienced today. 


## 🎯 Project Objectives

- [ ] Define the research questions.
- [ ] Obtain and evaluate the dataset.
- [ ] Clean and prepare the data.
- [ ] Perform exploratory data analysis (EDA).
- [ ] Identify trends, correlations, and outliers.
- [ ] Create visualizations and dashboards.
- [ ] Summarize findings and recommendations.

## 📂 Dataset

**Data Source:** (https://www.kaggle.com/datasets/brandonconrady/living-wage-top-100-cities)

**Dataset Description:** Living wage findings for the 100 top cities. 

**Data Characteristics:**

| Attribute | Description |
|---|---|
| Number of Records | 100 |
| Number of Columns | 19 |
| Date Range | 2020 |
| File Format | CSV |
| Source | www.Kaggle.com |

**Key Variables:**
- `Variable_1`: The Primary variable is the cost of living in USD. The original author of the dataset chose to record the value in hourly wage dollars. 
- `Variable_2`: The size of the household is a very important variable. The number of adults either 1 or 2 and whether or not the both work is accounted for. The number of children ranges from 0 to 3.
- `Variable_3`: The geographical location of the population, city and state, is included. 
- `Variable_4`: The final variable is population size and density. Information for the year 2010 is also included as another perspective point for leveraged understanding. 

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and manipulation |
| Pandas | Data cleaning and transformation |
| NumPy | Numerical analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |

*
## 🧹 Data Cleaning & Preparation

The steps taken to prepare the data for analysis are as follows:

- searched for and found no missing values.
- Searched for and found no duplicate records.
- Combed the data for inconsistent data types.
- Standardized column names and formats.
- Identified and evaluated outliers.
- Created calculated columns and derived variables.
- Validated data accuracy and consistency.
The dataset was very concise and did not contain errors or unfilled entries. 

## 📈 Exploratory Data Analysis (EDA)

Describe the analytical methods used to investigate the dataset.

**Analysis Performed:**
- Descriptive statistics.
- Distribution analysis.
- Trend analysis.
- Correlation analysis.
- Comparative analysis.
- Grouping and aggregation.
- Identification of anomalies and outliers.

**Research Questions:**
1. What was the recorded living wage found across the data set? 
2. How does the cost of living compare across the cities and states?
3. Are there patterns and correlations to be observed?
4. How does this compare the the dollar amounts for my current location in the year 2026? 

## 💡 Key Findings

There are repeating shapes in the data. Logical hypothesis are supported by the numbers. Which is to say the more kids you have the more expensive it is. 

| Finding | Description | Significance |
|---|---|---|
| Finding 1 | [Insert finding] | [Explain importance] |
| Finding 2 | [Insert finding] | [Explain importance] |
| Finding 3 | [Insert finding] | [Explain importance] |

## 📊 Visualizations

Include charts, graphs, dashboards, and other visual representations of your findings.

**Visualization 1: [Chart Title]**

![Visualization 1](images/chart_1.png)

*Description: Explain what this visualization demonstrates.*

**Visualization 2: [Chart Title]**

![Visualization 2](images/chart_2.png)

*Description: Explain the significance of this visualization.*

**Dashboard:**

[Separate plotly dashboard]

## 📝 Recommendations & Conclusions

The visualizations show that the more children in the household the greater the varience in cost. In higher cost areas like New York and California we see greater change in cost.

**Conclusions:**
- The number of working adults and the number of children are directly correlated. 
- Geographical location year are also correlated with the cost of living. 
- Cost of living is increasing and the rate of change is speeding up over time. 

**Recommendations:**
- [Recommendation 1]
- [Recommendation 2]
- If I was to run this again I would try to get data from more years and really limit the number of columns. I had been struggling with my initial data gathering because i ended up finding a dataset that ended up being 2gigabytes in size. there was alot of interesting possible information and correlations to be found but there was simply too much data, and a number of the entries like "occupation" were numeric codes instead of actual words which limited their usefulness due to lack of interpretability. I also am not happy with the originator's source for the data. I used the MIT cost of living calculator for my "current day" comparison data and the author only lists their source as Wikipedia.
- I think there is a likelihood of preconcieved biases between me and the data. I do feel that the facts are such that the conclusions are not in question but it would be good to work with arms length datasets in the future.

## 📁 Project Structure

```text
project-name/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── exploratory_analysis.ipynb
│
├── scripts/
│   └── data_cleaning.py
│
├── images/
│   ├── chart_1.png
│   └── chart_2.png
│
├── reports/
│   └── findings.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 How to Run This Project

**1. Clone the repository**

```bash
git clone https://github.com/username/project-name.git
```

**2. Navigate to the project directory**

```bash
cd project-name
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the analysis**

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Follow the instructions within the notebook to reproduce the analysis.

## ⚠️ Limitations

Document any limitations that may affect the interpretation of your findings.

- Data availability or completeness.
- Potential sampling bias.
- Assumptions made during analysis.
- Limitations of the analytical methods.
- Data collection or reporting inconsistencies.

## 🔮 Future Improvements

Identify opportunities to expand or improve the project.

- Incorporate additional datasets. 
- Automate data collection and cleaning.
- Develop predictive models.
- Build interactive dashboards.
- Expand the analysis to additional time periods.
- Improve statistical testing and validation.

## 👨‍💻 Author

**Adam Albright**

Data Analytics Student | Aspiring Data Analyst

- GitHub: [@username](https://github.com/username)
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/)

---

## 📜 License

This project is available under the [MIT License](LICENSE).

---

*If you found this project useful, feel free to ⭐ star the repository!*



# Living Wage 2020 Data Exploration
Python Fundementals Exploration Project

Initial Dataset is based around the living wage values

https://www.kaggle.com/datasets/brandonconrady/living-wage-top-100-cities
