EDA of Women's Dress Attributes and Sales

Project Type: Guided coursework exercise, not an independent project.

The datasets, notebook structure, and question prompts were provided as part of a course ([Course / Provider: Add Name]). This notebook contains my worked solutions to the exercises, followed by a subsequent cleanup and refinement pass.

Problem Statement

A retailer's dress catalogue consists of two datasets: a dress attributes dataset containing information such as style, price, size, season, neckline, material, rating, and recommendation status; and a sales dataset containing sales figures across multiple dates.

The objective was to clean and combine these datasets and perform exploratory data analysis (EDA) to understand sales patterns, customer ratings, and product recommendations.

Dataset and Source

Source: UCI Machine Learning Repository – Dresses_Attribute_Sales

Citation: Usman, M. & Ahmed, A. (2014).

DOI: https://doi.org/10.24432/C56W3V

License: CC BY 4.0

The notebook uses the course-provided CSV files:

Attribute+DataSet.csv

Dress+Sales.csv

Each dataset contains 479 dress records. These course-provided copies may differ from the original UCI release containing 500/501 rows.

Course-Provided Materials

The course supplied:

The two CSV datasets.

The notebook section structure.

Multiple-choice analysis prompts (paraphrased in this notebook).

Code cell hints and instructions.

My Contribution

My work included:

Implementing code and answering the exercise prompts across data cleaning, univariate, bivariate, and multivariate analysis.

Handling missing values and inconsistent data formats.

Standardising categorical variables and converting sales columns into numerical values.

Merging the dress attributes and sales datasets.

Performing exploratory analysis and interpreting the resulting patterns.

Conducting a subsequent cleanup and refinement pass, with AI assistance from Claude, including bug fixes, code consolidation, sensitivity checks, and improvements to the findings and limitations documentation.

Approach and Methodology

Data Profiling: Examined dataset structures, data types, inconsistencies, and missing values.

Data Cleaning: Standardised categorical labels and converted sales columns into numerical formats.

Seasonal Aggregation: Grouped date-based sales columns into four seasons using the mapping provided in the course.

Data Integration: Performed a left merge of the sales dataset with the dress attributes dataset.

Missing Value Treatment: Handled missing values through removal or explicit labelling, where appropriate.

Category Consolidation: Grouped infrequent categorical values into an "Others" category.

Exploratory Data Analysis: Conducted univariate, bivariate, and multivariate analysis to examine distributions, relationships, and patterns across dress attributes and sales.

Scope and Limitations

This project focuses exclusively on descriptive exploratory data analysis.

No predictive or machine learning models were developed.

No statistical significance tests were performed.

Findings describe observed patterns and associations only.

No causal relationships or conclusions about sales drivers are established.

Results are based on the course-provided dataset copies and seasonal mapping.

Change Log

The initial notebook was completed as a guided coursework exercise. A subsequent cleanup pass, assisted by Claude, included:

Bug fixes and code consolidation.

Additional sensitivity checks.

Refinement of the findings and limitations sections.

The original coursework scope and supplied materials have been retained and clearly distinguished from my subsequent contributions.
