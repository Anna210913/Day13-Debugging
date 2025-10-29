# Day13-Debugging

Day 13 didn't have a project however we did three exercises on debugging. Debugging is one of the most important skills in programming. We learned how to identify, trace, and fix errors in our code so it actually does what we expect

## What We Learned
1. **Describe the problem** – figure out what the code is supposed to do and what’s going wrong.  
2. **Reproduce the bug** – make sure the error actually happens consistently.  
3. **Play computer** – mentally trace each line of code to understand what it does.  
4. **Fix errors** – look for red underlines, syntax errors, or logic mistakes.  
5. **Squash bugs with print()** – print variables at key points to see what’s really happening.  
6. **Use a debugger** – step through the code line by line to inspect values and flow.

## Exercises and how we debugged them
# 1. Odd or even:
**Problem**: We needed the code to correctly say whether a number is odd or even.

**How we fixed it**: We tried different numbers and printed the remainder when dividing by 2 (number % 2). This showed us if the number was even (remainder 0) or odd (remainder 1).

**Outcome**: Now the code correctly tells you if a number is odd or even.

# 2. Leap Year:
**Problem**: Leap years follow tricky rules: every 4 years is a leap year, except every 100 years is not, unless it’s divisible by 400. We needed the code to handle all these cases.

**How we fixed it**: We tested example years like 1900, 2000, 2024, and printed the checks at each step. This helped us see if the code was following the rules correctly.

**Outcome**: The code now correctly identifies leap years and normal years.

# 3. FizzBuzz:
**Problem**: The program should print “Fizz” for numbers divisible by 3, “Buzz” for numbers divisible by 5, and “FizzBuzz” for numbers divisible by both. Sometimes it might print the wrong thing.

**How we fixed it**: We tested small numbers and printed what the code was checking (number % 3 and number % 5) to make sure the rules were applied in the right order.

**Outcome**: Now it prints the correct word or number every time.
