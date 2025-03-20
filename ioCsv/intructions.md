# Code Kata: CSV Data Processor

## Objective
Create a command-line tool that reads a CSV file containing sales data, processes it, and outputs calculated statistics.

## Requirements
1. Build a program that:
   - Reads data from a CSV file
   - Calculates summary statistics (total, average, min, max)
   - Groups data by categories
   - Outputs results in a structured format

2. The program should:
   - Handle errors gracefully (file not found, malformed data)
   - Process numeric and categorical data
   - Follow a clean separation of concerns (file I/O, data processing, output)

## Example Usage
```
$ ./process_sales.js sales_data.csv

Sales Summary:
Total Revenue: $12,750.00
Average Sale: $425.00
Largest Sale: $1,200.00
Smallest Sale: $120.00

Sales by Region:
North: $3,950.00 (8 sales)
South: $2,800.00 (7 sales)
East: $3,200.00 (7 sales)
West: $2,800.00 (8 sales)
```

