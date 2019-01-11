# Pig Dice
### 09.01.2019
## By Perpetue Muhawenimana
### Description
 A simple dice game. Each turn, a player repeatedly rolls a die until either a 1 is rolled or the player decides to "stay":

* If the player rolls a 1, they score nothing and it becomes the next player's turn.
* If the player rolls any other number, it is added to their turn total and the player's turn continues.
* If a player chooses to "hold", their turn total is added to their score, and it becomes the next player's turn.

The first player to score 100 or more points wins.
### Setup/Installation Requirements
* Open CMD/Terminal
* git clone https://github.com/Perpetue/Project-Pig-Dice
* Open the index.html file with the browser of your choice
 and To access on this project, you have to use google chrome and text-editor.
## Specs

 | Behavior                                       |  Input | Output    |
 | ---------------------------------------------- | ------ | --------- |
 | Player rolls die to get a random number    | Click button      | 5      |
 | When player rolls 1, turn is over and lose all current points from turn  | 1 | Hide player's buttons, show other player's buttons  |
 | When player rolls any other number add to turn total | 3     | 3  |
 | Player can end turn by "staying", and turn total is added to banked total        | 12      | 27         |
 | First player to reach 100, wins     | 9      | 100 - You win!       |
## USER STORY
    As a user, I want to roll the dice when it's my turn to play in the game.
    As a user, I want to see the score I get for each roll of the dice I make in the game.
    As a user, I want to see my cumulative score for each round I play in the game. For example, if I roll the scores 2-6-3 consecutively, I should see my end score as 11.
    As a user, I want the option to hold my score when I'm satisfied with the points I've gained in a round of playing. The game should, therefore, add my held score to my most recent cumulative score.
    As a user, I want to be alerted when my dice rolls on number 1. This will help me know that I can't roll the dice until the alternate player takes their round.
    As a user, I need a way to know which player has won the game, which means they have scored 100 points before the alternate player.
## Link to live site on GitHub Pages
    https://github.com/Perpetue/Project-Pig-Dice

#### Support and contact details
   Please feel free to contact muperpety@gmail.com if you have any issues or questions, ideas or concerns.
# Technologies Used
**Main Languages used:**
* HTML
* CSS
* JavaScript
* jQuery
* Bootstrap
**Other Technologies:**
* Terminal
* visual studio code
## License
This project is licensed under the MIT License
**_Perpetue Muhawenimana_** Copyright (c) 2019

