# 📊 Data Analytics Project

## 1. Overview

This project demonstrates an end-to-end data analytics workflow, starting from raw data preparation to generating actionable business insights through data visualization and reporting.

The project focuses on exploring, cleaning, analyzing, and visualizing data using Python, PostgreSQL, and Power BI. The final results are presented in an interactive dashboard, a comprehensive analytical report, and a presentation created with NotebookLM.

**Project Objectives:**
- Understand the dataset through Exploratory Data Analysis (EDA).
- Clean and prepare raw data for accurate analysis.
- Perform data analysis using SQL queries in PostgreSQL.
- Identify trends, patterns, and meaningful insights.
- Develop an interactive Power BI dashboard.
- Communicate findings through a report and presentation.

## 2. Dataset

The dataset used in this project contains **[briefly describe your dataset and its subject]**.

It was used as the primary data source throughout the analytical process.

**Dataset Information:**
- **Source:** https://drive.google.com/file/d/1LDM_yA8lx5RBsgXFjknYezhrVwUzNVNM/view?usp=drive_link
- **Format:** CSV / Excel

## 3. Tools & Technologies

The following tools and technologies were used throughout the project:

| Tool | Purpose |
|---|---|
| Python | Data loading, cleaning, and EDA |
| Pandas & NumPy | Data manipulation and processing |
| Matplotlib & Seaborn | Exploratory data visualization |
| PostgreSQL | Database management and SQL analysis |
| SQL | Data querying and insight extraction |
| Power BI | Interactive dashboard development |
| Jupyter Notebook | Data analysis environment |
| NotebookLM | Report and presentation preparation |

## 4. Project Workflow

The project was completed through the following stages:

### Step 1: Data Loading
- Imported the raw dataset into Python using Pandas.
- Inspected the dataset structure, dimensions, and data types.
- Reviewed initial records to understand the available information.

### Step 2: Exploratory Data Analysis (EDA)
- Analyzed descriptive statistics and data distributions.
- Identified patterns, trends, and potential anomalies.
- Explored relationships between variables using visualizations.

### Step 3: Data Cleaning
- Handled missing and duplicate values.
- Corrected inconsistent data types and formatting.
- Identified and addressed data quality issues.
- Prepared a clean dataset for further analysis.

### Step 4: SQL Analysis with PostgreSQL
- Loaded the cleaned dataset into PostgreSQL.
- Executed SQL queries to explore and analyze the data.
- Used aggregations, filtering, grouping, and joins where applicable.
- Extracted key metrics and business insights.

### Step 5: Power BI Dashboard
- Connected the analyzed data to Power BI.
- Created visualizations to highlight important findings.
- Designed an interactive dashboard with relevant KPIs and filters.
- Presented key trends and insights in an easy-to-understand format.

### Step 6: Reporting & Presentation
- Summarized the analytical findings into a structured report.
- Used NotebookLM to organize the project findings and create a presentation.
- Communicated the key insights and recommendations in a clear and concise format.

## 5. Dashboard Preview

The Power BI dashboard provides an interactive overview of the analysis, allowing users to explore key metrics, trends, and patterns.

**Dashboard Highlights:**
- Key Performance Indicators (KPIs)
- Trend and performance analysis
- Category-based comparisons
- Interactive filters and visualizations
- Key findings to support data-driven decisions

**Dashboard Preview:**

<img width="3075" height="1763" alt="Customer Behavior Dashboard pdf_page-0001" src="https://github.com/user-attachments/assets/7a0a6bb5-7409-4ab3-8c61-3b95ec5e459f" />


## 6. Key Results & Insights

The analysis generated several findings from the dataset, including:

- **Key Finding 1:** [Describe the most important insight.]
- **Key Finding 2:** [Highlight a significant trend or pattern.]
- **Key Finding 3:** [Explain an interesting comparison or discovery.]
- **Business Implication:** [Describe how the findings can support better decision-making.]

The project demonstrates how raw data can be transformed into meaningful insights through a structured analytical workflow.

## 7. Project Structure

```text
data-analytics-project/
│
├── dataset/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── dashboard.pbix
│
├── reports/
│   └── analysis_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
└── README.md
```

## 8. How to Run

Follow these steps to reproduce the analysis:

**1. Clone the repository**

```bash
git clone https://github.com/yourusername/data-analytics-project.git
cd data-analytics-project
```

**2. Install the required Python libraries**

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
```

**3. Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open the notebook in the `notebooks/` folder and execute the cells sequentially.

**4. Set up PostgreSQL**

- Create a PostgreSQL database.
- Import the cleaned dataset.
- Configure the database connection.
- Execute the SQL queries provided in the `sql/` folder.

**5. Open the Power BI Dashboard**

Open the `.pbix` file in Power BI Desktop and configure the data source if necessary.

**6. Review the Final Deliverables**

Explore the analytical report and project presentation in their respective folders.

## 9. Author

**Ahmad Fauzi Ardiansyah**

Aspiring Data Analyst | Interested in Data Analytics, SQL, Python, and Business Intelligence.

- **GitHub:** fauziarcsy
- **LinkedIn:** linkedin.com/in/ahmadfauziardi
- **Email:** fauziarcsy@gmail.com

---

*This project was developed to demonstrate practical data analytics skills, including data preparation, exploratory analysis, SQL querying, dashboard development, and data storytelling.*
