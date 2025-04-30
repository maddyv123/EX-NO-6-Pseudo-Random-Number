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

import random

# Generate a pseudorandom integer between a range
    random_int = random.randint(1, 100)
    print(f"Pseudorandom Integer: {random_int}")

# Generate a pseudorandom floating-point number between 0 and 1
    random_float = random.random()
    print(f"Pseudorandom Float (0-1): {random_float}")

# Generate a pseudorandom floating-point number in a given range
    random_uniform = random.uniform(10, 50)
    print(f"Pseudorandom Float (10-50): {random_uniform}")

# Generate a pseudorandom choice from a list
    choices = ['apple', 'banana', 'cherry', 'date']
    random_choice = random.choice(choices)
    print(f"Pseudorandom Choice: {random_choice}")

# Generate a pseudorandom sample of multiple items
    random_sample = random.sample(choices, 2)
    print(f"Pseudorandom Sample: {random_sample}")

# Shuffle a list randomly
    random.shuffle(choices)
    print(f"Shuffled List: {choices}")

# Generate a random seed for reproducibility
    random.seed(42)
    seeded_int = random.randint(1, 100)
    print(f"Seeded Random Integer (42): {seeded_int}")

# Generate cryptographically secure random numbers (optional)
    import secrets
    secure_random = secrets.randbelow(100)
    print(f"Cryptographically Secure Random Integer: {secure_random}")



# OUTPUT:
![Screenshot 2025-03-27 092720](https://github.com/user-attachments/assets/50142cc4-5124-4927-a05d-e46ac7946015)


# RESULT:
The code executed successfully!
