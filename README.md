# 4X4-TIC-TAC-TOE-with-Deep-Learning
This project includes a 4x4 Tic-Tac-Toe game that is equipped with **custom deep learning** that can beat humans. The game becomes more aggressive whenever a game is finished as the algorithm develops on the history of games played.

## 4X4 Tic-Tac-Toe
An interactive 4×4 Tic-Tac-Toe game for a person to play against a computer. The game consists of a 4×4 grid. To win, a player must mark 4 of his/her marker on 4 grids that line up vertically, horizontally or diagonally.

Custom algorithm was used that was built from scratch that differentiates one solution from another on the no. of steps, step grid or both - C++ language

## DETAILED DESCRIPTION:
The implementation of the game is in *CPP language*.
There project encompasses 4 classes – LinkedList, Multi , DeepLearner, and GameLogic.

  - **Multi** class is used for multiplayer 4X4 Tic-Tac-Toe by utilizing LinkedList class.
  - **DeepLearner** handles all the database creation, deletion, and updation operations via custom linked list.
  - **GameLogic** class utilizes database provided by DeepLearner, and stimulates the game of CPU.

Although, code has descriptive variables, and is self-explanatory; there are some inline comments for explanation.

## GAMEPLAY DETAILS:
**Single player mode** - encorporates the custom deep learning algorithm where the CPU player becomes more *aggressive* upon the *history of games*. The games will probably end up in a draw rather than winning at a point or user may win in the first few games.
**Multiplayer mode** - encorporates the two player 4X4 Tic-Tac-Toe that asks for name, and then each player gets their turn until a win/lose occurs or a draw.
**Login** - This is an additional feature that creates account for highscore names, and records.
**High-score** - The best players of the game are recorded here. The high-score is calculated by the time that is consumed for the completion of game.
**How to play** - This tells the user, how the to play tic tac toe. This obviously isn't required as only a cave person wouldn't know of this! But, we still added this feature.
**Exit** - Exits the game

## HOW TO RUN:
Compile and run the source code in command line or IDE having CPP in extension/system.
UI will be shown where you play the game.
The user is first asked to enter login details to actually enter the game menu.
Then user selects whether he/she wants to play single player, multi player, see high-score, see how to play or exit the game.

### NOTE:
> This was a group project where I was the leader, and I built, and managed the DeepLearner class, GameLogic class, solutions filing, high-score filing, QA testing to make sure there were no errors, and many more. My group member were: (*Abdul Rafay Syed, and Sarfaraz Ali*). Abdul was responsible for the multiplayer class,  LinkedList class, and the main compilation. Sarfaraz made the login system along with its filing.
