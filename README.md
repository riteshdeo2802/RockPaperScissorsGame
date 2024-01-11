# RockPaperScissorsGame

Introduction:
The Rock-Paper-Scissors game is a classic hand game that is often used as a simple decision-making tool. In this theoretical description, we explore the design and implementation of a Rock-Paper-Scissors game using Java programming language. The primary goal of this project is to create an interactive and enjoyable console-based game where the user can play against the computer.

Objective:
The main objective of this project is to implement a user-friendly Rock-Paper-Scissors game that allows players to make their choices (rock, paper, or scissors) and compete against a computer opponent. The game follows the standard rules: rock beats scissors, scissors beat paper, and paper beats rock. The project aims to showcase the principles of Java programming, including user input handling, randomization, and conditional logic.

Components:

User Input Handling:
The game starts by prompting the user to enter their choice—rock, paper, or scissors. To enhance user experience, input is case-insensitive and can be entered in lowercase or uppercase. The game continues to loop until the user decides to exit by typing 'exit'.

Randomized Computer Choice:
The computer opponent's choice is determined using Java's Random class. The computer selects a random index from an array containing the possible choices (rock, paper, scissors). This randomness ensures unpredictability, making the game more challenging and entertaining.

Game Logic:
The game logic is implemented to determine the winner based on the user's choice and the computer's choice. The rules are straightforward: rock beats scissors, scissors beat paper, and paper beats rock. The logic incorporates conditional statements to compare the choices and declare the winner of each round.

Game Loop:
The core of the game is a continuous loop that allows the user to play multiple rounds until they decide to exit. After each round, the user is informed of the computer's choice and the outcome of the round (win, lose, or tie). The loop ensures a dynamic and engaging gaming experience.
