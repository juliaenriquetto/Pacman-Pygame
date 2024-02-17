# Pacman-Pygame: A python game for raspberry pi :joystick:
![gamescreen](https://github.com/juliaenriquetto/pacman-pygame/blob/main/gamescreen.jpeg)

  A Python game to run on Raspberry Pi. A customized version of Pacman, with the teachers' photos as ghosts and the Cotuca logo as Pacman.

## How does it work?
  The ghosts have pre-programmed movement, so they don't follow the Cotuca character. It works like the real Pac-Man; if you touch a ghost, you lose the game and the following message appears: 'Poxa, pegou DP - Oops, you failed a course.' If you don't touch any ghosts and eat all the yellow dots, totaling 209 points, you win the game and the following message appears: 'Parabéns, você passou de ano! - Congratulations, you passed the year!'".

## To run:
- You need to have the Raspberry Pi; 
- Open a text editor such as Nano or Thonny on your Raspberry Pi;
- Open the terminal on your Raspberry Pi;
- Navigate to the directory where you saved the Python file;
- Install Necessary Libraries: For Pygame, you can install it using pip:
```
  pip install pygame
```
- Run the Code: write pacman.py, and run it using Python
```
python pacman.py
```

You can interact using the keyboard (up, down, left, and right keys).
