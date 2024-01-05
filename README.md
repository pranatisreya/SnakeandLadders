# MINI PROJECT REPORT
# SNAKE AND LADDER GAME USING PYTHON!



# ABSTRACT
Game development uses Python to scripts small codes that automate tasks . Python’s 
framework provides gaming development for Windows, Mac, Linux, iOS, and Android 
platforms. The language is often used for making video games that can be played on PC as well as mobile devices.It’s easy to create entire video games using this one language and existing games can add scripting engines to make versioning improvements and modifications. Python is used to provide add on game functionality, create 3D graphics, and script various parts of games. 

Python GUI programmers can use windows, icons, and menus to carry out certain commands 
for games or programs.The Snake And Ladder Program In Python is a totally practical laptop software venture that covers all the factors that IT college students and computer-associated publications would require for his or her university tasks or for enjoyment time purposes. Snakes and ladders is an antique Indian board sport this is now taken into consideration a conventional across the world. 

It is performed with greater gamers on a board with numbered, gridded squares. Snakes and ladders pass at some point of the board, connecting specific squares. The gamers navigate the board with the aid of using rolling a dice. A participant who lands on a ladder advances one rectangular up the board, while a participant who lands on a snake ought to go back to the preceding position. This Snake And Ladder Game In Python is beneficial for mastering new talents and working towards Python Game development. This venture is pretty beneficial, and the idea and common sense of the venture are easy to grasp. We may also create highly fascinating games with the Python programming language. The snake and ladder game is one of them. The project system file comprises resource files as well as a Python script. The graphics of the game are smooth, and the controls are simple.

How to play:
The Snake And Ladder Game Python Code participant should roll the cube on the begin of the sport, and after doing so, the sport will flow the token within the path indicated via way of means of the die range. The engagement is as real because it receives. The participant additionally receives every other threat to roll the cube if she or he gets a 6 range. Each participant locations their counter at the ‘begin here’ spot. It’s a recreation of taking turns rolling the cube. Increase the range of areas to your counter via way of means of the quantity  of areas proven at the cube. You can flow your counter up the ladder if it lands on the bottom. 

If your counter lands on a snake’s head, you should slide right all the way down to the snake’s tail. The participant who arrives on the closing rectangular of the tune is the champ. This Snakes and Ladders Game includes python document scripts (snakes_ladders.py), assets documents and sound documents. The gameplay of the system, that’s the person can select an choice both to play a couple of player or with the computer. There are portions of stepping stools and snakes in the sport which reasons the participant to replace or minimization the rectangular number. Python Game Projects With Source Code Before you begin on the way to create Snakes and Ladders Game in Python, ensure which you have PyCharm IDE and Pygame set up in your desktops. In the code below. Which is for the random() function, which generates 
random numbers between 0 and 1.
- Dictionary
- List
- Generating random number
- Selecting a Random value from a list
- Adding wait/sleep in program
- Conditional Statements i.e. IF and ELSE
- Getting input from user


TABLE OF CONTENTS

ABSTRACT v
1. INTRODUCTION
1.1 Introduction 1
1.2 Application 1
1.3 Problem statement 1
1.4 Aim and objective 2

2. SYSTEM REQUIREMENTS
2.1 Functional requirements 3
2.2 Non-functional requirements 4
2.3 Software requirements 4
2.4 Hardware requirements 5

3. IMPLEMENTATION 6

4. RESULTS AND TESTING 19

6. CONCLUSION AND FUTURE SCOPE
 6.1 Conclusion 22
 6.2 Limitations 22
 6.3 Future Scope 22

7. BIBLIOGRAPHY 23

# 1. INTRODUCTION

## 1.1 INTRODUCTION

The Snake And Ladder Program In Python is a totally useful computer based task that covers all the factors that IT college students and computer-associated guides would require for his or her university tasks or for enjoyment time purposes. Snakes and ladders is an vintage Indian board recreation this is now taken into consideration a conventional across the world. It is performed with or greater gamers on a board with numbered, gridded squares. Snakes and ladders cross all through the board, connecting exceptional squares. The gamers navigate the board through rolling a dice. A participant who lands on a ladder advances one rectangular up the board, while a participant who lands on a snake should go back to the preceding position. 
This Snake And Ladder Game In Python is beneficial for getting to know new talents and 
training Python Game development. This task is pretty beneficial, and the idea and common sense of the task are easy to grasp. The supply code is open supply and unfastened to use. Simply scroll down and click on the down load option.


## 1.2 APPLICATION
This SnakeAnd Ladder Game Using Python players navigate the board by rolling a dice. A 
player who lands on a ladder advances one square up the board, whereas a player who lands on a snake must return to the previous position. The goal of the game is to get to the last square. The game is a famous children’s race that is dependent on pure luck.

## 1.3 PROBLEM STATEMENT
The gist of the problem statement is that we need to create a snake and ladder game. The game will have multiple snakes and ladders and there will be multiple people playing the game. The game is played automatically based on certain rules and ends when a player wins. Here we have decided that we have keep a Driver class to take input from the user and a SnakeAndLadderService to orchestrate the game.

## 1.4 AIM AND OBJECTIVE
The main aim is to provide some platform of entertainment to the people through virtual mode, instead of playing with the original board. The people from far places can be connected easily and play. The game can allow maximum of 4 people to play at a time. We can play the game n number of times until we get satisfied. This is a ancient game where our before generation used to play. So, mainly to put the record of it, the game is now available in online.

# 2. SYSTEM REQUIREMENTS
## 2.1. FUNCTIONAL REQUIREMENTS
Number of snakes (s) followed by s lines each containing 2 numbers denoting the head and tail positions of the snake.
- Number of ladders (l) followed by l lines each containing 2 numbers denoting the start and end positions of the ladder.
- Number of players (p) followed by p lines each containing a name.
After taking these inputs, you should print all the moves in the form of the current player name followed by a random number between 1 to 6 denoting the die roll and the initial and final position based on the move.
Format: <player name> rolled a <dice value> and moved from <initial_position> to 
<final_position>
When someone wins the game, print that the player won the game.
Format: <player_name> wins the game
Rules of the game
- The board will have 100 cells numbered from 1 to 100.
- The game will have a six sided dice numbered from 1 to 6 and will always give a 
random number on rolling it.
- Each player has a piece which is initially kept outside the board (i.e., at position 0).
- Each player rolls the dice when their turn comes.
- Based on the dice value, the player moves their piece forward that number of cells. Ex: 
If the dice value is 5 and the piece is at position 21, the player will put their piece at 
position 26 now (21+5).
- A player wins if it exactly reaches the position 100 and the game ends there.
- After the dice roll, if a piece is supposed to move outside position 100, it does not move.
- The board also contains some snakes and ladders.
- Each snake will have its head at some number and its tail at a smaller number.
- Whenever a piece ends up at a position with the head of the snake, the piece should go
down to the position of the tail of that snake.
4
- Each ladder will have its start position at some number and end position at a larger 
number.
- Whenever a piece ends up at a position with the start of the ladder, the piece should go 
up to the position of the end of that ladder.
- There could be another snake/ladder at the tail of the snake or the end position of the 
ladder and the piece should go up/down accordingly.


## 2.2. NON FUNCTIONAL REQUIREMENTS
The board size can be customizable and can be taken as input before other input (snakes, 
ladders, players).In case of more than 2 players, the game continues until only one player is 
left.On getting a 6, you get another turn and on getting 3 consecutive 6s, all the three of those 
get cancelled. On starting the application, the snakes and ladders should be created 
programmatically without any user input, keeping in mind the constraints mentioned in rules.
Once the project is deployed, since media queries are used, the website can be easily accessed 
on any device such as a laptop, or phone, or tablet. This makes the project portable. 
Furthermore, since our website does not take any personal or confidential information from the 
user, it is secure. 


## 2.3 SOFTWARE REQUIREMENTS
Before you start on how to create Snakes and Ladders Game in Python, make sure that you 
have PyCharm IDE and Pygame installed in your computer.
By the way if you are new to python programming and you don’t know what would be the 
Python IDE to use, I have here a list of Best Python IDE for Windows, Linux, Mac OS that will suit for you. I also have here How to Download and Install Latest Version of Python on Windows.

Importing Random Module
In the code below. Which is for the random() function, which generates random numbers 
between 0 and 1.
Installing pip package
PIP is a package manager for Python packages, or modules if you like. Mainly in our project 
pip to get pygame module.
Initially pip software used be installed and then we can proceed further to install pygame 
module.
Importing Pygame Module

In the code given below, which is pygame library is an open-source module for the Python 
programming language specifically intended to help you make games and other multimedia 
applications. Pygame can run across many platforms and operating systems.(Snakes and 
Ladders Game in Python). This module is used for the graphics color use in a text.(Snakes and 
Ladders Game in Python)
In the code given below, which is for the function of a players that you want to choose either 
single player, two player, three player, or four player and it is color design .
Language/s Used: Python (GUI 
Based)
Python version 
(Recommended): 3.8 or 3.9
Type: Desktop 
Application


## 2.4. HARDWARE REQUIREMENTS
The hardware required for constructing this mini task is pretty simple. To enforce any software program task, one calls for a pc on which the task may be run and as a result be used. A Windows PC and Windows 7 because the running machine become used for growing this task as it’s miles strong and reliable.


# 4.RESULTS AND TESTING
The following are the images of the ouput screen when the code is executed.The 
game can be played by choosing the respective given options.

 
 
Here , the number of players can be chosen until 4 players

Single player
2 Players

 
 
 
4 Players
3 Players

# 6 CONCLUSION AND FUTURE SCOPE
## 6.1 CONCLUSION
The present study has been made to suggest and develop the project in python. We may also create highly fascinating games with the Python programming language. The snake and ladder game is one of them. The project system file comprises resource files as well as a Python script. The graphics of the game are smooth, and the controls are simple.This project helps to know some python implementations, some pre-defined modules like pygame, random module ,time module etc. This Snake And Ladder Game In Python is useful for learning new skills and practicing Python Game development. This project is quite useful, and the concept and logic of the project are simple to grasp. The source code is open source and free to use. Simply scroll down and click the download option.

In conclusion, learning while playing can be used as a strategy and appropriate teaching methods for students with learning difficulties. This is to enhance their cognitive development and to build up their interest to be involved actively in learning.

## 6.2 LIMITATIONS
The limitations are nothing but pygame installation is must to implement this project. This game is only restricted to 4 players. Snake and ladder do not form an infinite loop and there won’t be multiple snakes/ladders at same start and end point. GUI based application and implementation of the installation must be done properly.

## 6.3 FUTURE SCOPE
Project scope is the part of project planning that involves determining and documenting a list of specific project goals, deliverables, tasks, costs and deadlines.The project file contains python scripts (snakesladders.py) and other image files. This is a GUI based board game which is very easy to understand and use. In order to run the project, you must have installed python and Pygame on your PC. This is a 2D GUI Based game written for the beginners. Snakes and Ladders Game in Python project with source code is free to download. This algorithm is very easy and fun to use as it can also be used to make a simple Snake and Ladder game for small projects. The whole code structure is the marking of the cells has to be visualized.

# 7 BIBLIOGRAPHY
[1] https://en.wikipedia.org/
[2] https://code-projects.org/snakes-and-ladders-game-in-python-with-source-code/
[3] https://www.geeksforgeeks.org/
[4] https://codingshiksha.com/python/python-3-tkinter-snake-and-ladder-game-script-usingpillow-library-gui-desktop-app-full-project-for-beginners/
[5] https://www.docsity.com/en/project-report-on-snakes-ladders/2587404/
[6] https://pythoncircle.com/post/676/text-based-snake-and-ladder-game-in-python/
