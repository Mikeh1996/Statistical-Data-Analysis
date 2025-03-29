# Statistical Data Analysis
## Inspiration
This project is my first experience using statistics to gain meaningful insights from real-world data. My goal was to apply statistical thinking and Python tools to analyze customer behavior, identify trends, and evaluate which telecom plan performs better financially. This project marks a milestone in my progress with statistical analysis and programming logic.

## Problem Statement
Megaline is a telecom operator offering two prepaid plans, Surf and Ultimate. The commercial department wants to know which plan generates more revenue so they can adjust their advertising strategy. This project focuses on:

* Cleaning and preparing Megaline datasets for analysis

* Calculating revenue from calls, messages, and internet usage

* Using statistical methods to analyze user behavior

* Comparing Surf and Ultimate plans in terms of revenue and usage trends

* Visualizing findings with charts and summary statistics

Key questions I explored:

* Are there any duplicate or missing rows in the data?

* How does customer behavior vary between plans?

* Which plan is more profitable overall?

* Are there specific trends based on region, month, or customer type?

## What I Learned from This Project
I practiced using pandas, numpy, matplotlib, math, and scipy to process and analyze multiple datasets. Specifically, I learned how to:

* Load, inspect, and clean data from CSV files

* Identify and remove duplicates and handle missing values

* Merge and transform datasets for analysis

* Calculate monthly revenue based on plan logic (rounded calls and data)

* Apply statistical methods to compare usage patterns

* Create informative visualizations to support analysis

This project helped me understand how statistics and programming can work together to generate actionable business insights.

## Project Execution
### Setting Up the Environment
To run this project, install the following Python packages:

sh
Copy
Edit
pip install pandas numpy matplotlib scipy math

### Data Collection
This project uses five CSV files provided by Megaline:

* megaline_calls.csv

* megaline_internet.csv

* megaline_messages.csv

* megaline_plans.csv

* megaline_users.csv

Each dataset was examined for completeness and consistency before merging them for full analysis.

### Analysis Overview
* Removed duplicate rows and verified data integrity

* Explored usage data for calls, messages, and internet

* Applied plan-specific rules to calculate user revenue

* Compared revenue between Surf and Ultimate users

* Visualized findings with histograms, bar charts, and summary stats

* Used t-tests and other statistical tools for comparisons

## How to Run the Project Locally
#### Clone the repository

sh
Copy
Edit
git clone https://github.com/YOUR-USERNAME/Statistical-Data-Analysis.git
cd Statistical-Data-Analysis
Set up a virtual environment and install dependencies

sh
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
Open the Jupyter Notebook

sh
Copy
Edit
jupyter notebook Statistical_Data_Analysis.ipynb