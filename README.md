# Guess The Number Game

This simple Java-based Guess The Number game challenges players to guess a randomly generated number within 10 attempts. It provides hints to guide the player closer to the correct number.

## How to Play

1. **Objective**: Guess the randomly generated number within 10 attempts.

2. **Game Rules**:
    - The system generates a random number between 0 and 100.
    - You have 10 chances to guess the correct number.
    - After each guess, the system provides hints to guide you:
        - If your guess is greater than the generated number, it prompts you to try a smaller number.
        - If your guess is smaller than the generated number, it prompts you to try a greater number.

3. **Getting Started**:
    - Run the `GuessTheNumber.java` file in a Java-supported environment.

4. **Instructions**:
    - Enter a number between 0 and 100 when prompted.
    - Based on the hints provided, adjust your guesses to reach the correct number.

5. **Winning**:
    - If you guess the number within 10 attempts, you win!
    - Your score is calculated based on the number of attempts remaining out of 10.

## Code Overview

### Classes:
- `Game`: Manages the game logic, including generating a random number, taking user inputs, and checking correctness.
- `GuessTheNumber`: Implements the game interface, interacts with users, and runs the game loop.

### How the Game Works:
- The system generates a random number between 0 and 100.
- Players input their guesses.
- The game provides hints if the guess is not correct.
- Players win if they guess the number within 10 attempts.

### Note:
- This code provides a basic structure for a Guess The Number game and can be expanded upon for additional features or enhancements.

Enjoy the game!
