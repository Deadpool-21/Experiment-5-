AIM : To study and implement C++ decision making statements

SOFTWARE USED : VS CODE

1) Theory
   
Decision-making is a core aspect of programming that allows the program to make choices based on specific conditions. C++ provides two primary conditional control structures:

A. If-Else Statement
The if-else structure is flexible and allows evaluation of expressions that return true or false. It supports:

Simple conditions (if)

Multiple choices (if-else if)

Default fallback logic (else)

Complex logic using relational and logical operators (==, !=, >, <, &&, ||, etc.)

This structure is ideal when:

You need to compare ranges or expressions

Decisions involve multiple variables

You want full control over complex conditions

B. Switch-Case Statement
The switch-case structure is used when a single variable or expression needs to be matched against multiple constant values. It includes:

Multiple case blocks for each possible value

A break statement to prevent fall-through

An optional default case when no match is found

This structure is best for:

Menu-driven programs

Character or numeric input-based options

Cleaner syntax for multiple fixed choices

Choosing Between If-Else and Switch-Case
Use if-else for complex logical expressions, range comparisons, and multi-variable decisions.

Use switch-case when comparing one variable to specific constant values for better readability and structure.

2) Algorithms
   
A. Even or Odd Program
Objective: Determine whether a number is even or odd.

Steps:

Start the program.

Declare an integer variable number.

Take input from the user.

Use if to check if number % 2 == 0:

If true, print "The number is even".

Else, print "The number is odd".

Stop the program.

B. Vowel or Consonant Program
Objective: Identify whether a character is a vowel or consonant.

Steps:

Start the program.

Declare a character variable ch.

Take character input from the user.

Use if or switch to check if ch is one of: a, e, i, o, u (or their uppercase variants).

If true, print "The character is a vowel".

Else, print "The character is a consonant".

Stop the program.

C. Largest Among Three Numbers
Objective: Find the largest number among three integers.

Steps:

Start the program.

Declare three integer variables: num1, num2, and num3.

Take input for all three numbers.

Compare the numbers using nested if-else:

If num1 > num2 and num1 > num3, print "Num1 is the largest".

Else if num2 > num1 and num2 > num3, print "Num2 is the largest".

Else, print "Num3 is the largest".

Stop the program.

3) Conclusion
   
This experiment demonstrated how decision-making in C++ is carried out using if-else and switch-case structures.
By implementing programs that check conditions like even or odd, vowel or consonant, and maximum of three numbers, we learned how to:

Build logical flows using conditionals

Choose between flexible logic (if-else) and fixed value matching (switch-case)

Make user-interactive, responsive applications using decision control

These concepts are foundational for developing intelligent, condition-based programs in C++.
