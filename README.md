# Snake Water Gun Game using python
A simple game in python as play Snake, Water, Gun against the computer.

# How it works
internally, each choice is mapped with a number:
Value         Choice
'1'            Snake
'-1'           Water
'0'            Gun
The computer picks a value randomly using 'random.choice([1, -1, 0]) , the player's input ('s', 'w', or 'g') is mapped to the same scale,
and the two values are compared to determine the winner.

# How to run

when prompted, enter your choice:
- 's' for snake
- 'w' for water
- 'g' for gun

