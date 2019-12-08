# Iconic Albums Covers - The Memory Game!
<img src="https://media.giphy.com/media/lOCD8V992TQSk/source.gif" width="100%">

## Description
Can you remember all of these classic album covers? Can you beat your own score? Try my [album memory game](https://album-memory.netlify.com/)!

## Rules
To start your game, click [here](https://album-memory.netlify.com/). All cards are facing the other way so that the images are not visible, mixed and aligned. You reveal two cards by clicking on them and if they match you may continue, otherwise the cards are hidden again. You may then flip two cards again and so on ... The aim of the game is to try to memorize the location of different cards and when the you  put face up successively two identical cards forming the pair you win them. The game is over when all pairs were found. 

## Built with
- HTML
- CSS
- Javascript

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Testers
- [Oskar Joss](https://github.com/OskarJoss)
- [Betsy Alva Soplin](https://github.com/milliebase)
- [Victor Ljungblad](https://github.com/Ljungblad)

## Author
Henric Björkvall

## Code review 
By [Alexander Gustafsson Flink](https://github.com/alexandergustafssonflink)

- on scripts.js:1: The cards array contains the different cards twice. Might make the code more dynamic if you instead used a function to duplicate the objects in the array. 

- on scripts.js:36: The function description says that it creates an image tag, but seems to create a div as well

- on index.html:40: You seem to calla functions.js-file, but no such file exists

- on script.js:70: Theres is no description to the flipCard-function

- on script.js:120: Theres is no description to the resetBoard-function

- Keep on rockin' in the free world
