# First-automation-project

# Project Summary
This was accomplished by looking at the user's need of comparing total sales recorded in
excel. We used python to automate manual process for an end of day balance transaction sheet.
This will allow the user to know when there is a mismatch between daily transactions and,
end of day total number of sales for the day. With the goal fo corrobrating the total amounts match.
We focused on locating the amounts located in cells withing the excel sheet that add to the
grand total to be able to compare both. Using highlighting to better see the information we need.
The final report shows the totals match allowing the user be prone to skipping crucial data that 
could generate any issues.


# Technical Summary
Back end language: Python
Dataset:  Excel

# Features
The script will check for differences between daily total transactions and end of day final numbers report. 
If there is a difference found the program will compare totals by PO number. 
There will be a graphical representation by highlighting the values to better visualize data 
for final totals check.

# Milestones
Import the needed packages.
Open the files needed and show them through Jupyter Notebooks.
Convert pdf files into excel sheets (xlsx, or csv) using tabula technology.
Compare final amounts from the two excel files.

# Requirements
Python
MS Excel
Pandas-Jupyter Notebooks
Tabula Technology
Numpy
Openpyxl