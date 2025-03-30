# Guess-Game
Let's guess the number!
import random
number1 = random.randint(1,10)
guess1 = int (input("guess a number between 1 to 10:"))
if guess1 == number1:
    print ("\U0001F389 Good job!")
    print ("Nex Level")
else:
    print ("\U0000274CGame over The correct answer is:" , number1)
    exit()
number2 = random.randint(1,20)
guess2 = int (input("now guess a number between 1 to 20:"))
if guess2 == number2:
    print ("\U0001F389Good job!")
    print ("\U0001F3C6you win")
else: 
    print ("\U0000274CGame over The correct answer is:" , number2)
