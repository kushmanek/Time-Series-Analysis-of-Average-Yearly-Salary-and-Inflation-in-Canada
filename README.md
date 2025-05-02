******Time Series Analysis of Average Yearly Salary and Inflation in Canada******

**Overview**
This project performs a time series analysis of average yearly salaries and inflation rates in Canada using historical data. The analysis explores patterns, stationarity, and relationships between these two economic indicators using transformation techniques and visualizations.

**Author**
Kush Manek

**Files**
final project report.Rmd – R Markdown file containing the full analysis, plots, and methodology.

data.csv – The dataset used, containing monthly data on average yearly salary and inflation values.

**Key Techniques**
Time Series Conversion using ts()

Log Transformations and Differencing to achieve stationarity

Visualization using base R plotting functions

Autocorrelation Analysis with ACF and PACF plots

Libraries used: forecast, tseries, astsa

**Requirements**
Ensure the following R packages are installed:

r
Copy
Edit
install.packages(c("forecast", "tseries", "astsa"))
**How to Run**
Place data.csv in the working directory.

Open final project report.Rmd in RStudio.

Click Knit to generate the report as a Word document.

**Output**
Plots showing trends, seasonality, and transformations.

Insights into salary and inflation trends in Canada over time.
