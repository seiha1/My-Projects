## Trying to describe the update and changes I have made ##

- The changes will be first the difference from the original,
which was made for the edX 6.00 course that I am taking.

##
    The first game started pretty simple with just guessing a letter,
    no ability to guess the whole word! My first thought was to change this.
    I did so by adding in an if statement to check if the current user
    guess was equal to 1 if so then run the program as normal.
    I the guess length was as long as the secret word then,
    check if it is the word.
    
    This lead me to consider a bonus score amount, and really a total score!
    Which I have added in by making a bonusScore function.
    
    Other changes consist of the letterAvialable output being changed
    Now there is a - between the letter for easier reading
    
    I have added in some output text to the user
    Hoping this adds a bit more fun and interactiveness to the game
    I give the secretWord output more and also upcase it 
    so that it stands out!
    
##
    Output_update was hard to figure out since when the append has
    to happen within the if statement.... therefore if i place
    output_update outside the if statement it does not change 
    until the next time through
    problem happens when i try to reference the output_update 
    in the elif statement below. It didn't exist. So I know it looks 
    stupid to have it in both place but I cant figure out how to 
    make this 'prettier'
    
## 
    Really trying to understand the work flow part of git 
    Not being successful!
    Have done both a clone of a repo and the branch of the master 
    but I cant seem to figure out how it works other then making a new file
    and then not leetting me merge it back in
    OR at least I cannot figure it out
    
    
Jan 30 2015

## Made the switch to python v 3.4!

* This is my first successful attempt to convert one of my running v2 script
  to v3 script. And I have also made to different branches so that I can 
  keep working on and using python 2.7 for now. That is until the rest of the 
  world hops on board.
