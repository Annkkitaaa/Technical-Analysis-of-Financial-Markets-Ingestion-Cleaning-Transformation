## Technical Analysis of Financial Markets - Data Processing Pipeline

This repository contains scripts and data files related to the ingestion, cleaning, transformation, and visualization of OHLC (Open-High-Low-Close) financial market data. The pipeline includes the following steps:

1. **Data Ingestion:**
   - Developed a script capable of ingesting OHLC data feeds from various sources and formats.
   - Validated data integrity, checked for missing values, outliers, and ensured data type consistency.
   - Standardized the data format to a common structure using pandas DataFrame.

2. **Data Cleaning:**
   - Identified and handled missing values through imputation or removal techniques.
   - Detected and corrected outliers using statistical methods or domain knowledge.
   - Addressed inconsistencies in timestamps or date formats.

3. **Data Transformation:**
   - Calculated technical indicators based on OHLC data, such as moving averages, Bollinger Bands, and Relative Strength Index.
   - Applied feature engineering techniques to create new features relevant for trading strategy, including volatility measures and price patterns.
   - Resampled the data based on desired frequencies, e.g., from daily to hourly.

4. **Data Validation:**
   - Implemented unit tests to ensure the pipeline's functionality and data integrity.
   - Monitored the pipeline for errors and data quality issues.

5. **Data Storage:**
   - Utilized a simple database (e.g., SQLite, MySQL) to store the processed data.
   - Partitioned the data by year, month, or other relevant categories for efficient querying.
   - Optimized the data format for fast retrieval and analysis, such as using a columnar format.

### Visualization on Tableau
- The processed data has been visualized on Tableau for further analysis and exploration.
- [Tableau Visualization](https://public.tableau.com/shared/K4XGHBHSB?:display_count=n&:origin=viz_share_link)

![Dashboard 1 (1)](https://github.com/Annkkitaaa/Technical-Analysis-of-Financial-Markets-Ingestion-Cleaning-Transformation/assets/100662026/dd2b6c85-ceab-4052-be4c-6e8f99a27075)


### Files Included
- `data_exploration_and_cleaning.ipynb`: Jupyter Notebook containing the code for data exploration and cleaning.
- `before_analysis.csv`: Raw data file before any processing.
- `cleaned_output.csv`: Processed data file after ingestion, cleaning, and transformation.

