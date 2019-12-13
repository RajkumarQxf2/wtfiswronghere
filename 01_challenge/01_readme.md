This is a simple code using the for loop with range to print the numbers from 1 to 99 which are divisible by 3, 5, 3 & 5 and calling the name fizz, buzz and fizzbuss respectively.
The error was in line 27 where assignment operator (=) was present instead of comparison operator (==).
Updated line 27 from elif i%num1=0: to elif i%num1==0: