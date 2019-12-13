This is a simple code using the for loop with range and using file operation to read inputs from the file and to print the numbers from 1 to 99 which are divisible by 3, 5, 3 & 5 and calling the name fizz, buzz and fizzbuss respectively.
There was in error in Step 20, 21.
Updated step 20 from [with open('mifile.txt','r') as f:] to [with open('c:/Users/raj/code/wtfiswronghere/05_challenge/myfile.txt','r') as f:]--> gave the complete path name for the myfile and updated the file name.
Updated Step 21 from print 'i have created' to print ('i have created')
Updated myfile.txt. Changed the 3 row value from 99 to 100 since range takes the value 1 less than then mentioned value.