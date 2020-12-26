# simple-python-game
"""this is a simple pythin project which is like a fun game"""
#guess the number
n = """I have created a game called "guess the number" simple
python fun code"""

n = 34
number_of_guesses = 1
print("number of guesses is only limited 9 times")
while (number_of_guesses<=9):
    guess_number = int(input("guess the number:\n"))
    if guess_number<34:
        print("you have entered lesser number.\n")
    elif guess_number>34:
        print("you have entered greater number.\n")
    else:
        print("you won \n")
        print(number_of_guesses, "no. of guesses you took to finish")
        break
    print(9-number_of_guesses,"number of guesses left")
    number_of_guesses = number_of_guesses+1

if (number_of_guesses>9):
    print("game over,you lose")n = 25
