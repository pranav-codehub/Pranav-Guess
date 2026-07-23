# Pranav-Guess
Here the computer select any number between 1 and 100 then user has to guess the selected number. And then it display the attempts. 

#Here is my code. 

import random

number = random.randint(1, 100)
attempts = 0

print("Guess a number between 1 and 100")

while True:
    guess = int(input("Enter your guess: "))
    attempts += 1

    if guess < number:
        print("Too low!")
    elif guess > number:
        print("Too high!")
    else:
        print("Congratulations! You guessed the number.")
        print("Attempts:", attempts)
        break
