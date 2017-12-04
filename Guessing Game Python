# This is a guessing game
import random
print('Hello, what is your name?')
name = input()
secretnumber = random.randint(1,20)
print('Well, ' + name + ', I am thinking of a number between 1 and 20. Take a wild guess!')
#ask the player to guess six times
for guesstaken in range (1,8):
    print('Take a guess!')
    guess = int(input())
    if guess < secretnumber:
        print('Your guess is too low, Try again.')
    elif guess > secretnumber:
        print('Your guess is too high, Try again.')
    else:
        break # this condition  is the correct guess!
if guess == secretnumber:
    print('Great job ' + name + '! You guessed my number in 5 guesses!')
else:
    print('Nope, the number I was thinking of was' + str( secretnumber))
print('Thanks for playing!')
