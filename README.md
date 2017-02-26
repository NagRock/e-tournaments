# e-Tournaments

This project allows to create service that allows users to create and manage tournaments. Rules of tournament is set. 
Each participant is playing with each other. Participant is rewarded 3pt for victory, 1pt for for draw, and 0pt for 
lose. In case two participants has same amounts of points, small points matter.  

## Features

### Creating tournament
User click create new tournament. Form is displayed. User fills name of the tournament, participants and clicks create. 
Two links are generated. One is used for managing tournament and the other is used to view tournament.

### Viewing tournament
User enters page from viewing link (generated during tournament creation). User is able to see current table of 
participants. Each row representing one participant user is able to see number representing number of matches played, 
number of points gathered so far, small points lost and won. Table is sorted, so winning players are on top.\
On seperate view user can see a list of played matches in chronological order (date of addition not modification).

### Managing tournament
User enters page from viewing link (generated during tournament creation). In this view user can add, update, or remove 
matches. If user tries to add, previously added match, user will not be allowed and instead will be asked if user wants 
to modify existing match. If so, user will be moved to update match view (it does not change the date of creation).
