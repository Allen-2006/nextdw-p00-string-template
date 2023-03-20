# Project 00 For NeXT CS
### Class Period: 5
### Name0: Allen Fertidos
#### Selected Game: Wordle
---

### How To Play
Explain how to play your game. Include any keyboard and/or mouse commands, game objectives, etc.

#### The mouse is used to interact with the buttons on the introduction screen. The rules button brings you to an overview of the game mechanics and how to start a new game/return to menu. Apart from the buttons, all other input is through the keyboard. The game is played by using the alphabet as well as a placeholder to input possible guesses. The enter key is used to try a guess. The objective of the game is to guess a 5 letter word in 6 tries by using hints given after every guess.

---

### Features
List all the game features you were able to implement.
#### 
- A way to visually update the display of letters in order to hint the user towards the correct answer. (After a guess, if a letter is in the correct spot, it will turn green. If its in the word however not in the correct spot, it will turn blue.)
- The user is prompted when a guess is valid or invalid through a outputted message which appears for an interval of time.
- The high score box reflects the users current high score in a scale from 0-100 in multiples of 16.
- Created 3d looking buttons in order to visually stimulate the user before playing what is a pretty simple game regarding its visual elements.
- Allowed a hyphen input to work as a placeholder for the users.
- Implemented some fun images to present to the user as they have won or lost.
- Allowed both keyboard and mouse input throughout the game.
- Devised a procedure in conjunction to the update state feature which makes sure that only the amount of letter x in the answer to be updated if there were to be more x's in the guess.
- Implemented a 3d look to all text as fonts werent available.



---

### Changes
What changed about your game after the design phase? Separate changes that occurred after the feedback round and changes that occurred during programming.

####

-After the feedback round I changed my objectives regarding in game features and focused on making one unique feature as well as a couple others instead of creating an arcade style game with multiple modes. Such as focusing on making cool buttons and creating a scoring system instead of adding a timed mode.

-While I was programming, I reckoned that sometimes it would be easier to access certain things as strings as (to my knowledge) there arent many array methods in processing. I also believed it would be easier to create a button class instead of making buttons with a very specific set of parameters. I also focused alot less on making individual class methods and focused more on getting the basics done with each class, and playing around with different things in the driver file. I also thought that it would be alot easier to create a bunch of variables to keep track of things.
