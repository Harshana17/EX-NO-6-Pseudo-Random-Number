# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.

Seed the random number generator using the current time(i.e) rand(time(0));

Get the number of randon number to generate.

Pass the value for number of iterations and print the numbers.

End the program.

# PROGRAM:
```
import random
import time

random.seed(int(time.time()))
count = int(input("Enter the number of random numbers to generate: "))
min_val = int(input("Enter the minimum value: "))
max_val = int(input("Enter the maximum value: "))
print("Pseudorandom numbers:")
for _ in range(count):
    random_number = random.randint(min_val, max_val)
    print(random_number)
```

# OUTPUT:

<img width="1914" height="1037" alt="image" src="https://github.com/user-attachments/assets/491b24db-af18-4392-a10f-5449d30bdf15" />


# RESULT:
The program is executed successfully
