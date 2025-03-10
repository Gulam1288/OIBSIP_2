# Number Guessing Game

The fun and easy project "Guess the Number" is a short Java project that allows the user to guess the number generated by the computer. The game involves the following steps:

1. The system generates a random number from a given range, say 1 to 100.
2. The user is prompted to enter their guess in a displayed dialogue box.
3. The computer then tells if the entered number matches the guessed number or if it is higher/lower than the generated number.
4. The game continues until the user guesses the number.

## Additional Features

- **Limited Attempts:** Limit the number of attempts a user has to guess the number.
- **Multiple Rounds:** Allow the game to be played in multiple rounds.
- **Score Display:** Show the user's score based on their performance.
- **Points System:** Award points based on the number of attempts taken to guess the number.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your system.
- A Java IDE or text editor (e.g., IntelliJ IDEA, Eclipse, VS Code).

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/gulam1288/OIBSIP-02.git
    ```
2. Navigate to the project directory:
    ```sh
    cd OIBSIP-02
    ```

## Usage

1. Compile the Java files:
    ```sh
    javac NumberGuessingGame.java
    ```
2. Run the application:
    ```sh
    java NumberGuessingGame
    ```

3. Follow the on-screen instructions to play the game.

## Code Structure

The main logic of the application is in the `NumberGuessingGame` class. The class uses a few key methods to manage the game flow:

- `generateRandomNumber()`: Generates a random number within the specified range.
- `getUserGuess()`: Prompts the user to enter their guess.
- `checkGuess(int guess)`: Checks if the user's guess is correct and provides feedback.
- `playGame()`: Manages the game loop and keeps track of rounds and scores.

## Example

Here's a simple example of how to interact with the game:

1. **Game Start:**

    ```
    Welcome to the Number Guessing Game!
    I'm thinking of a number between 1 and 100.
    Can you guess what it is?
    ```

2. **User Guess:**

    ```
    Enter your guess: 50
    ```

3. **Feedback:**

    ```
    Your guess is too high. Try again!
    ```

4. **Correct Guess:**

    ```
    Congratulations! You've guessed the number correctly.
    ```

## Acknowledgements

This project is part of my Java Development Internship at Oasis. Special thanks to my mentors and colleagues for their support and guidance.
