Assignment 1
Takehiro Tanaka

Description:
From q1.90 to q5.f90, the code was constructively programmed. Hence, the q5.f90 and
q5_2.f90 are the latest version of code that contains everthing.(Because I couldn't implement module...)
If you need to read the code, just read q5.f90 that contains everything functions.

Hence, q1.f90 only shows the Gaussian elimination solution in question 1. --> output result in the terminal.
q4.f90 shows from question 2 to question 4 for 10 terms. -->output 'q4_output_10terms.pdf'
q4_2.f90 shows from question 2 to question 4 for 100 terms.  -->output 'q4_output_100terms.pdf'
q5.f90 repeat q4.f90 for different xi for 10 terms. --> output 'q5_output_10terms.pdf'
q5_2.f90 repeat q4.f90 for different xi for 100 terms. --> output 'q5_output_100terms.pdf'

Difference between q4 and q5 is using populateArray2() function in q5 instead of populateArray() function used in q4.

Note q3.f90 shows the solution for question3, which is also shown in q4.f90 and q4_2.f90. --> output 'q3_output.pdf'

Also maximum value and the location of x is shown in the terminal for each case (q4.90, q4_2.f90, q5.f90, q5.f90)


Running Instruction, type command and hit enter:
bash runme.sh

To see the output pdf, make sure to make pdf 'full screen'. Otherwise, you may not be able to see the last page! I believe this is the software problem of pdf in linux!
