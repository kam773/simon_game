# Simon game
https://codepen.io/kam773/pen/BxpoZd
# The Project
A web replication of the classic game of memory - Simon! Built with HTML, CSS, and Javascript using jQuery as part of the freeCodeCamp Front End Curriculum.

After turning the game on and starting, users are displayed a sequence of tones and lights, with the game requiring the player to repeate the series to progress to the next level. Levels increase the sequence by one step each round, and the tempo with which the game displays the sequence increases halfway throught the game.
![simon game](https://user-images.githubusercontent.com/33424405/43583432-cd0f2442-965f-11e8-8165-40604be3759c.png)
# The Logic
Once the game loads I generate a new game sequence - an array with 20 strings of either "red", "green", "blue", or "yellow". Whenever the game starts or a new round is started, the game plays through the sequence up until the current round the users is on. Panels are lit up by adding and removing a 'highlight' class on a setTimeout delay, and one of four sounds is played using HTML5 audio - this occurs either when the game plays through the new round sequence or when the user selects a panel when it is his/her turn to select panels to to complete the current round's sequence.
