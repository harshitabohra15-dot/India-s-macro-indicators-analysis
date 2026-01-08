# India Macroeconomic Indicators Analysis using SQL
This project analyses India’s macroeconomic performance using World Bank Development Indicators data. 
The analysis focuses on key indicators such as inflation, GDP growth, unemployment, and government 
final consumption expenditure using SQL Server.
## Data Source
- World Bank – World Development Indicators (WDI)
- Country: India
- Frequency: Annual
- Indicators used:
  - Inflation, consumer prices (annual %)
  - GDP growth (annual %)
  - Unemployment, total (% of labor force)
  - General government final consumption expenditure (% of GDP)
## Database Design
The data was first imported into a raw staging table to handle text values and formatting issues.
After cleaning and type conversion, a final analysis table was created with properly defined 
numeric and categorical columns for efficient querying.
## Key SQL Questions Analysed
- What are the year-wise trends in inflation, GDP growth, unemployment, and government consumption?
- Which years experienced high inflation and low economic growth?
- How do inflation, growth, and unemployment move together over time?
- How do macroeconomic indicators differ across decades?
- ## Key Insights
- Inflation shows significant variation across years, reflecting changing price pressures.
- GDP growth fluctuates, highlighting periods of expansion and economic slowdown.
- High inflation does not always coincide with low unemployment, indicating structural factors.
- Government consumption tends to increase during periods of economic stress, suggesting a 
  counter-cyclical fiscal role.
- Certain years exhibit characteristics of macroeconomic stress, combining low growth, 
  high inflation, and higher unemployment.
## Limitations
- The analysis is based on annual data, which limits short-term dynamics.
- The study is descriptive and does not establish causal relationships.
- Missing values in some indicators restrict full time-period coverage.

