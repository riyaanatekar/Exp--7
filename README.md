Aim
To study and implement different types of loops in Python,
especially the while loop, and to perform various operations such as printing numbers, calculating factorial, generating Fibonacci series, 
checking palindrome, reversing numbers, counting digits, searching elements in a list, and using loop control statements like break and continue.

Theory
Loops are used in programming to execute a block of code repeatedly as long as a specified condition is true. In Python, loops help in reducing code repetition and improving efficiency.

1. While Loop
The while loop executes a set of statements repeatedly as long as the given condition remains true
The loop checks the condition.
If the condition is true, the statements inside the loop are executed.
The loop continues until the condition becomes false.

2. Applications of While Loop
In this experiment, the while loop is used for:
Printing numbers from 1 to N
Calculating the factorial of a number
Generating Fibonacci series
Reversing a number
Checking palindrome (number and string)
Counting digits in a number
Searching an element in a list

3. Loop Control Statements
break: Terminates the loop immediately.
continue: Skips the current iteration and moves to the next iteration.
else with while: Executes when the loop finishes normally (without break).
These control statements improve flexibility and control over loop execution.

Algorithm for Program 1: Study of Loops in Python (Header Information)
Step 1: Start.
Step 2: Display the experiment title and student details.
Step 3: Stop.

Algorithm for Program 2: Print i as long as i is less than 6
Step 1: Start.
Step 2: Initialize i = 1.
Step 3: Check if i < 6.
Step 4: If true, print i.
Step 5: Increment i by 1.
Step 6: Repeat Steps 3 to 5 until condition becomes false.
Step 7: Stop.

Algorithm for Program 3: Print Numbers from 1 to N
Step 1: Start.
Step 2: Accept integer n from user.
Step 3: Initialize i = 1.
Step 4: Check if i <= n.
Step 5: If true, print i.
Step 6: Increment i by 1.
Step 7: Repeat Steps 4 to 6 until condition becomes false.
Step 8: Stop.

Algorithm for Program 4: Factorial of a Number
Step 1: Start.
Step 2: Accept integer n from user.
Step 3: Initialize fact = 1.
Step 4: While n > 0, multiply fact = fact × n.
Step 5: Decrement n by 1.
Step 6: Repeat Steps 4 and 5 until n becomes 0.
Step 7: Print fact.
Step 8: Stop.

Algorithm for Program 5: Fibonacci Series using While Loop
Step 1: Start.
Step 2: Accept integer n from user.
Step 3: Initialize a = 0, b = 1, i = 1.
Step 4: Check if i <= n.
Step 5: If true, print a.
Step 6: Compute c = a + b.
Step 7: Assign a = b.
Step 8: Assign b = c.
Step 9: Increment i by 1.
Step 10: Repeat Steps 4 to 9 until condition becomes false.
Step 11: Stop.

Algorithm for Program 6: Fibonacci Series up to a Limit
Step 1: Start.
Step 2: Accept integer limit from user.
Step 3: Initialize a = 0, b = 1.
Step 4: Check if a <= limit.
Step 5: If true, print a.
Step 6: Compute next term using a = b and b = a + b (simultaneous update).
Step 7: Repeat Steps 4 to 6 until condition becomes false.
Step 8: Stop.

Algorithm for Program 7: Reverse a Number
Step 1: Start.
Step 2: Accept integer num from user.
Step 3: Initialize rev = 0.
Step 4: While num > 0, find digit = num % 10.
Step 5: Update rev = rev × 10 + digit.
Step 6: Remove last digit using num = num // 10.
Step 7: Repeat Steps 4 to 6 until num becomes 0.
Step 8: Print rev.
Step 9: Stop.

Algorithm for Program 8: Check Palindrome Number
Step 1: Start.
Step 2: Accept integer num from user.
Step 3: Store original number in temp.
Step 4: Initialize rev = 0.
Step 5: While num > 0, compute reversed number using modulus and division.
Step 6: Compare temp and rev.
Step 7: If equal, print “Palindrome”.
Step 8: Otherwise, print “Not Palindrome”.
Step 9: Stop.

Algorithm for Program 9: Check Palindrome for a String (Fixed String)
Step 1: Start.
Step 2: Assign string s = "madam".
Step 3: Initialize i = 0, j = length of s - 1.
Step 4: Set is_palindrome = True.
Step 5: While i < j, compare s[i] and s[j].
Step 6: If not equal, set is_palindrome = False and break.
Step 7: Increment i and decrement j.
Step 8: After loop, if is_palindrome is True, print “Yes”.
Step 9: Otherwise, print “No”.
Step 10: Stop.

Algorithm for Program 10: Check Palindrome for User Input String
Step 1: Start.
Step 2: Accept string s from user.
Step 3: Initialize i = 0, j = length of s - 1.
Step 4: Set is_palindrome = True.
Step 5: While i < j, compare characters at position i and j.
Step 6: If unequal, set is_palindrome = False and break.
Step 7: Increment i and decrement j.
Step 8: If is_palindrome is True, print “Yes”.
Step 9: Otherwise, print “No”.
Step 10: Stop.

Algorithm for Program 11: Check Palindrome using Slicing
Step 1: Start.
Step 2: Accept string st from user.
Step 3: Reverse string using slicing and store in rev.
Step 4: Compare st and rev.
Step 5: If equal, print “Palindrome”.
Step 6: Otherwise, print “Not Palindrome”.
Step 7: Stop.

Algorithm for Program 13: Exit Loop when i is 3
Step 1: Start.
Step 2: Initialize i = 1.
Step 3: While i < 6, print i.
Step 4: If i == 3, terminate loop using break.
Step 5: Increment i by 1.
Step 6: Stop.

Algorithm for Program 14: Search an Element in a List
Step 1: Start.
Step 2: Define list nums = [10, 20, 30, 40, 50].
Step 3: Accept integer key from user.
Step 4: Initialize i = 0.
Step 5: While i < length of nums, compare nums[i] with key.
Step 6: If equal, print index and terminate loop using break.
Step 7: Increment i by 1.
Step 8: If loop completes without break, print “Element not found”.
Step 9: Stop.

Algorithm for Program 15: Print Only Odd Numbers (1 to 10)
Step 1: Start.
Step 2: Initialize i = 0.
Step 3: While i < 10, increment i by 1.
Step 4: If i is even, skip iteration using continue.
Step 5: Otherwise, print i.
Step 6: Repeat Steps 3 to 5 until condition becomes false.
Step 7: Stop.

Conclusion
In this experiment, we successfully studied and implemented the while loop in Python.
We learned how loops help in executing repetitive tasks efficiently. We also understood the working of loop control statements like break and continue.
By performing different programs such as factorial calculation, Fibonacci series generation, palindrome checking, digit counting, and searching elements in a list, we gained practical knowledge of how loops are applied in real-world programming problems.
Thus, the concept of loops in Python was successfully studied and implemented.
