

# Game in greenfoot

This is an interactive game inspired by the classic **MazeWorld** and the anime **One Piece**. In this game, players navigate through mazes filled with enemies, points, and lives. Each level builds on the previous one, carrying over the player's score and lives to increase the challenge and engagement.

## Game Features

### Tracks and Levels
- **MyWorld**: The first level of the game, where the initial maze is generated. The player, enemies, points, and lives are placed strategically within the maze.
- **MyWorld2**: The second level, featuring a new maze layout, different enemies, and additional boosters. The player's score and lives carry over from the previous level.

### Characters and Objects
- **OnePiece_ship**: The main player character, equipped with lives and points. This class also contains most of the core gameplay methods.
- **Enemies**: The game's main adversaries, implemented with two primary movement patterns:
  - **EnemyWalker**: A subclass of enemies with vertical or horizontal movement constrained between walls.
  - **Wave**: Another subclass that enables enemies to move horizontally in a repetitive pattern, traveling from one end of the maze to the other.
- **TreasureBoost**: Items that provide bonuses to the player, appearing in both the first and second levels.

### Visual Elements
- **Block1** and **Block2**: Images used for creating the first track's maze design.
- **Heart**: An image representing game lives.

### Interface and Screens
- **InstructionsScreen**: Shows the game instructions. Start the game by pressing the space bar.
- **YouLoseScreen**: Displays an image indicating that the player has lost.
- **YouWinScreen**: Shows a win message, including the final score.
- **YouWinFinal**: An object in the second level. When touched by the player, it triggers the win message and ends the game.

### Mechanics and Display
- **Movers**: Contains three movement methods used by **OnePiece_ship** and **Enemies**.
- **Score**: Displays the player's score throughout the game and transfers it from the first level to the second.
- **NextLevel**: A transition object that takes the player from the first level to the second, carrying over their lives and score.

## How to Play
1. Open the game and review the instructions on the **InstructionsScreen**.
2. Press the space bar to start.
3. Navigate through the maze, avoiding enemies and collecting points and lives.
4. Complete the first level and progress to the second with your accumulated score and lives.
5. Reach the **YouWinFinal** object in the second level to win the game.



Enjoy navigating through challenging mazes, avoiding enemies, and collecting treasures to increase your score and win the game!


