For those frustrated by chess.com's recent Review Game changes, the following is a set of instructions to allow you to once again see both the 'Move Played' and 'Best Move' Bubbles at the same time when reviewing your games.

1). Install the 'TamperMonkey' browser extension.

2). Enable developer mode: Go to;    chrome://extensions    (there's a button in the top right corner)

3). Click on the TamperMonkey extension icon and select 'Create a new script...'

4). Copy the code linked here and replace what's shown in the TamperMonkey editor with it.
https://raw.githubusercontent.com/edcoded/Chess.com/main/Chess.com%20Move%20Bubble%20Modification%20TamperMonkey%20Script

5). *** IMPORTANT *** go to a game, click 'Start Review' and then once you go get to Move 1 (move=1) REFRESH THE PAGE! If nothing happens, click on the TamperMonkey icon again and make sure the script is Enabled. 

6). This should create the space required to see both Move Bubbles at the same time going forward, without the need for incessant scrolling. (to begin with the extra space is a little redundant as there often isn't a best move to show in the opening but you'll just have to live with that - also if you've played the Best Move during the game)

7). The Code; make sure that // ==UserScript== is on line 1 of the TamperMonkey editor. Have a look here if you need clarification: https://github.com/edcoded/Chess.com/blob/main/game%20review%20both%20bubbles.png

8). Happy Reviewing!
