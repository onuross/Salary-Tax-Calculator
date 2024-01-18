# Salary Tax Calculation Program

This Python script calculates income tax for sales representatives based on their gross salary. The tax rates vary depending on the salary range.

## Constants
- `maxLowGross`: Maximum gross salary for the low tax rate.
- `minHighGross`: Minimum gross salary for the medium tax rate.
- `maxHighGross`: Maximum gross salary for the high tax rate.
- `lowRate`: Low tax rate (15%).
- `medRate`: Medium tax rate (20%).
- `highRate`: High tax rate (25%).

## Counters and Accumulators
- `lowCounter`: Counter for representatives with low gross salary.
- `medCounter`: Counter for representatives with medium gross salary.
- `highCounter`: Counter for representatives with high gross salary.
- `higherCounter`: Counter for representatives with more than $50k gross salary.
- `totalLowGrossSalary`: Accumulator for total gross salary in the low range.
- `totalMedGrossSalary`: Accumulator for total gross salary in the medium range.
- `totalHighGrossSalary`: Accumulator for total gross salary in the high range.
- `totalHigherGrossSalary`: Accumulator for total gross salary above $50k.
- `totalNetLowSalary`: Accumulator for total net salary in the low range.
- `totalNetMedSalary`: Accumulator for total net salary in the medium range.
- `totalNetHighSalary`: Accumulator for total net salary in the high range.
- `taxPaid`: Accumulator for total tax paid.

## User Input and Calculation
The script takes user input for gross salary in a loop until the user enters `0` or `-9999999999`. Based on the gross salary, it calculates the net salary and tax paid for each representative, updating counters and accumulators accordingly.

## Results and Analysis
After user input is complete, the script calculates and prints various results, including the number of representatives in each salary range, the percentage of representatives with more than $50k salary, the average net salary, and the total tax paid with its percentage relative to the total gross salary.

## Note
- The script doesn't handle invalid inputs (other than `0` or `-9999999999`) or edge cases explicitly. Additional input validation could be added if needed.
