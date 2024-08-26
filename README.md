# Simulation of the slot machine game
This program simulates a slot machine game where the player can deposit money, choose how many lines to bet on, and place a bet on each line. The game then spins the slot machine and checks if the player wins based on the symbols that appear in the slots. The player can continue playing until they choose to quit or run out of money.

# Key Components:
 - Deposit Functionality: The player starts by depositing a certain amount of money to play the game.
 - Betting on Lines: The player can choose to bet on up to 3 lines (horizontal rows on the slot machine).
 - Bet Amount: The player places a bet on each line, and the total bet is the product of the bet amount and the number of lines.
 - Slot Machine Spin: The slot machine randomly generates symbols for each of the three columns.
 - Winning Calculation: If all symbols in a line match, the player wins an amount based on the symbol's value multiplied by their bet.
 - Game Continuation: After each spin, the player’s balance is updated based on their winnings and total bet. The player can continue playing or quit the game.

# Simulation:
The program begins by asking the player how much money they would like to deposit:

  - What would you like to deposit? $100

The player deposits $100, which becomes their initial balance.
Next, the player is asked how many lines they want to bet on:

  - Enter the number of lines to bet on (1-3)? 2

The player chooses to bet on 2 lines. Then he is prompted to enter their bet amount per line:

  - What would you like to bet on each line? $10

The player decides to bet $10 per line. Since they are betting on 2 lines, the total bet is:

  - You are betting $10 on 2 lines. Total bet is equal to: $20

The slot machine spins and generates the following output:

      C | D | C
      B | C | B
      A | A | A

This represents the symbols on each of the three rows.
The program checks if there are any winning lines. In this case, the third row has three "A" symbols, which means the player won on that line. The value of "A" is $5 per symbol, so the winnings for that line are:

  - You won $50.
  - You won on lines: 3

The player won $50 because he bet $10 on a line where all symbols matched.
The player’s balance is updated:

  - Current balance is $130
  - Press enter to play (q to quit).

Now, the player has $130 and can choose to either spin again or quit the game.
If the player decides to quit, the program will end with:
  
  - You left with $130
