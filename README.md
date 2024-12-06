# week-01-code-challenge--for
 #netsalarrycalculator.js
The program uses the readline-sync library to prompt the user for input directly from the console:
The SalaryCalculator class organizes all calculations and methods related to salary processing. Upon instantiation, it performs the following
Constructor: Initializes with the user's inputs (basicSalary, benefits), calculates derived values (like grossSalary), and stores results
NHIF Deduction: Uses a bracket-based approach to determine deductions based on grossSalary
Gross Salary Calculation: Adds the basic salary and benefits
NSSF Deduction: Calculated as 6% of gross salary, split into two tiers
ran the program using node.js

 First Ksh 6,000 of gross salary
 
The next Ksh 12,000 (if applicable)
#how it works grade generator
Prompts the user to enter student marks between 0 and 100.
Validates the input to ensure it's a number within the range.
Determines the grade based on the following criteria
Outputs the corresponding grade or requests valid input if the entry is incorrect
ran the program using node.js

#speed detector
determines if a car's driver is adhering to the speed limit and calculates demerit points for overspeeding.
Prompts the user to input the car's speed in km/s.
Validates the input to ensure it's a positive number.
Compares the speed against the speed limit (70 km/s):
If within limit: Outputs Ok.
If over the limit: Calculates demerit points as 1 point for every 5 km/s above the limit.
If the demerit points exceed 12, outputs License suspended.
ran the code using node.js
