# README.MD - SI 507 Project 4
### Description: Learning Pyglet with a Breakout Game
### Python Version: Python3
---
## Description
SI507_project4.py is an application that utilizes Pyglet, a multimedia library for Python that lets users create games and other applications using media files like .png, .jpg, and .gif, along with sound and video files.

## Controls & Gameplay

**W** Move Paddle Up

**S** Move Paddle Down

**P** Pause/Unpause

**Q or Escape** Quit

**Gameplay** Users move the paddle to bounce the ball toward all faceheads. Destroy all the faceheads to win the game. If your paddle misses the ball, the game will reset and you will need to press the P Pause button to start again.

## Modifications ##

I made some adjustments to the art assets, converting the blocks to faceheads and adding a little style to the paddle. The ball was also turned into a baseball.

I modified the scoring to keep track of the number of blocks hit with the record_score function, which is displayed in both the terminal window and on the games interface. Once all the blocks are cleared, the Score displays "Game Over".

I also modified the velocity of the ball's speed by increasing it every 10 times a block is hit within the game. It can get quite challenging!

---
## Files Included
1. **SI507_project4.py:** Utilized to run the modified Breakout application

2. **ball.png:** Image asset used to create the game's ball.

3. **brick.png:** Image asset used to create the game's destroyable bricks.

4. **paddle1.png:** Image asset used to create the game's player paddle.

5. **vertical_wall.png:** Image asset used to create the game's vertical wall.

6. **horizontal_wall.png:** Image asset used to create the game's horizontal wall.

7. **requirements.txt:** The installed python modules that are required to run this project.

---
## Installing Pyglet

Pyglet can be installed by running the command:

> $ pip install pyglet

Further information can be found at https://bitbucket.org/pyglet/pyglet/wiki/Home

---
## Requirements.txt / Dependencies

The following dependencies were ran in a virtualenv for the python files included in this repo:


- astroid==2.2.5
- beautifulsoup4==4.7.1
- bs4==0.0.1
- future==0.17.1
- isort==4.3.16
- lazy-object-proxy==1.3.1
- mccabe==0.6.1
- pyglet==1.3.2
- pylint==2.3.1
- six==1.12.0
- soupsieve==1.9
- typed-ast==1.3.1
- virtualenv==16.4.3
- wrapt==1.11.1

