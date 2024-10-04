# Rock, Paper, Scissors - GUI Game 🎮

This is a simple Rock, Paper, Scissors game with a graphical user interface (GUI) built using Python and tkinter. The game allows you to play against the computer, and it keeps track of the scores for both the player and the computer. The game features images for Rock, Paper, and Scissors and provides a fun way to play this classic game.


## Features
- Full-Screen Window: The game launches in full screen for an immersive experience.
- Player vs. Computer: The player can choose Rock, Paper, or Scissors, and the computer will randomly select one.
- Score Tracking: The game keeps track of:
  - Player wins
  - Computer wins
  - Ties
- Graphical Feedback: The game shows images of Rock, Paper, and Scissors for both the player’s choice and the computer’s choice.
- Exit Button: Easily exit the game with the press of a button.
## How to Play
- Click one of the images (Rock, Paper, or Scissors) to make your selection.
- The computer will make its choice, and the game will display the result (Win, Lose, or Tie).
- The game will keep track of the scores for both the player and the computer.
- You can exit the game at any time by clicking the Exit button.
## Prerequisites
To run this game, you need:

- Python 3.x installed. You can download Python from here.
- The Pillow library for image processing. Install it by running:
```
pip install pillow
```
## Installation
  1. Clone the repository to your local machine:
  ```
  git clone https://github.com/yourusername/rock-paper-scissors-gui.git
  ```
  2. Navigate to the project directory:
  ```
  cd rock-paper-scissors-gui
  ```
  3. Make sure you have the images `rock.png` , `paper.png`, and `scissors.png` in the same directory as the script. If not, add them. You can download your own or find suitable images online.

  4. Run the game:
  ```
python rock_paper_scissors_gui.py
  ```
## File Structure
```
rock-paper-scissors-gui/
│
├── rock_paper_scissors_gui.py   # Main game script
├── rock.png                     # Image for rock
├── paper.png                    # Image for paper
├── scissors.png                 # Image for scissors
├── README.md                    # This README file
└── requirements.txt             # List of dependencies (Pillow)
```
## Game Logic
- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- If both the player and the computer choose the same option, it results in a Tie.

## Screenshots

## Built With
- Python - The core programming language used.
- tkinter - The standard Python interface to build the GUI.
- Pillow - Python Imaging Library to handle images for the game.

## How to Contribute
Feel free to submit issues and enhancement requests or fork the repository and submit pull requests. Contributions are welcome!

1. Fork it (https://github.com/Yashas711/Rock-Paper-Scissors-GUI-Game/fork)
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add some new feature`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a new Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Yashas R Yadav - GitHub
