# Mpox Data Analysis
**Overview**
This project analyzes the global mpox (monkeypox) dataset to gain insights into testing numbers, positive case ratios, and top countries affected. The data is explored and processed using various R libraries to produce summary statistics and key findings.

**Project Steps:**
1. Loading and Exploring Data: The dataset was loaded using readr and tibble to explore and understand the structure of the data.
2. Data Filtering and Selection: Relevant columns were filtered and selected using dplyr functions to focus on the necessary data points for analysis.
3. Data Aggregation by Country: The data was aggregated by country to calculate summary statistics, such as total tests conducted and positive case ratios.
4. Top Countries by Testing Numbers and Positive Cases: The analysis identified the top countries with the highest number of tests and highest positive case ratios, providing a clearer understanding of the global impact of mpox.
5. Vectors and Matrices for Key Findings: Key findings, such as the top countries and summary statistics, were stored in vectors and matrices for better data handling and analysis.
6. List Structure:The results were compiled into a comprehensive list structure, summarizing all findings in a structured manner.

**Tools and Packages Used:**
1. readr: For data loading.
2. tibble: For data exploration.
3. dplyr: For data filtering, selecting, and aggregation.
4. Base R: For creating vectors, matrices, and list structures.

**Files:**
owid-monkeypox-data.csv: The primary dataset used for analysis.
mpox_analysis.Rmd: R Markdown file containing the code for data analysis, filtering, aggregation, and summarization.

**Findings:**
Top countries by total tests conducted.
Highest positive case ratios by country.
Summary statistics across all analyzed countries.

**License**
This project is open-source and available under the MIT License.
