# Income-Statement-Consolidation-and-Analysis
Advanced Python: Assignment 1
A.1 Write a Python notebook (named like LastnameFirstnameAsn1-A1), that reads the following
spreadsheets, using pandas read_excel():
incstmt-0.xlsx – template for income statements (all 0 results)
incstmt-diva.xlsx – income statement for division A
incstmt-divb.xlsx – income statement for division B
and combines division A and division B results into a total company income statement. All
spreadsheets have two historical columns (for actual years 2018 and 2019) and one future column
(projected for 2020).
Notes:
- Use the spreadsheet's first column (named "CODE") as an index (row label) for the DataFrames
- The spreadsheets have comment lines beginning with a #
- The column labelled "Description" can be dropped from the combined income statement
- Consider using the DataFrame add() method to add DataFrames
- This notebook should assume there are only two divisions, each with their own .xlsx file. So for this
notebook, you use hardcoded statements such as pd.read_excel('incstmt-diva.xlsx')
A.2 Using your notebook written for part A.1 as a reference point, create a new notebook (named like
LastnameFirstnameAsn1-A2) that could easily handle any number of divisions, in order to create a
composite income statement.
Notes:
- Create a list of division names whose spreadsheets are to be combined, e.g.,
divisions = ['diva', 'divb']
- Use a for loop to read each division's .xlsx, add cumulate a composite company-wide income
statement in a pandas dataframe
- Use a DataFrame corresponding to the worksheet incstmt-0.xlsx as a starting point for cumulating
income statements.
