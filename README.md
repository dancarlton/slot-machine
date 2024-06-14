# Slot Machine Project

Welcome to the Slot Machine Project! This project is a simple yet engaging slot machine game that runs entirely in your terminal. It is built using only JavaScript and provides a fun and interactive way to play a slot machine game in the command line.

## Features

- **Randomized Results**: Each spin generates a random combination of symbols.
- **Interactive Gameplay**: Prompts guide you through the game, enhancing user experience.
- **Simple and Fun**: A straightforward game designed to entertain.

## Technologies Used

- JavaScript
- Node.js

## High-Level Code Description

This slot machine game involves the following steps:

1. **Deposit Some Money**: The user is prompted to enter a deposit amount.
2. **Determine Number of Lines to Bet On**: The user chooses the number of lines to bet on (1-3).
3. **Collect a Bet Amount**: The user enters the total bet amount.
4. **Spin the Slot Machine**: The slot machine reels spin and generate a random combination of symbols.
5. **Check If the User Won**: The game checks if the user has won based on the symbols.
6. **Give the User Their Winnings**: The user's winnings are calculated and displayed.
7. **Play Again**: The user can choose to play again.

### Code Breakdown

- **deposit**: Prompts the user to enter a deposit amount and validates it.
- **getNumberOfLines**: Prompts the user to enter the number of lines to bet on and validates the input.
- **getBet**: Prompts the user to enter the bet amount and ensures it does not exceed the balance divided by the number of lines.
- **spin**: Randomly generates the symbols for each reel.
- **transpose**: Converts the reels into rows to make it easier to check for winnings.
- **printRows**: Prints the rows of symbols.
- **getWinnings**: Calculates the winnings based on the bet and the number of lines.
- **game**: Manages the overall game flow, including prompting the user to play again or ending the game when the balance is zero.


## Getting Started

To get started with the Slot Machine project, follow these steps:

1. **Clone the Repository**:

   ```sh
   git clone https://github.com/dancarlton/slot-machine.git
   ```

2. **Navigate to the Project Directory**:

```sh
    cd slot-machine
```

3. **Install Node.js**:
   Make sure you have Node.js installed on your machine. If not, download and install it from [Node.js](https://nodejs.org/).

4. **Run the Slot Machine**:
   ```sh
   node index.js
   ```

Once you run node index.js, you will be prompted to start the slot machine. Follow the on-screen instructions to enjoy the game!
