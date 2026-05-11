Student Club Participation Bar Chart

A simple data visualization program made in R.
This program allows users to input club names and student counts, then generates a colorful bar chart showing student participation in different clubs.

Features
- Input club names
- Input number of students
- Generates colorful bar charts
- Error handling for invalid inputs
- Automatic graph generation

Input Validation

The program validates user inputs:

| Input              | Validation                    |
| ------------------ | ----------------------------- |
| Club Name          | Letters and spaces only       |
| Number of Students | Numeric values only           |
| Number of Clubs    | Numeric values greater than 0 |

Program Structure

The program contains several features:

User Input
Allows the user to:
- Enter number of clubs
- Enter club names
- Enter student counts

Error Handling
Uses:
- repeat loops
- if statements
- regular expressions
to prevent invalid inputs.

Bar Chart Visualization

Uses the barplot() function to display:

club names
student counts
colored bars

Graph Design

The graph includes:
- title
- x-axis label
- y-axis label
- different bar colors
- borders

Data Used

Club Participation Table

Stores all club participation records.

Columns:
- Club Name
- Number of Students

How to Run
1. Open R or RStudio
2. Copy the code into a script file
3. Save the file as:
Data Visualization.R
4. Run the script:
source("Data Visualization.R")

Example Output:
Bar Chart Title:
Student Club Participation

X-Axis:
Clubs

Y-Axis:
Number of Students

Requirements
- R programming language
- Base R only (no additional packages required)

Author: Adrianne Alia
Note: Created for the Finals requirement in R Programming
