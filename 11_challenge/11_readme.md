This is a simple code using the for loop with range to print the numbers from 1 to 99 which are divisible by 3, 5, 3 & 5 and calling the name fizz, buzz and fizzbuss respectively.
There was no error but the if loops were not in order. For the iteration, the order goes for if and elif. Since the condition elif i%3==0 and i%5==0: was in 3rd condition, the iteration was not able to check whethr the number is divisible by both 3 & 5.
Updated the if statements and arranged in order:
        if i%3==0 and i%5==0:
            print(i,"fizzbuzz")
        elif i%3==0:
            print(i,"fizz")
        elif i%5==0:
            print(i,"Buzz")