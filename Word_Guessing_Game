# HunarIntern1_word_guessing_gaame
import random
name = input("What is your name? ")
print("Good Luck ! ", name)
words = ['computer', 'science', 'programming','python', 'mathematics', 'game', 'ethical','hacking', 'cloud', 'java']
word = random.choice(words)
print("Guess the Letter")
guesses = ''
turns = 10
while turns > 0:
    failed = 0

    for char in word:

        if char in guesses:
            print(char, end=" ")

        else:
            print("_")
            failed += 1

    if failed == 0:
        print("Congratulations!You Won the Game")
        print("The word is: ", word)
        break
    print()
    guess = input("guess a letter:")
    guesses += guess

    if guess not in word:
        turns -= 1
        print("Wrong Guess")
        print("You have", + turns, 'more guesses')
        if turns == 0:
            print("You Loose the game")
