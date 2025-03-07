# Salary Calculator

## Overview

The Salary Calculator is a Python program designed to compute the net salary after deductions such as SSS, PhilHealth, Pag-IBIG, and income tax. The program prompts users to input their monthly salary and then calculates and displays a detailed breakdown of deductions and the resulting net salary.

## Features

- Calculates SSS, PhilHealth, Pag-IBIG, and income tax deductions.
- Displays a detailed salary breakdown for clarity.
- Ensures accurate deduction calculations based on user input.

## Refactored Changes

### Enhancements & Fixes

- Input Validation & Error Handling
  - Ensured salary input is a positive numeric value.
  - Added exception handling to prevent program crashes due to invalid inputs.

- Code Readability & Maintainability
  - Improved variable naming for better clarity.
  - Standardized formatting in the salary breakdown output.

### Bug Fixes

- Corrected the syntax for script execution: if _name_ == "_main_": was fixed.

## Technical Debt Identified

- Income Tax Calculation: Currently a fixed value rather than being dynamic or based on actual tax brackets.
- SSS Contribution: Hardcoded SSS contribution instead of being computed based on official SSS tables.
- Unit Tests: No unit tests implemented to verify the correctness of the salary calculations.

## Refactoring Improvements Made

- Error Handling: Implemented robust error handling for salary input to ensure program stability.
- Input Validation: Enhanced user experience by prompting for valid salary inputs.
- Code Clarity: Increased maintainability by fixing syntax issues and improving variable naming.

## Challenges Faced & Solutions

### 1. Handling Invalid Inputs Gracefully
   - Solution: Utilized a while True loop with exception handling to prompt the user until a valid salary is entered.

### 2. Ensuring Accurate Salary Deductions
   - Solution: Identified areas for improvement, such as dynamically calculating tax brackets and SSS contributions, for future updates.

### 3. Correcting Minor Syntax Errors
   - Solution: Fixed the script's entry point (if _name_ == "_main_"to ensure proper execution.

## Future Improvements

- Implement dynamic tax bracket calculations and SSS contributions based on the latest official tables.
- Add unit tests to verify the correctness of the deduction calculations.
- Optimize code for better performance and scalability.

## Usage

1. Clone or download the repository.
2. Run the salary_calculator.py script.
3. Input your monthly salary when prompted.
4. View the breakdown of deductions and the resulting net salary.