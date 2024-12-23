Name: Mayank raj
Company:CODTECH IT SOLUTION
ID:CT08DS388
Domain: Java programing
Duration:December 2024to January 2025
Mentor:Muzammil Ahmed  


Overview of the Code:
The provided Java program, GradeTracker, is designed to manage and calculate student grades. The program performs the following key functions:

User Input for Grades:

The program prompts the user to enter the number of subjects or assignments they want to input grades for.
It then collects the grades for each subject/assignment from the user and stores them in an array.
Grade Calculation:

After receiving all the grades, the program calculates the average grade by summing up all the grades and dividing by the total number of subjects or assignments.
Grade Categorization:

The program calculates the letter grade based on the average grade:
A: 90–100
B: 80–89
C: 70–79
D: 60–69
F: Below 60
Additionally, the program calculates the GPA based on the average grade using a predefined scale:
A: 4.0
B: 3.0
C: 2.0
D: 1.0
F: 0.0
Output Results:

The program displays the calculated average grade, the letter grade, and the GPA to the user.
Detailed Breakdown:
Input Section:

The program begins by asking how many subjects or assignments the user wants to input grades for (numberOfGrades).
The grades are collected using a loop, where the user is asked to input a grade for each subject.
Average Calculation:

The sum of all entered grades is calculated in a loop.
The average grade is determined by dividing the total sum by the number of grades entered.
Grade Calculation (Letter Grade and GPA):

The program contains two methods (getLetterGrade and getGPA) to convert the numeric average into a letter grade and GPA, respectively.
The getLetterGrade method determines the letter grade based on fixed grade ranges.
The getGPA method assigns a GPA based on the same ranges but in the GPA scale.
Output:

Finally, the program prints the calculated average grade, letter grade, and GPA.
Key Features:
Dynamic Input: The number of subjects/assignments can vary based on user input, allowing flexibility in grade tracking.

Grade to Letter Conversion: It provides an automatic conversion of numeric grades into letter grades and GPA, which are commonly used in academic systems.

Clean and Interactive: The program is interactive and user-friendly, providing clear prompts and output for the user to understand their grades.
