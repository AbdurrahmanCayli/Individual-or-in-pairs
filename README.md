# Individual-or-in-pairs
Write a C/C++ console program to calculate the GPA results of a student for a term.
The console program asks the student to enter his/her name and surname at the
beginning. Afterwards the program prompts the student to enter how many courses
he/she has taken this term. Furthermore, the student needs to enter the ı credits,
midterm result, homework result and final exam result for each course one by one.
The Grade calculating system will show how many courses the student has taken this
term and the total credit amount. The program calculates the grade average of each
course as well as student’s GPA mark for the corresponding term.
The program does not allow any student to take more than 7 courses in a term. In
another words, a student takes at least one course and at most 7 courses in any term.
Assume that you know your total grade from each course.
Use different variables to store student’s number, full name and number of courses
taken in a term. The program calculates the total credits and the overall GPA for a term.
The courses that can be taken is limited with 7 so you need to create a series of arrays
which contains maximum of 7 values.
Use a string pointer to store 7 course names such as :
char courses[7][99];
Use a single dimensional array of 7 integers to store course credits and course marks.
Additionally, use a single dimensional array of 7 float number for the gpa.
int totalMark[7];
int credits[7];
float gpa[7];
You will need to calculate the GPA points earned from each course.
After calculating the total grade of each course successfully, you need to find the GPA
points for each course in order to calculate the overall GPA mark.
Use the following values to calculate the GPA points for a course:
4.00 total mark >= 95
3.70 total mark < 95 and total mark >= 90
3.50 total mark < 90 and total mark >= 85
3.30 total mark < 85 and total mark >= 80
3.00 total mark < 80 and total mark >= 75
2.70 total mark < 75 and total mark >= 70
2.50 total mark < 70 and total mark >= 65
2.30 total mark < 65 and total mark >= 60
2.00 total mark < 60 and total mark >= 55
1.70 total mark < 55 and total mark >= 50
0.00 total mark < 50
GPA Calculation
To calculate your GPA, take the number of points for each grade and multiply it by the
number of credits. For example, if you take 95 from a 3 credit course, that is :
3 X 4.00 = 12 credits
Example
3 credits A 3 x 4.0 = 12.0 points
3 credits B- 3 x 2.7 = 8.1 points
2 credits C 2 x 2.0 = 4.0 points
2 credits F 2 x 0.0 = 0.0 points
Term GPA:
10 credits = 24.1 points
24.1 divided by 10 credits = 2.41 GPA
