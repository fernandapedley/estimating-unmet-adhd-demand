# Methodology

## Navigation

* [Home](index.md)
* [Detailed Findings](findings.md)
* [Methodology](methodology.md)
* [Project Resources](resources.md)

---

## Overview

This project explored whether trends in ADHD prevalence, referrals and waiting-list activity could provide useful insight into potential unmet demand for ADHD assessment and treatment services in England.

The analysis used publicly available ADHD data published by NHS England and focused on national trends between December 2024 and December 2025. The project combined exploratory data analysis, descriptive statistics and visualisation techniques to identify patterns within the dataset.

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

Special attention was paid to ensuring that indicators were interpreted consistently across reporting periods and age groups.

---

## Exploratory Data Analysis

The exploratory analysis was completed in several stages.

First, trends in ADHD prevalence, waiting-list activity and referrals were examined over time. The analysis then explored differences between age groups to identify where growth and service pressure appeared to be concentrated.

Finally, a simple waiting-list-to-prevalence ratio was developed to explore the relationship between recorded ADHD prevalence and waiting-list activity. While this was not intended to measure unmet need directly, it provided a useful way of identifying areas where service pressure may be greatest.

Visualisations were created using Matplotlib to support interpretation of the findings.

---

## Limitations

Several limitations should be considered when interpreting the findings.

The analysis relied on routinely collected management information published by NHS England and therefore depends on the quality and completeness of the source data. Changes in reporting coverage may mean that some increases observed during the reporting period reflect improved data submission as well as genuine increases in activity.

The project focused on descriptive analysis and did not attempt to establish causal relationships between variables.

In addition, the waiting-list-to-prevalence ratio may reflect a combination of unmet demand, service backlog, referral behaviour and service capacity constraints. It should therefore be interpreted as a broad indicator of service pressure rather than a direct measure of unmet need.

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* GitHub Pages

---

## Next Page

➡ [View Detailed Findings](findings.md)
