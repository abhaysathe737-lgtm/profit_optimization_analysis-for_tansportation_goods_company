Financial Performance Analysis and AI Optimization Strategies

Overview

This project analyzes the financial performance of a transportation goods company from 2015 to 2025, focusing on revenue, costs, segment performance, and profitability. The analysis identifies key challenges such as high purchase costs, profitability volatility, and data gaps, and proposes AI-driven strategies to optimize profits and minimize costs. The dataset is sourced from an Excel file (data (version 1).xlsb (1).xlsx), and the analysis is performed using Python scripts (code.py). This README provides an overview of the project structure, setup instructions, and key components.

Project Structure





Documentation (1).docx: Contains the executive summary of the financial performance analysis, key findings, problem statement, and AI-driven recommendations.



data (version 1).xlsb (1).xlsx: The dataset with quarterly financial metrics (e.g., Net Sales, Total Expenditure, PBT, Segment Revenue) from Q2 2015 to Q1 2025.



code.py: Python script performing data loading, exploratory data analysis (EDA), segment analysis, cost analysis, profitability analysis, correlation analysis, problem statement formulation, and visualization generation.



README.md: This file, providing an overview and instructions for the project.

Setup Instructions

Prerequisites





Python 3.8 or higher



Required Python libraries:





pandas



matplotlib



seaborn



Optional: Jupyter Notebook for interactive execution of code.py

Installation





Clone the Repository:

git clone <repository-url>
cd <repository-directory>



Install Dependencies:

pip install pandas matplotlib seaborn



Prepare the Dataset:





Ensure the dataset (data (version 1).xlsb (1).xlsx) is converted to CSV format (data.csv) for compatibility with the Python script.



Place data.csv in the same directory as code.py.



Run the Analysis:

python code.py

Alternatively, open code.py in a Jupyter Notebook and execute the cells sequentially.

Key Components

1. Data Analysis

The Python script (code.py) performs the following steps:





Data Loading and Inspection: Loads the dataset, checks structure, and identifies missing values (e.g., Shares segment data from Q3 2024 onward).



Exploratory Data Analysis (EDA): Analyzes trends in Net Sales, Total Expenditure, PBT, and PAT, identifying revenue growth and Q3 profitability weaknesses.



Segment Analysis: Compares Tankers and Shares segments, confirming Tankers' dominance (>83% of revenue and profit).



Cost Analysis: Identifies Purchase Operating Expenses as the primary cost driver (~87% of total expenditure) with high volatility.



Profitability Analysis: Highlights volatile profitability with significant losses (e.g., -167.12 in Q1 2020) and peaks (e.g., 144.02 in Q3 2023).



Correlation Analysis: Reveals a strong sales-expenditure correlation (0.997) but weak sales-profit correlation (0.14), indicating cost inefficiencies.



Problem Statement: Summarizes challenges, including high purchase costs, Q3 losses, weak revenue-profit linkage, and data gaps.



Visualizations: Generates charts for revenue growth, cost breakdown, profitability volatility, and segment performance.

2. Key Findings





Tankers Segment Dominance: Contributes over 83% to revenue and profit.



High Purchase Costs: Account for ~87% of total expenditure with significant volatility (e.g., 2276.67 in Q1 2024).



Profitability Volatility: Notable losses in Q3 (e.g., -94.15 in Q3 2019) and other quarters (e.g., -167.12 in Q1 2020).



Weak Revenue-Profit Link: Sales and profitability have a low correlation (0.14), suggesting cost inefficiencies.



Data Gaps: Missing Shares segment data from Q3 2024 onward.

3. AI-Driven Recommendations

The following AI use cases are proposed to address identified challenges:





Predictive Cost Optimization: Forecast purchase costs to reduce expenses by 10-15%.



Seasonal Profitability Forecasting: Predict and mitigate Q3 losses by 20-30%.



Demand and Margin Analysis: Optimize pricing and costs to improve profit margins by 5-10%.



Segment Performance Monitoring: Impute missing Shares data and monitor segment performance for data-driven decisions.

Visualizations

The script generates four visualizations:





Revenue Growth Over Time: Line chart showing Net Sales trends from 2015 to 2025.



Cost Breakdown: Pie chart illustrating the percentage contribution of cost components (Purchase, Employees, Depreciation, Other).



Profitability Volatility Over Time: Line chart displaying PBT fluctuations, highlighting significant losses and gains.



Segment Revenue Performance: Bar chart comparing Tankers and Shares revenue contributions.

Usage

To reproduce the analysis:





Ensure data.csv is in the project directory.



Run code.py or execute cells in a Jupyter Notebook.



Review console outputs for analysis summaries and check generated plots for visualizations.

Limitations





Data Gaps: Missing Shares segment data from Q3 2024 onward limits recent performance analysis.



Assumptions: Missing values in segment metrics are filled with zeros, which may affect accuracy.



Visualization Environment: Plots require a compatible display environment (e.g., Jupyter Notebook or a system with a graphical interface).

Next Steps





Implement AI models for the proposed use cases (e.g., predictive cost optimization, seasonal forecasting).



Enhance data collection to address Shares segment gaps.



Conduct deeper analysis of external factors causing Q3 weaknesses and profitability volatility.

License

This project is licensed under the MIT License. See the LICENSE file for details.
