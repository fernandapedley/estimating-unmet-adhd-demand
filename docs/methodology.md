# Methodology

<p align="center">

<a href="index.html"><b>Home</b></a>

<a href="findings.html"><b>Detailed Findings</b></a>

<a href="visualisations.html"><b>Visualisations</b></a>

<a href="methodology.html"><b>Methodology</b></a>

<a href="resources.html"><b>Resources</b></a>

</p>

---

## Overview

This project explored whether trends in ADHD prevalence, referrals and waiting-list activity could provide useful insight into where service pressure may be greatest and where potential unmet demand may exist.

The analysis used publicly available ADHD data published by NHS England and focused on national trends between December 2024 and December 2025.

The project combined exploratory data analysis, descriptive statistics and data visualisation techniques to identify patterns within the dataset.

---

## Analytical Approach

The analysis followed a structured three-stage approach:

### Stage 1: Trend Analysis

Overall trends in ADHD prevalence, waiting-list activity and referrals were examined across the reporting period to understand how ADHD service demand changed over time.

### Stage 2: Age Group Analysis

The data was analysed by age group to explore whether patterns differed across different parts of the population and to identify where growth and service pressure appeared to be concentrated.

### Stage 3: Proxy Indicator Development

A simple waiting-list-to-prevalence ratio was developed to explore the relationship between recorded ADHD prevalence and waiting-list activity.

While this was not intended to measure unmet need directly, it provided a useful way of comparing relative service pressure across age groups.

---

## Data Sources

The main dataset used in this project was the NHS England ADHD dataset published through the Neurodevelopmental Data Hub.

The analysis focused on four key indicators:

* ADHD prevalence
* Waiting-list activity
* Open referrals
* New referrals

The dataset was analysed at England level and across the following age groups:

* 0–4 years
* 5–17 years
* 18–24 years
* 25+ years

Supporting NHS England documentation, including the ADHD Data Improvement Plan and NHS England data dictionary, was reviewed to better understand how indicators were defined, collected and reported.

---

## Data Preparation and Cleaning

Several data preparation steps were completed before analysis began.

These included:

* Importing and reviewing raw data files
* Simplifying column names
* Removing unnecessary fields
* Filtering records to England-level data
* Converting date fields into a consistent monthly format
* Reshaping data to support time-series analysis
* Creating summary tables for analysis and visualisation

Records containing suppressed values were treated as missing and excluded from calculations where they could affect results.

Basic data quality checks were completed throughout the process, including reviews of missing values, duplicate records and unusual changes between reporting periods.

Particular attention was given to reporting periods where changes in data coverage may have influenced results, including review of NHS England documentation relating to the ADHD Data Improvement Plan.

---

## Exploratory Data Analysis

The exploratory analysis was completed in several stages.

First, trends in ADHD prevalence, waiting-list activity and referrals were examined over time.

Second, age-group comparisons were completed to identify where increases in prevalence, referrals and waiting-list activity appeared to be concentrated.

Finally, a waiting-list-to-prevalence ratio was developed to explore the relationship between recorded ADHD prevalence and waiting-list demand.

The analysis was primarily descriptive and focused on identifying patterns and trends within the data rather than establishing causal relationships.

Visualisations were created using Matplotlib to support interpretation of the findings.

---

## Limitations

Several limitations should be considered when interpreting the findings.

The analysis relied on routinely collected management information published by NHS England and therefore depends on the quality and completeness of the source data. Changes in reporting coverage may mean that some increases observed during the reporting period reflect improved data submission as well as genuine increases in activity.

This is particularly relevant when interpreting the notable increase observed between January and February 2025.

The project uses aggregate national data and does not include individual patient records. As a result, it was not possible to explore patient-level factors or understand the experiences of individual people within ADHD pathways.

The waiting-list-to-prevalence ratio was used as a proxy measure of service pressure. While it provided useful insight into relative demand, it should not be interpreted as a direct measure of unmet need.

The ratio may reflect a combination of unmet demand, service backlog, referral behaviour, diagnostic capacity, service capacity constraints and reporting practices.

Finally, the analysis covered a relatively short reporting period and focused primarily on age-group differences. Other potentially important factors, including ethnicity, sex, deprivation and geographical variation, were outside the scope of this project and may provide useful areas for future investigation.

---

## Tools and Technologies

The project was completed using:

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* GitHub Pages
* Markdown

---

## Next Step

For a detailed discussion of the results and interpretation of the findings, please visit the **Detailed Findings** page.
