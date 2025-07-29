#Aim:
To study and implement C++ decision making statements

#Software Required:
Visual Studio

#Theory:
Decision-making is the process to make a decision about which part of the code should be executed or not based on some condition. Decision-making in C++ involves the usage of conditional statements (also called decision control statements) to execute specific blocks of code primarily based on given situations and their results.

#if Statement:
In C++, the if statement is the simplest decision-making statement. It allows the execution of a block of code if the given condition is true. The body of the if statement is executed only if the given condition is true.

if-else Statement The if else is a decision-making statement allows us to make a decision based on the evaluation of a given condition. If the given condition evaluates to true then the code inside the 'if' block is executed and in case the condition is false, the code inside the 'else' block is executed.

if else if Ladder The if else if Ladder statements allow us to include additional situations after the preliminary if condition. The 'else if' condition is checked only if the above condition is not true, and the else is the statement that will be executed if none of the above conditions is true. If some condition is true, then not only the associated block is executed.

Nested if else The nested if else statement contains an 'if' statement inside another 'if' statement. This structure lets in more complex selection-making by way of comparing multiple conditions. In this type of statement, multiple conditions are checked, and then the body of the last if statement is executed.

Switch Statement In C++, the switch statement is used when multiple situations need to be evaluated primarily based on the value of a variable or an expression. switch statement acts as an alternative to multiple if statements or if-else ladder and has a cleaner structure and it is easy for handling multiple conditions.

#Implementation:
Based on the above decision making statements in C++ , Simple programs have been used to help understand how decision making statements work in c++. The programs are:

Odd-Even check

Vowel Check

Finding the largest number from three given numbers by the user

Making a Calculator using Switch Case

Made a basic Hostel fee structure using Switch Case

#Algorihtms:
#Program 1:
Objective: To determine whether a user-entered number is even or odd.

Steps:

Start

Ask the user to enter an integer (n)

Read input into variable n

Check divisibility of n by 2:

If n % 2 == 0, then:

Display "This is an even number"

Else:

Display "This is an Odd number"

End

#Program 2:
Objective: To determine whether the character entered by the user is a vowel or a consonant.

Steps:

Start

Declare a character variable str

Ask the user to enter a character

Read the input into str

Check if the character is a vowel:

If str is equal to 'a', 'e', 'i', 'o', 'u' (or their uppercase forms), then:

Display "The Character entered is a Vowel"

Else:

Display "The Character entered is a Consonant"

End

#Program 3
Objective:

To determine and display the largest number among three user-entered integers.

Steps:

Start

Declare three integer variables: a, b, c

Ask user to enter three numbers

Read input values into a, b, and c

Initialize num ← a

Compare b and c with num:

If b > num, set num ← b

If c > num, set num ← c

Display the largest number (num)

End

#Program 4:
Objective: To perform one of four basic arithmetic operations—Addition, Subtraction, Multiplication, or Division—based on user input.

Steps:

Start

Declare float variables a, b, sum, sub, mul, Div and integer num

Ask user to enter two numbers

Read inputs into a and b

Ask user to select an operation:

1 → Addition

2 → Subtraction

3 → Multiplication

4 → Division

Read input into num

Use a switch-case statement to perform the selected operation:

Case 1: sum ← a + b

Case 2: sub ← a - b

Case 3: mul ← a * b

Case 4: Div ← a / b

Default: Display invalid input message

Display the result of the selected operation

End

#Program 5:
Objective : to display hostel fees based on user choice

START Begin the execution of the program.

INCLUDE HEADER FILE Use #include to enable input/output operations using cin and cout.

USE NAMESPACE Use using namespace std; to avoid writing std:: before standard library components.

DISPLAY MENU OPTIONS Print the available choices for hostel-related queries:

Option 1: Hostel fee for 3 months

Option 2: Hostel fee for 6 months

Option 3: Hostel fee for 12 months

Option 4: Additional charges for AC and Mess

Option 5: Exit

ACCEPT USER INPUT Declare an integer variable choice.
Prompt the user to enter their selection using cin >> choice.

USE SWITCH-CASE STATEMENT Evaluate the value of choice using a switch(choice) block.
CASE 1: If choice == 1:

Print Hostel fees for 3 months is Rs. 48,000 (exclusive of GST)

Use break; to exit the current case.

CASE 2: If choice == 2:

Print Hostel fees for 6 months is Rs. 96,000 (exclusive of GST)

Use break; to exit the current case.

CASE 3: If choice == 3:

Print Hostel fees for 12 months is Rs. 1,92,000 (exclusive of GST)

Use break;

CASE 4: If choice == 4:

Print AC charges: Rs. 2000/month, Mess charges: Rs. 5000/month

Use break;

CASE 5: If choice == 5:

Print Exiting the program

Use break;

NO DEFAULT CASE INCLUDED Since all valid choices from 1–5 are covered, there is no default: case in this version.
You may optionally add error handling to notify users if the input is invalid.

END Terminate the program after executing the selected case.
#Program 6:
Objective : to display days of the week using switch case

START Begin the execution of the program.

INCLUDE REQUIRED HEADER Include the iostream library to enable input/output operations:

#include 3. USE STANDARD NAMESPACE Use the standard namespace to simplify usage of built-in objects like cin and cout

using namespace std; 4. DECLARE VARIABLES Declare an integer variable named choice to store the user's input.

DISPLAY MENU TO USER Print the list of days of the week with numbered options:
Monday

Tuesday

Wednesday

Thursday

Friday

Saturday

Sunday

Prompt the user to enter a number corresponding to a day.

ACCEPT USER INPUT Read the user’s input and store it in the variable choice:
cin >> choice; 7. EVALUATE INPUT USING SWITCH CASE Use a switch(choice) statement to check the value entered:

Case 1: Print "Monday"

Case 2: Print "Tuesday"

Case 3: Print "Wednesday"

Case 4: Print "Thursday"

Case 5: Print "Friday"

Case 6: Print "Saturday"

Case 7: Print "Sunday"

Default: If the input doesn’t match any of the cases, print "Invalid choice"

Each case ends with a break; statement to prevent fall-through.

END PROGRAM Return 0 from main() to indicate successful completion.
