# Pranav-Guess
This is my small Project. Here the computer select any number between 1 and 100 then user has to guess the selected number. And then it display the attempts. 

import random
number=random.randint(1, 100);
attempt=0
print("Guess the number between 1 and 100") 

while True:
       guess=int(input("Enter your guess")) 
       attempt+=1;

       if guess < number:
          print("To low") 
       elif guess > number:
            print("To high") 
       else
            print(You guessed the number") 
            print("Attempt: ", attempt) 
            break

  
            
       
   
       
