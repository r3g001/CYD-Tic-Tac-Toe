# CYD-Tic-Tac-Toe
An implementation of Tic-Tac-Toe on a CYD using ESPHome

## Description
This is a simple project as an experiment with an ESP32 CYD (Cheap Yellow Display).

The aim was to create a Tic-Tac-Toe (naughts & crosses) game using the touch screen.

When initialised, a blank grid is displayed and "X" always makes the first move. Pressing one of the squares on the grid will enter an "X". The next player presses a blank square and it will show a "O".

Play continues, alternating between players until either, no blank sqaures are left, or a player completes a line of 3 of their tokens.

When the game ends, the message area at the top indicates the winner and the game auto-resets after a 5 second delay.

## Hardware
This project was built using an ESP32-2432S024R, which is the slightly smaller version of the more standard ESP32-2432S028R.
