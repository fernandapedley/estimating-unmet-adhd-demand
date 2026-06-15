# Methodology

<p align="center">

<a href="index.md"><b>Home</b></a>

   |   

<a href="findings.md"><b>Detailed Findings</b></a>

   |   

<a href="visualisations.md"><b>Visualisations</b></a>

   |   

<a href="methodology.md"><b>Methodology</b></a>

   |   

<a href="resources.md"><b>Resources</b></a>

</p>

---

## Overview

This project explored whether trends in ADHD prevalence, referrals and waiting-list activity could provide useful insight into potential unmet demand for ADHD assessment and treatment services in England.

The analysis used publicly available ADHD data published by NHS England and focused on national trends between December 2024 and December 2025. The project combined exploratory data analysis, descriptive statistics and data visualisation techniques to identify patterns within the dataset.

---

## Analytical Approach

The project followed a structured analytical process:

```text
NHS England ADHD Dataset
            ↓
      Data Preparation
            ↓
 Exploratory Data Analysis
            ↓
   Age Group Comparison
            ↓
 Proxy Indicator Development
            ↓
 Findings and Recommendations
```

This approach was designed to move from understanding the underlying data to identifying patterns that may provide useful insight into service demand and potential unmet need.

---

## Data Sources

The primary data source was the NHS England Neurodevelopmental Data Hub (NDH), which publishes monthly ADHD management information for England.

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

Additional background information was obtained from NHS England publications, including documentation relating to the ADHD Data Improvement Plan.

---

## Data Preparation

Data preparation and cleaning were completed using Python and the Pandas library.

The process included:

* Importing and reviewing raw data files
* Filtering records to England-level data
* Removing incomplete reporting periods
* Converting date fields into a consistent monthly format
* Renaming indicators to improve readability
* Creating summary tables for analysis and visualisation

Particular attention was given to data quality and consistency across reporting periods. This included reviewing potential changes in reporting coverage and ensuring that indicators were interpreted consistently across age groups and reporting periods.

---

## Exploratory Data Analysis

The exploratory analysis was completed in several stages.

First, trends in ADHD prevalence, waiting-list activity and referrals were examined over time. The analysis then explored differences between age groups to identify where growth and service pressure appeared to be concentrated.

Finally, a simple waiting-list-to-prevalence ratio was developed to explore the relationship between recorded ADHD prevalence and waiting-list activity.

While this was not intended to measure unmet need directly, it provided a useful way of identifying areas where service pressure may be greatest and helped support comparison between age groups.

Visualisations were created using Matplotlib to support interpretation of the findings.

---

## Limitations

Several limitations should be considered when interpreting the findings.

The analysis relied on routinely collected management information published by NHS England and therefore depends on the quality and completeness of the source data. Changes in reporting coverage may mean that some increases observed during the reporting period reflect improved data submission as well as genuine increases in activity.

This is particularly relevant when interpreting the notable increase observed between January and February 2025.

The project focused on descriptive analysis and did not attempt to establish causal relationships between variables.

In addition, the waiting-list-to-prevalence ratio may reflect a combination of unmet demand, service backlog, referral behaviour, diagnostic capacity, service capacity constraints and reporting practices. It should therefore be interpreted as a broad indicator of service pressure rather than a direct measure of unmet need.

Finally, the analysis focused primarily on trends over time and differences between age groups. Other potentially important factors, including ethnicity, sex, deprivation and geographical variation, were outside the scope of this project and may provide useful areas for future investigation.

---

## Tools and Technologies

The project was completed using:

* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* GitHub Pages
* Markdown

---

## Next Step

[View Detailed Findings](findings.md)
