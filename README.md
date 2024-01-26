# Timecard Analysis

This repository contains Python code for analyzing timecard data to identify potential scheduling issues and overtime concerns.

## Features

- Identifies employees who have worked seven consecutive days.
- Identifies employees with short breaks (less than 10 hours) between shifts.
- Identifies employees who have worked single shifts longer than 14 hours.

## Requirements

- Python 3.x
- pandas library

## Usage

1. Clone this repository.
2. Install the required libraries: `pip install pandas`
3. Place the Excel file containing timecard data in the same directory as the Python script, ensuring it's named `Assignment_Timecard.xlsx`.
4. Run the Python script: `python timecard_analysis.py`

## Output

The script will print the following information to the console:

- List of employees who have worked seven consecutive days.
- List of employees with short breaks between shifts.
- List of employees who have worked single shifts longer than 14 hours.
