## Diary WebAPP Ludo - Project 3
 
### Day 1 - *31 Jan*
We got together as a group and started sharing our thoughts and ideas for the project. We decided to use Stephans code instead of our own to focus more on the tasks we had ahead of us and knowing we had a fully working code.

### Day 2 - *Feb 1*
Started off by creating a board on DevOps to easier assign roles to members of the group. But also to set small milestones and to get an overall picture of what we have to do to get a fully working WebApp. Each one of us started digging into our role in the project. We added a function in DevOps that shows the results and statistics for the builds and tests created for the project. 

### Day 3 - *Feb 4*
Some of us started off with CSS and HTML and the visuals of the Ludo game.
One of the other things we did today was to give the tiles an unique ID. We did this by looking at the gameboard and by studying the Gameboard.cshtml code. We added the correct ID for the right tile. We started with Dependency Injection and gamelogic for the game but that resulted with a mergeconflict at the end of the day.

### Day 4 - *Feb 5*
We’ve given the pieces an unique ID as well as creating a script linking it to a button.This made it possible to click on a piece and get the ID for it. This will later on be helpful to move the piece the player wants to move. If the piece was moved to the gameboard out of the nest, the piece would simply be removed from the nest and added to the gameboard.  We also made a IF-statement so that the dots on the dice showed the right dots, if we told the dice to roll 5, the dice showed 5 dots. 
We continued adding logic and looking through the already implemented logic but also adding more Dependency Injection.

### Day 5 - *Feb 6*
We added Continuous Deployment to DevOps for our API. Later on we started building our interface for the "New Game" function, by pressing the New Game-button you now have the opportunity to chose how many players you want to play with. After that you can chose the name and color of the player. 

### Day 6 - *Feb 7*
The day started of by changing the form where you enter the players name and color. We now have a button you have to press to submit the player to the API and this has to be done for each player so that we don't send all players and the same time to the API. We've updated the Index page by making it look more up to date. By using Javascript we added drop-down animations for the clickable text, for example, by clicking on *Created by* will result in a text dropping down showing the name of the creators (us). We then added 2 Get-methods in  *Controllers* that gets all the essential info (pieceID, playerID etc.) to the gameboard.

### Day 7 - *Feb 8 - Feb 10*
Added logging to Controller aswell as when you add a player it will show up under *Added Players*.

### Day 8 - Feb 11
With the API basically done we will now move on to making the game playable. We tried to get the position of a specific piece from a player but not the result we were looking for. So most of the day were spent on forums to find a soluton for this. UnitTests were also added to the project.

### Day 9 - *Feb 12*
We started of where we left of yesterday, by trying to get information(position) from a piece. We also went back to the gameboard and "implementing" the game logic to the visible gameboard. For example, we want to move pieces out to the gameboard, for now we can only hardcode it to move to a specific tile. Fixed some of-by-one errors and changed a few lines of code of html to razor.

### Day 10 - *Feb 13*
We had a small breakthrough in moving the pieces out to the gameboard. We added incomplete functions that removes the pieces out of the nest, this happens after you roll the dice and press "Move Piece". We are still working on this part. The interface has been slightly updated by adding colors to the player's name, so if you chose the color red, your name will be red. Our javasript has now basically been completely removed and replaced by razor, simply because we realized that we didn't need that much javascript in our project (but we also got some feedback from out teacher). Smaller things like html code, SOLID and changes to our code was also added.

### Day 11 - *Feb 14*
One of the things we started with was to make the website more responsive to different devices. For example if you use a mobile device, we want the buttons and the layout to adapt to the screen so the buttons/text doesn't overlap with eachother. We also made the website look better when you make the window bigger and smaller. And just like yesterday we did another small breakthrough in how to move the gamepieces on the board.

### Day 12 - *Feb 15*
After many days of working in school and outside of school we seem to be getting closer to the end of the project. Today we started looking at the VG criterias to see if we can add anything more to the project. We decided to add localization so that the Index/ can be translated to different languages. Everything from entering the website, creating a game and joining a game, to actually playing the game seem to be working fine now. We fixed minor bugs and fixes to the code, for example the dice could be rolled numerous times before you move your piece. The website was slighty updated by making it more responsive to mobile users, so that not only the Index is adapted to the screens but the *Add Player* page adapts aswell. 
You can now win the game by making all your 4 pieces enter goal, when a piece reaches goal it will automatically be removed from the dropdown menu *Select Piece* so that you can't chose that piece again.

### Day 13 - *Feb 18*
A server was set up on the weekend that logs everything (IPs, creating games, adding players, etc) that happens on the website. We ran into a small problem with the compatability between Chrome and Mozilla Firefox, the text was overlapping in Firefox but worked fine in Chrome. This was fixed by adding a webkit/-moz to our code making it compatible with other browsers. We expect that this will be the last day working on the project so we are going to do some finishing touches. We've finished most of our documentation and added all the necessary .md files that is needed for a VG grade. The code is cleaned up and fully functioning. 
