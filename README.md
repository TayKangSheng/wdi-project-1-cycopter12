[How to write readme - Markdown CheatSheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  
[How to write a good readme for github repo!](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)

# wdi-project-1-cycopter12(script.js)
Rapid typer is a game to test the player's typing speed on a designated time before it runs out. Player will earn a point for every correct word typed. If player types a wrong letter, the error count will increase.

You will need to declare the following functions in the global scope:
### updateTimer()
The updateTimer is the timer function of the game. Each player will get 30 seconds to type as many words as possible.

To make the timer work, you will need to add a button in HTML. This button will be disabled once it has been click and the count down starts.

If the timer reaches 0 seconds, the game will alert the player of their score and errors.

The timer can also be reset by creating a reset button. Upon clicking the button all scores, errors and time will be reset back to its original state. (score =0, errors = 0 and time = 30s)

### newWord()
This function will generate random words from the list array.

It should have a math random method.

Once a word is selected from the list, the word should be put into a loop to go through each letter of the word. Each letter will then need to be put into a <span>. Assigned a class to the span.

Lastly, the span will need to be put in the words class.

### keyCheck(e)
This function is to check the keys that are pressed to make sure the correct letters are being entered.

Make sure to create a global variable as a counter

If every correct letter typed, the counter will increase, the letter will be highlighted and move on to the next character of the word.   

Else, the error count will increase.

If all letters are typed, 1 point will be added to score.

A new word will be generated after each letter of a word has been completed. To do so, the words class will have to be restarted and run the newWord function again.

### function method for Name Space

Use the function method for Name Space. This is to protect your code and run the whole JS by just one function.

Make sure to return all functions and add an eventListener to load the DOM content.
### General Tips
Create a few variables to store information about the current state of the game for example, (var points =0, var seconds= 30)

Extra: It is optional but it would be cool to add some animations to your game to make it stand out! You can create an animation of a horse or race car to coordinate its movement based on your points increments.

### Author
Andre Mark The 

### Acknowledgment
Credit goes to current online multiplayer game, "Type Racer" for inspiration

Pixabay for awesome horse images
