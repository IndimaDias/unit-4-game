# Crystal Collector
Repository for Crystals Collector game

## Web-page : https://indimadias.github.io/unit-4-game/

### Introduction

Another fun game to reach the total by guessing the random numer hidden in the crystals and win

### Instructions

When App is loaded a random no is generated by the application for the player to guess. 
Clik the "Rules" button to view the ruels of the game
clicking each crystal would add to the total
If total and pre generated number tallys player wins
If total exceeds the pre generated no player lose

### Problem

In this game the payer has to guess the answer with nos
 
Here's how the app works:


There will be four crystals displayed as buttons on the page.
The player will be shown a random number at the start of the game.

When the player clicks on a crystal, it will add a specific amount of points to the player's total score. 


Your game will hide this amount until the player clicks a crystal.
When they do click one, update the player's score counter.


The player wins if their total score matches the random number from the beginning of the game.
The player loses if their score goes above the random number.

The game restarts whenever the player wins or loses.


When the game begins again, the player should see a new random number. Also, all the crystals will have four new hidden values. Of course, the user's score (and score counter) will reset to zero.


The app should show the number of games the player wins and loses. To that end, do not refresh the page as a means to restart the game.

The random number shown at the start of the game should be between 19 - 120.
Each crystal should have a random hidden value between 1 - 12.

### Approach    

This web application dynamically generate nos for the crystals and number to tally randomly. 
The math random funtion is used in this case

Jquery libraries are used in this application. 

Add number hidden to the total every time a crystal is clicked.
compare total and main number generated.
If nos equal user wins
If total less than the main allow user to continue
If total exceeds main player looses. 
Win or loose ask player if wants to play again
if yes restart game

A modal type is used for user confirmation messages 
