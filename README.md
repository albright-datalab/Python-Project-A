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

There are repeating shapes in the data. Logical hypothesis are supported by the numbers. Which is to say the more kids you have the more expensive it is. Unfortunately the data does not include the hard numbers but we can infer some information from the data. The MIT living wage calculator includes the following definition of how they calculate the figure. 
"What typical expenses are included in the Living Wage Calculator’s estimates?
The Living Wage Calculator’s estimate of living wage includes eight typical expenses or basic needs—childcare, civic engagement, food, health care, housing, internet and mobile, transportation, and other necessities. In addition to these basic needs, the Calculator also accounts for income and payroll tax costs for each family."  One of the necessities that is going to have a large impact is child supervision.  Daycare costs have ballooned and we can see that the the Min and Max dollar values from the data support this inferance. the lowest living wage in the data set falls within the category of 2 working adults with no kids. The max is, no surprise, on adult 3 kids in the state of California. In fact the "living wage" for that household calculated for six years ago was nearly 170 thousand dollars after multiplying the hourly number by 40 hours per week, and 52 weeks per year. 

| Statistic | Population (2020) | Living Wage ($/hr) | Salary ($/yr) |
|:---|---:|---:|---:|
| Count | 1,200 | 1,200 | 1,200 |
| Mean | 650,040 | 28.99 | 60,302.84 |
| Standard Deviation | 978,037.90 | 12.14 | 25,258.27 |
| Minimum | 226,610 | 10.15 | 21,112.00 |
| 25th Percentile | 282,216.80 | 20.01 | 41,615.60 |
| Median (50th Percentile) | 390,263.50 | 28.35 | 58,957.60 |
| 75th Percentile | 644,553 | 35.40 | 73,632.00 |
| Maximum | 8,804,190 | 81.63 | 169,790.40 |

	population_2020	living_wage	salary
count	1.200000e+03	1200.000000	1200.00000
mean	6.500400e+05	28.991750	60302.84000
std	9.780379e+05	12.143399	25258.27083
min	2.266100e+05	10.150000	21112.00000
25%	2.822168e+05	20.007500	41615.60000
50%	3.902635e+05	28.345000	58957.60000
75%	6.445530e+05	35.400000	73632.00000
max	8.804190e+06	81.630000	169790.40000

| Finding | Description | Significance |
|---|---|---|
| Finding 1 | [Insert finding] | [Explain importance] |
| Finding 2 | [Insert finding] | [Explain importance] |
| Finding 3 | [Insert finding] | [Explain importance] |

## 📊 Visualizations

Include charts, graphs, dashboards, and other visual representations of your findings.

**Visualization 1: household composition and state **

![Visualization 1](images/chart_1.png)
<img width="989" height="2990" alt="Household size, cost and state multiplot" src="https://github.com/user-attachments/assets/1e37a5c7-7154-427a-80d1-36c041f781f4" />

*Description: There are 3 breakdowns based on the adult composition: single parent, 2 parents (one working), and 2 working parents. We can see each of the 3 groupings share a similar shape but the shape spreads out creating greater variance as the number of children increases.ffff*

**Visualization 2: [Chart Title]**

![Visualization 2](images/chart_2.png)

*Description: Explain the significance of this visualization.*

**Dashboard:**

[Separate plotly dashboard or collab here]

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
- Build interactive dashboards. Plotly allows for interactivity and would make for more effective comparisons of the data side by side. 
- Expand the analysis to additional time periods. It would be interesting to include more historical benchmarks as well being able to analyze the increased change over the last few years. 
- Include additional monetary benchmarks for the data. For example average and median home cost for the area, average and median income in the area. This specifically might lead to interesting results. It would allow for comparisons of cost of living and actual wages. Home prices are a part of the cost of living but again it can be useful to see the data on its own and compare the amount of correlation between the entries. f
- Improve statistical testing and validation. Especially the source of the data, as previously mentioned. 
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
