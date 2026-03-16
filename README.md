Streaming Wars: Netflix vs. Disney Market Analysis (2020 - 2024)

Project Summary
This Python based financial analysis compares the stock performance of industry leaders Netflix and Disney over a four year period. The analysis evaluates investment growth, volatility, and market resilience to understand how both companies navigated changes in the media and streaming industry. The results show a clear trade off. Netflix delivered stronger growth and higher returns, while Disney offered more stability through its diversified business model.

Overview
This project analyzes stock price trends during major industry events, including the 2022 streaming market downturn and the recovery observed in 2024. The analysis combines financial data processing with visualization to answer three key questions.

• Which company generated stronger long term shareholder returns
• Which stock carried higher risk based on daily price volatility
• How major business events affected stock performance and market value

Tools and Technologies

Language
Python

Libraries
Pandas
Matplotlib
NumPy

Environment
Google Colab or Python IDE

Visualization
Tableau Desktop or Tableau Public

Feature Engineering and Methodology

To create a fair comparison between stocks with different share prices, two financial metrics were engineered.

Cumulative Returns
Used to measure the growth of a one dollar investment from the starting date.

Formula
Cumulative Return = Current Price divided by Initial Price

Daily Returns
Used to measure daily price changes and evaluate volatility.

Formula
Daily Return = (Price at time t minus Price at time t-1) divided by Price at time t-1

Technical Workflow

Data Cleaning
Standardized the Date column to datetime format.
Removed hidden whitespace from column headers using string manipulation.
Handled missing values and ensured consistent column formatting.

Time Series Preparation
Sorted the dataset chronologically and set Date as the index to enable accurate time series analysis.

Event Annotation
Identified key market events including the 2022 subscriber loss announcement and the 2024 recovery peak. These events were highlighted in visualizations to provide context.

Data Export
Prepared and exported cleaned datasets for visualization and dashboard development in Tableau.

Key Insights

Growth vs Stability
Netflix produced stronger total returns during the analysis period but showed higher volatility. Disney maintained more stable price movement due to revenue diversification across streaming, theme parks, and film studios.

The 2022 Market Shock
Netflix experienced a sharp stock decline in 2022 following its first reported subscriber loss in over a decade.

Recovery Trend
Netflix recovered strongly and reached new highs in 2024, outperforming Disney in overall return.

Market Sensitivity
Pure streaming companies like Netflix respond more strongly to subscriber growth and platform performance updates than diversified media companies like Disney.

Repository Structure

data
Contains raw and cleaned stock datasets used for the analysis.

notebooks
Python notebooks containing the full analysis workflow and exploratory analysis.

visualizations
Charts and links to interactive Tableau dashboards created from the processed data
