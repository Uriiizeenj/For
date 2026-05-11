Student Ranking System

This R program is a simple Student Ranking System that allows users to input student names and grades.
The program validates the inputs, sorts the grades from highest to lowest, assigns rankings, and displays the results in a formatted table.

Features:
- Input student names
- Input student grades
- Automatic ranking system
- Sorts grades from highest to lowest
- Error handling for invalid inputs
- Formatted console output

Input Validation
The program validates user inputs:

| Input              | Validation                    |
| ------------------ | ----------------------------- |
| Student Name       | Letters and spaces only       |
| Grades             | Numeric values only           |
| Number of Students | Numeric values greater than 0 |

Program Structure

The program contains several features:

User Input
Allows the user to:

- Enter number of students
- Enter student names
- Enter grades

Error Handling
Uses:
- repeat loops
- if statements
- regular expressions
to prevent invalid inputs.
Ranking System
The program:
- Sorts grades from highest to lowest
- Automatically assigns rankings

Formatted Output
Displays:
- Rank
- Student Name
- Grade
in a clean table design.

Data Used

Student Table

Stores all student records.

Columns:
- Name
- Grade
- Rank

How to Run

1. Open R or RStudio
2. Copy the code into a script file
3. Save the file as:
For.R

Run the script:

source("For.R")

Example Output:

=================================
      STUDENT RANKING SYSTEM
=================================

Rank   Name            Grade
---------------------------------
1      Adrian          95.00
2      John            91.00
3      Mark            88.00

=================================
        END OF REPORT
=================================

Requirements
- R programming language
- Base R only (no additional packages required)

Author: Adrianne Alia
Note: Created for the Finals requirement in R Programming
