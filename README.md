# PianoTiles-Bot
This script is written in Python and uses the PyAutoGUI and Win32Api libraries to automate the Piano Tiles Game.

## Working

Script continuously check pixel value of 4 different cordinates, if any of them is 0.0.0 i.e black, it simulates a mouse click 15px below it.
Some minor adjustments are done to make it faster and facilitate higher difficulty levels.

You can check the comments for basic description.

## Setup

1. Clone the repository to your machine using the following command:

    `git clone https://github.com/adhirajpandey/PianoTiles-Bot`
  
2. Install all the requirements:
  `pip install -r requirements.txt`
  
3. Open game, and ensure that the game window is located on the left side of the screen as shown below else you can manually set pixel cordinates of tiles using PyAutoGUI mouseInfo().
4. Run the application using `python main.py` and start the gameplay after scripts start.

# Sample
  
  ![piano](https://user-images.githubusercontent.com/87516052/213633200-89cf7ecd-e98e-40ea-8733-684bf748b6b9.gif)
