# Experiment-06-new

Experiment 6
Title: Study of Conditional Statements in Python
Name: Madhur Gupta | PRN: 25070123070 | Batch: B1

Aim


To study and implement conditional statements in Python using if, if-else, and if-elif-else constructs by solving a variety of real-world problems.




Theory

Conditional Statements in Python

Conditional statements allow a program to make decisions and execute certain blocks of code based on whether a condition evaluates to True or False. Python provides three primary forms:

a) if Statement — Executes a block only if the condition is True.

b) if-else Statement — Provides an alternative block to execute when the condition is False.

c) if-elif-else Statement — Handles multiple mutually exclusive conditions in a chain. Python evaluates each condition top-down and executes the first matching block.

Operators Used



Comparison: >, <, >=, <=, ==, !=

Logical: and, or, not

Membership: in (e.g., checking vowels)

Modulus: % (used for even/odd and leap year checks)





Algorithms

Q1: Check if a Number is Positive, Negative, or Zero


Start

Accept a floating-point number as input.

If number > 0, print "The number is positive."

Else if number < 0, print "The number is negative."

Else, print "The number is zero."

Stop






Q2: Check if a Number is Even or Odd



Start

Accept a floating-point number as input.

Compute number % 2.

If remainder == 0, print "The number is even."

Else, print "The number is odd."

Stop





Q3: Find the Greatest Among Three Numbers


Start

Accept three numbers a, b, c as input.

If a > b AND a > c, print "a is greater."

Else if b > a AND b > c, print "b is greater."

Else, print "c is greater."

Stop





Q4: Calculate Grade Based on Marks



Start

Accept subject name and marks (0–100) as input.

If marks >= 90, assign Grade A.

Else if marks > 75, assign Grade B.

Else if marks > 60, assign Grade C.

Else if marks > 40, assign Grade D.

Else, print "Fail."

Print the resulting grade.

Stop





Q5: Check if a Year is a Leap Year



Start

Accept an integer year as input.

If (year % 4 == 0 AND year % 100 != 0) OR (year % 400 == 0), it is a leap year.

Else, it is not a leap year.

Print the result.

Stop





Q6: Calculate Gross Salary of an Employee



Start

Accept basic salary as input.

If basic <= 10,000: HRA = 20% of basic, DA = 80% of basic.

Else if basic <= 20,000: HRA = 25% of basic, DA = 90% of basic.

Else: HRA = 30% of basic, DA = 95% of basic.

Gross Salary = Basic + HRA + DA.

Print Basic, HRA, DA, and Gross Salary.

Stop





Q7: Calculate Income Tax Based on Annual Income



Start

Accept annual income as input.

If income <= 2,50,000: Tax = 0, print "No tax."

Else if income <= 5,00,000: Tax = 5% of (income − 2,50,000).

Else if income <= 10,00,000: Tax = 12,500 + 20% of (income − 5,00,000).

Else: Tax = 12,500 + 1,00,000 + 30% of (income − 10,00,000).

Print the tax amount.

Stop




Q8: Check if a Character is a Vowel or Consonant



Start


Accept a single character as input.

If the character is in {a, e, i, o, u, A, E, I, O, U}, print "is a vowel."

Else, print "is a consonant."

Stop





Q9: Increment a Date by One Day



Start

Accept date in dd/mm/yyyy format and parse into dd, mm, yy.

Validate month: if mm < 1 or mm > 12, print "Date is invalid" and stop.

Determine max_days: 31 for months 1,3,5,7,8,10,12; 30 for months 4,6,9,11; 29 for February in a leap year, else 28.

Validate day: if dd < 1 or dd > max_days, print "Date is invalid" and stop.

If dd == max_days: set dd = 1; if mm == 12, set mm = 1 and yy += 1; else mm += 1.

Else: dd = dd + 1.

Print the incremented date.

Stop





Conclusion

In this experiment, we successfully studied and implemented conditional statements in Python through nine diverse programming problems. The key takeaways are:



The if, if-else, and if-elif-else constructs enable programs to branch and execute different logic based on evaluated conditions.

Logical and comparison operators are fundamental to building compound conditions.

Real-world problems such as salary calculation, tax computation, leap year detection, and grade assignment can be modelled efficiently using conditional logic.

The membership operator (in) provides a concise way to handle character classification like vowel detection.

Nested conditional statements are effective for multi-level decisions such as date validation and incrementing.
