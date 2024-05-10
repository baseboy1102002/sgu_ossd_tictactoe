# Welcome to our project!

Hi! We're student in major Information Technology at Sai Gon University. This is our project about building a Tic tac toe game that run on Desktop using Python.


## Introduction website

This is our introduction's website, you can find more about our team members, and have a contact to us in the future . [visit here](https://baseboy1102002.github.io/sgu_ossd_tictactoe-web/)

## Download & Install Guild

> You can download the game and install in 2 ways: via Git or just download the source code.

### Requirements
Your local machine must have pre install Python3. You can download Python in [official site](https://www.python.org/downloads/)

### Download the game

- Download via Git

```
git clone https://github.com/baseboy1102002/sgu_ossd_tictactoe.git
```

- Download the source code

Our official release: [v.1.0](https://github.com/baseboy1102002/sgu_ossd_tictactoe/releases/tag/v1.0) 

### Install and run the game
> This project has 2 file you can run according to 2 player mode. The Server (for player1) and the Client (for player2).

#### Run the Server (player1)
> Before you can play, it need to set the IP Address correct to your IPv4 in the file player1.py. Find this line and replace the value to your value. 
> `serverAddress = 'YOUR_IPv4_ADDRESS`

- On Windows
```
cd ~/{YOUR_PATH_TO_GAME}/TicTacToe
ipconfig (get your ip address)
notepad player1.py (replace your IPv4) -> crtl+s
python player1.py
```
- On Linux

```
cd ~/{YOUR_PATH_TO_GAME}/TicTacToe
hostname -I (get your ip address)
vim player1.py (replace your IPv4) -> :wq (save file)
python3 player1.py
```

#### Run the Client (player2)

- On Windows
```
cd ~/{YOUR_PATH_TO_GAME}/TicTacToe
python player2.py
```

- On Linux
```
cd ~/{YOUR_PATH_TO_GAME}/TicTacToe
python3 player2.py
```

## Gameplay
- **Player1**
![Player1's screen](https://baseboy1102002.github.io/sgu_ossd_tictactoe-web/assets/imgs/tictactoe%20p1.jpg)

- **Player2**
![Player1's screen](https://baseboy1102002.github.io/sgu_ossd_tictactoe-web/assets/imgs/tictactoe%20p2.jpg)