This is a simple code using the for loop with Class and Object concept to print the numbers from 1 to 99 which are divisible by 3, 5, 3 & 5 and calling the name fizz, buzz and fizzbuss respectively.
The error was method did't had self keyword. The created object will be reffered inside the method via the self keyword.
So Updated line 15 from def fizzbuzz(max_num): to def fizzbuzz(self,max_num):