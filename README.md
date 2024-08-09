# Snake and Ladder Game

This is a simple console-based Snake and Ladder game implemented in C. The game supports two players and includes the classic snakes and ladders mechanics. The player who reaches position 100 first wins the game.


## Features

- Two-Player Mode: Players take turns to roll the dice and move their pieces on the board.
- Snakes and Ladders: The game includes several snakes and ladders:
  - Snakes: 25 to 9, 65 to 40, 99 to 1
  - Ladders: 13 to 42, 60 to 83, 70 to 93
- Victory Condition: The first player to reach position 100 wins.





## Getting Started

### Prerequisites

To compile and run the program, you'll need:

- A C compiler (like GCC)
- A command-line interface

### Installation
- Clone this repository to your local machine:

```bash
  git clone https://github.com/yourusername/snake-and-ladder-game.git
```

- Navigate to the project directory:

```bash
  cd snake-and-ladder-game
```

- Compile the program:
```bash
  gcc -o snake_ladder snake_ladder.c
```

- Run the program:
```bash
  ./snake_ladder
```





## How to Play

- Upon starting the game, you'll be presented with the following options:
  - Player 1 plays
  - Player 2 plays
  - Exit
- Players take turns to roll the dice by selecting their corresponding option.
- The game board is displayed after each turn, showing the current positions of both players.
- If a player lands on a snake or ladder, their position is adjusted accordingly.
- The game continues until one player reaches position 100 and wins.

### Example

```bash
        ** SNAKE AND LADDER GAME** 
        Coded By Parthiv Majumdar
Snakes:- 25 to 9, 65 to 40, 99 to  1.
Ladder:- 13 to 42, 60 to 83, 70 to 93.
Choose your option
1. Player 1 plays
2. Player 2 plays
3. Exit
```

- After selecting an option, the dice roll result is shown, and the player's position is updated on the board.
## Contribute

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or additional features are welcome!
## Acknowledgments

- Inspired by the classic Snake and Ladder board game.
- Thanks to the open-source community for their guidance and support.
