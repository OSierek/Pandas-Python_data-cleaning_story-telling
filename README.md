# Pandas-Python_data-cleaning_story-telling

The aim of this project to deal with unstructured data using Pandas and Python to transform into a useable and trustable dataset — objective: business question on discount strategy
##Data Science Portfolio: Week 2 (Pandas & Data Engineering)

### 1. Data Acquisition & Data Cleaning

- Data Import: Loading raw data from diverse sources into DataFrames.
- String Filtering & Regex: Cleaning textual data and identifying complex string patterns.
- Range & Set Filtering: Isolating specific data subsets using intervals and set memberships.

### 2. Exploratory Data Analysis & Transformation (EDA)

- Filtering: Conditional slicing and subsetting for targeted data exploration.
- Aggregation: Computing summary statistics to extract key data insights.
- Grouping: Utilizing split-apply-combine workflows for granular segment analysis.
- Joins & Merges: Executing relational data integration across multiple data sources.

### 3. Data Visualization

- Plotting: Visualizing data distributions and statistical trends directly from Pandas.

### 4. Software Engineering for Data Science

- Functions: Modularizing code to build scalable, reusable data pipelines.
- Error Handling: Building resilient workflows that gracefully handle unexpected data anomalies.
- Debugging Techniques: Systematically isolating and fixing bugs in data transformation logic.

### 5. Development Environment & Tech Stack

- Google Colab: Cloud-based prototyping and collaborative notebook development.
- Anaconda & JupyterLab: Local environment management and interactive coding.

## Featured Notebooks & Projects

- Advanced Transformations: Production-grade feature engineering and complex data manipulation.
- Metal Bands Database Analysis: End-to-end data cleaning, preprocessing, and exploratory analysis.
- Plotting Functions (Coin-Tossing Statistics): Stochastic simulation and visual analysis demonstrating the Law of Large Numbers.
- Debugging Showcase: Hands-on application of defensive programming and troubleshooting methods.

---

markdown# Pandas & Data Engineering – Project 2

Welcome to my repository for data cleaning focused on mastering data manipulation, exploratory data analysis (EDA), and production-grade software engineering practices using **Pandas**. 

The notebooks contained here demonstrate end-to-end workflows from data ingestion to advanced visualization.

## 🛠️ Tech Stack & Environments
*   **Languages:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib
*   **Environments:** Google Colab, Anaconda, JupyterLab

---

## 📚 Core Skills Covered

### 1. Data Acquisition & Cleaning
*   **Data Import:** Ingesting raw datasets into structurally sound DataFrames.
*   **Text & String Manipulation:** Using Regular Expressions (Regex) for data cleaning.
*   **Advanced Filtering:** Subsetting data using range boundaries and set memberships.

### 2. Exploratory Data Analysis (EDA) & Transformation
*   **Aggregation & Grouping:** Implementing split-apply-combine paradigms for segment analysis.
*   **Relational Operations:** Merging and joining disparate datasets to unify data sources.
*   **Conditional Slicing:** Filtering rows and columns based on multi-variable logic.

### 3. Software Engineering for Data Science
*   **Modular Programming:** Writing clean, reusable functions for data pipelines.
*   **Defensive Coding:** Implementing robust error handling to manage data anomalies.
*   **Debugging:** Applying systematic troubleshooting techniques to complex pipelines.

---

## 🚀 Featured Notebooks

Here are the highlights of my work from this week:

### 🔹 Advanced Transformations
*   **Focus:** Feature engineering and complex data manipulation.
*   **Description:** Showcases advanced Pandas techniques to transform raw inputs into model-ready features.

### 🔹 Metal Bands Database (End-to-End EDA)
*   **Focus:** Data cleaning and domain-specific exploration.
*   **Description:** A complete project analyzing a database of global metal bands. Features deep text cleaning, origin-based grouping, and statistical breakdown of genres.

### 🔹 Plotting Functions & Coin-Tossing Simulation
*   **Focus:** Data visualization and stochastics.
*   **Description:** Implements a simulation of coin-tossing to visualize statistical probabilities. Demonstrates the Law of Large Numbers through interactive Pandas plotting.

### 🔹 Debugging Showcase
*   **Focus:** Error handling and code optimization.
*   **Description:** A collection of troubleshooting scenarios, fixing broken data pipelines, and implementing defensive programming structures.

---

# Eniac Data Cleaning & Discount Analysis – Bootcamp Weeks 3 & 4

Welcome to the repository for the Eniac Capstone Project! Building upon our initial insights, this intensive two-week project focuses on processing a full year of business database records from the online Apple product and accessory retailer, **Eniac**. 

The primary business objective was to evaluate whether Eniac's aggressive discounting strategy yielded tangible business benefits. To answer this, a heavy emphasis was placed on advanced data parsing, data cleaning, and algorithmic price reconstruction.

## 🛠️ Tech Stack & Environments
*   **Languages:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
*   **Environments:** JupyterLab, Anaconda

---

## 📚 Core Skills Covered

### 1. Advanced Data Wrangling & Ingestion
*   **Relational Database Mapping:** Integrating four separate business tables (`products`, `orders`, `orderlines`, `brands`).
*   **Data Completeness & Integrity:** Validating foreign key constraints and reconstructing missing product codes directly from sales logs (`orderlines`).
*   **Funnel Segmentation:** Filtering transaction pipelines down to valid, completed orders (21% of total data) while dropping invalid shopping carts and ghost orders.

### 2. Algorithmic Data Cleaning & Anomaly Resolution
*   **Format Transformation:** Fixing corrupted floating-point strings (e.g., removing duplicate decimal dots caused by regional thousands-separator conflicts).
*   **Mathematical Price Reconstruction:** Utilizing logarithms and base-10 exponentiation to correct decimal orders of magnitude for corrupted `price` and `promo_price` attributes.
*   **Statistical Reference Heuristics:** Imputing missing or broken prices using historical minimum and maximum observed unit prices from real sales data.

### 3. Feature Engineering & Category Reconstruction
*   **NLP-Driven Categorization:** Generating per-type token frequency statistics from raw product descriptions to manually map cryptic category codes.
*   **Market Share Valuation:** Creating an optimized product-type taxonomy covering 97% of product variants and 99.7% of total sales revenue.

### 4. Exploratory Data Analysis & Strategic Presentation
*   **Correlation & Statistics:** Calculating actual discount percentages to analyze their relationship with sales volume on a weekly, per-category, and per-product level.
*   **Executive Presentation:** Translating statistical trends into a high-impact, 5-minute business presentation.

---

## 🚀 Repository Structure & Artifacts

### 🔹 [Data Exploration & Cleaning Notebook](./)
*   **Focus:** End-to-end preprocessing, data integrity checks, and mathematical price corrections.
*   **Outputs:** Generates the clean, production-ready core datasets: `products_cl`, `orders_cl`, and `orderlines_cl`.

### 🔹 [Product Categorization Notebook](./)
*   **Focus:** Word-frequency statistics and taxonomy assignment.
*   **Outputs:** Bridges missing database schemas using a custom category mapping framework. Includes the final [Type-Mapping CSV](./) and reference [Mapping Spreadsheet](./).

### 🔹 [Business Analysis & Visualization Notebook](./)
*   **Focus:** Discount effectiveness evaluation and correlation studies.
*   **Outputs:** Features sales distribution plots, weekly trend charts, and scatter plots mapping weekly sales performance against active discount tiers.

### 🔹 [Additional Exercises](./)
*   **Focus:** Skill reinforcement.
*   **Description:** A collection of side-notebooks with practice tasks completed throughout this intensive two-week phase.

---

### 👥 Collaboration Credit
This project was successfully delivered through a highly collaborative team effort. Special thanks to my talented teammates **Mathias** , **Jagan** and **Zhara** for the great teamwork!

---

## 📈 Learning Reflection
- 1. This project bridged the gap between writing simple scripts and building resilient data pipelines. Moving from basic filtering to regex-based text cleaning and relational merges allows me to handle real-world, messy datasets with high confidence.

- 2. This intensive project truly highlighted the reality of working as a Data Scientist: real-world data is messy, incomplete and highly corrupted. Moving from clean, curated business datasets to a live business database forced me to think algorithmically and apply advanced engineering strategies. 

Key takeaways from this project include:
*   **Data Cleaning as a Core Asset:** Writing mathematical correction logic (using log/exponentiation) to fix systematic database corruption proved that data cleaning is not just preparation—it requires creative and analytical problem-solving.
*   **Business Inferences from Incomplete Schemas:** When metadata was missing (like the product category codes), I learned how to engineer our own ground truth by extracting text statistics from product names to bridge schema gaps.
*   **Translating Data into Strategy:** Analyzing the direct correlation between aggressive discounts and sales performance taught me how to look past simple volume increases and evaluate true business viability. 

