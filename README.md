# WFC Stock Market Impact Analysis

## Objective
This project analyzes how the fake accounts scandal affected Wells Fargo's (WFC) stock price and market position.

## Methods
- **Comparative Analysis**: Compare WFC’s stock performance to competitors like JPMorgan Chase and Bank of America.
- **Time Series Analysis**: Examine WFC's stock price trends before, during, and after the scandal using the Prophet model.

## Data Sources
Stock data for Wells Fargo (WFC) and competitors were collected from the following sources:
- [Kaggle: WFC Stock Data](https://www.kaggle.com/datasets/varpit94/wells-fargo-stock-data-updated-till-30jun-2021)
- [Bank of America (BAC) Historical Data](https://investor.bankofamerica.com/shareholder-information/historical-data)
- [Investing.com: JPM Stock Data](https://www.investing.com/equities/jp-morgan-chase-historical-data)

### Data Fields
- **Date**: Trading date
- **Open**: Opening stock price
- **High**: Highest stock price of the day
- **Low**: Lowest stock price of the day
- **Close**: Closing stock price
- **Adj Close**: Adjusted closing price after corporate actions
- **Volume**: Number of shares traded

## Dependencies
To run this analysis, install the required Python libraries:
```sh
pip install pandas matplotlib seaborn prophet
```

## Usage
1. Clone this repository and navigate to the project directory:
   ```sh
   git clone <repo_url>
   cd WFC_Stock_Market_Impact_Analysis
   ```
2. Ensure the required datasets (`WFC.csv`, `BAC.csv`, `JPMorgan_Stock_Merged.csv` and `JPMorgan_Stock_Price_History.csv`) are in the working directory.
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook WFC_Stock_Market_Impact_Analysis.ipynb
   ```
4. Follow the notebook steps to analyze the data and generate visualizations.

## Results & Insights
- **Stock Trends**: The adjusted closing price is used for long-term trend analysis.
- **Impact of Scandal**: A sharp decline in WFC stock is observed during the scandal timeline.
- **Comparative Performance**: WFC underperformed relative to competitors post-scandal.

## Author
This analysis was conducted by Lizbeth Bolano.

Regis University – MSDS692 s40 - Data Science Practicum I

Instructor: Mike Busch


