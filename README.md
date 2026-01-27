# Amazon Sales Analysis:Data Scrub and show

This project analyzes sales performance and shipping efficiency for a retail dataset.I transformed raw trasactional data into actionable business insights regarding profitability and customer behaviour

## Tech Stack

* Language:Python 3.14
* Libraries:Pandas(Data Manipulation),Matplotlib/Seaborn(visualizations)
* Tools:Jupyter Notebook,VS code
  
## Data Cleaning Process

* Datetime Normalization:converted order_date and ship_date into standardized formats to allow time-series analysis
* Index Alignment:Used reset_index(drop=True) to ensure data integrity and filtering
* Scheme Validation:Ensured sales and profit were treated as floats for mathematical accuracy
* Column Renaming: Renamed columns to follow a consistent naming convention(snake_case),making the dataset easier to query
* Deduplication:Identified and removed duplicate rows to ensure each transaction is unique and to prevent skewed analysis results

  
