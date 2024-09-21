# Real Estate Price Volatility Analysis

This project analyzes the volatility of rent prices in different ZIP codes over the past 5 years, with a special focus on the year 2022. The objective is to identify which ZIP codes have experienced the highest and lowest volatility of rent prices, and to determine the main drivers contributing to this volatility.

## Objective

The primary goal of this analysis is to:
1. Identify the top 10 ZIP codes with the **highest volatility** in rent prices.
2. Identify the top 10 ZIP codes with the **lowest volatility** in rent prices.
3. Analyze and explain the factors that contributed to the high/low volatility in the year 2022.
4. Use statistical and data science methods to validate the findings.
5. Document and organize the process used to generate these lists.

## Data Sources

The data used in this analysis includes:
- **Zillow Observed Rent Index (ZORI)**: Rent price data by ZIP code, with 'RegionID' representing ZIP (equivalent to postal codes in Canada).
- **Zillow Home Value Index (ZHVI)**: Home value data by ZIP code, with 'RegionID' representing ZIP.
- **Economic and demographic data for 2022** from Altus Group.

## Deliverables

- A list of the top 10 most volatile ZIP codes based on rent prices over the past 5 years.
- A list of the top 10 least volatile ZIP codes.
- An explanation of the contributing factors to volatility in 2022 for each of the most and least volatile ZIP codes.
- A well-documented process, including statistical methods and data science techniques, to validate the results.

## Methodology

1. **Volatility Calculation**:
   - Volatility is measured as the variation of rent prices over time using data from ZORI and ZHVI.
   - The volatility is calculated for each ZIP code over the past 5 years.
   
2. **Top 10 Most and Least Volatile ZIP Codes**:
   - The ZIP codes with the highest and lowest volatility over the past 5 years are ranked, and the top 10 most and least volatile ZIP codes are selected.
   
3. **Drivers of Volatility**:
   - Using demographic and economic data from Altus Group (2022), the factors contributing to the volatility are analyzed.
   - Factors such as economic growth, population changes, and housing demand are considered.

4. **Statistical Validation**:
   - Data science and statistical best practices are used to ensure the robustness and reliability of the results.
   - Confidence intervals and other statistical methods are applied to validate the top 10 lists.

## Tools and Technologies

- **Python**: Programming language used for analysis.
- **Jupyter Notebook**: For documenting and running the analysis.
- **Pandas, NumPy**: For data manipulation and analysis.
- **Matplotlib, Seaborn**: For data visualization.
- **Scikit-learn**: For statistical modeling and analysis.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-estate-analysis.git
