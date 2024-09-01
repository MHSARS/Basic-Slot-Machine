This Python script implements a simple slot machine game where the user can deposit money, place bets on multiple lines, and spin the slot machine to win or lose money based on the outcome.

Key Features:

Configurable Slot Machine:

- The game has 3 rows and 3 columns, with four symbols (A, B, C, D) each having different frequencies and payout values.
- Symbols have specific counts and values, influencing the game's outcomes and potential winnings.

Betting System:

- Users can deposit money and decide how many lines (up to 3) they want to bet on.
- The betting amount per line is configurable, with limits set between a minimum ($1) and maximum ($100) bet.

Slot Machine Spin:

- The get_slot_machine_spin function randomly generates the outcome of the slot machine spin based on the symbol 
  distribution.
- Winning lines are determined by the check_winnings function, which checks if all symbols in a line match across the 
  columns.

User Interaction:

- The game prompts users to deposit money, select the number of lines to bet on, and place their bets.
- After each spin, the game displays the outcome, including the slot machine's visual layout, winnings, and the lines on 
  which the user won.

Game Loop:

- The game runs in a loop, allowing users to continue playing until they decide to quit or run out of balance.
- The current balance is updated after each spin, and the game ends when the user chooses to quit, displaying the final 
  balance.

How It Works:

Deposit and Betting: 

- The user starts by depositing money and then decides the number of lines to bet on and the amount per 
 line.

Spinning the Slot Machine:

- The game randomly generates symbols for each column and displays them. If a line has matching symbols, the user wins an 
  amount based on the symbol's value.
  
Winning and Losing: 
- After each spin, the user’s balance is updated based on their total bet and the amount won. The user can continue playing 
  or quit at any time.
  
Usage:

- This script is a simple implementation of a slot machine game, suitable for learning purposes or small-scale projects. It 
  demonstrates basic concepts such as user input handling, randomization, and simple game mechanics.
