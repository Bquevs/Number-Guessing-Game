Number Guessing Game

A Python project where the program randomly selects a number between 1 and 100, and the player guesses with hints such as too high or to low.

How It Works
	•	The game picks a secret number between 1 and 100.
	•	Enter guesses until you find the correct number.
	•	After each guess, the game tells you if your guess is too high or too low.
	•	Type QUIT at any time to stop the game (the secret number will be revealed).
	•	Tracks the number of attempts, with a special message if you get it on the first try.

Example Run:

 Welcome to Number Game
I am thinking of a number between 1 and 100.
Enter a whole number 1 to 100, or type QUIT: u
Please enter a valid whole number between 1 and 100.
Enter a whole number 1 to 100, or type QUIT: 80
Your guess is too low.
Enter a whole number 1 to 100, or type QUIT: 90
Your guess is too high.
Enter a whole number 1 to 100, or type QUIT: 85
Your guess is too high.
Enter a whole number 1 to 100, or type QUIT: 82
Your guess is too low.
Enter a whole number 1 to 100, or type QUIT: 83
You have guessed the secret number in 5 attempts.

 Features
	•	Quit at any time with QUIT.
	•	Input validation (only whole numbers between 1 and 100).
	•	Tracks number of attempts.
	•	Fun “first try” message if you guess right immediately.

Why I Built This

This project was a way to practice Python fundamentals, including:
	•	User input handling and validation
	•	Loops and conditionals
	•	Random number generation
	•	Basic game logic with win/lose conditions

It’s a starting point for building more interactive games while strengthening programming habits like clean code, input checks, and clear feedback for the user.
