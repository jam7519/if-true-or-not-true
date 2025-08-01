Project Title: if-true-or-not-true

Description:
This is a C++ program that asks the user for an integer, evaluates a complex set of conditions, and tells the user whether the result is considered "true" or "not true" based on custom logic. It's great for practicing boolean expressions and conditional logic in C++.

What the Program Does:
1. Prompts the user to enter a number.
2. Applies a series of logical expressions to determine if the input qualifies as “true”.
3. Prints one of two messages:
   - "That's true :)"
   - "That's not true :("

The result is true if one of the following conditions is met:
- The value is greater than or equal to 0 and less than 10
- The value multiplied by 2 is less than 20 AND its value minus 2 is greater than -2
- The value minus 1 is greater than 1 AND its value divided by 2 is less than 10
- The value is equal to 111

How to Run:
Using a C++ compiler:
  g++ main.cpp -o main
  ./main

Or you can run it in an online compiler like:
  - https://replit.com
  - https://cpp.sh
  - https://onlinegdb.com

Example Output:
Enter a value: 111
That's true :)

File:
- main.cpp (contains the logic and input/output)

License:
This project is free to use and modify for learning purposes.
