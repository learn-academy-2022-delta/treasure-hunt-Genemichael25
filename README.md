# ๐ฐ React Treasure Hunt Game

### ๐ค Remember
- Pseudocode!!
- Ask clarifying questions

### ๐ User Stories
- As a user, I can see a page with a 3 by 3 grid board game with a question mark in each square.
    Branch: grid

- As a user, when I click on one of the question marks an alert appears with the index position of that question mark in the array.
    Branch: alert
    -Passed index into square component
    -made an onclick method that alerts user to what index of the box

- As a user, when I click on one of the question marks instead of the alert the question mark turns into a tree emoji.
    Branch: tree-emoji
    -Destructured board from state so that we could update a single instance to be a tree emoji when clicked
    (done)

- As a user, if I select the winning square the question mark will become a treasure emoji and if I select the losing square the question mark will become a bomb emoji.
    Branch: treasure-bomb
    (done)

- As a user, I can click on a โPlay Againโ button that will restart the game.


- As a user, I can see a counter that shows how many guesses I have left. The counter starts at 5 and decrements one every time I click on a square that is not the treasure nor the bomb.


- As a user, I can see a message informing me that I won the game if I select the square that contains the treasure.


- As a user, I can see a message informing me that I lost the game if I select the square that contains the bomb.


- As a user, I cannot continue to play the game after I win or lose.
- As a user, I can see a message informing me that I lost the game when I run out of turns (the counter reaches zero).


### ๐ Stretch Goals
- Consider how to handle a situation where the bomb and the treasure are at the same index.
